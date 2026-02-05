---
feature_text: |
  
feature_image: "/assets/IMG_0238_Fotor.jpeg"
excerpt: ""
aside: true
---

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image Gallery</title>
  <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            padding: 10px;
        }
        .gallery-item {
            flex: 1 1 calc(25% - 20px);
            box-sizing: border-box;
            position: relative;
        }
        .gallery-item img {
            width: 100%;
            height: auto;
            border-radius: 8px;
            display: block;
        }
        @media (max-width: 768px) {
            .gallery-item {
                flex: 1 1 calc(50% - 20px);
            }
        }
        @media (max-width: 480px) {
            .gallery-item {
                flex: 1 1 100%;
            }
        }
    </style>
</head>
<body>

<h1>Image Gallery</h1>
<div class="gallery">
    <div class="gallery-item">
        <img src="/assets/IMG_1532.jpeg" alt="Image 1">
    </div>
    <div class="gallery-item">
        <img src="/assets/IMG_2553.jpeg" alt="Image 2">
    </div>
   
    <!-- Add more images as needed -->
</div>

</body>

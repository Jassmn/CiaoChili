<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Image Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            background-color: #f4f4f4;
        }
        h1 {
            text-align: center;
            margin-top: 20px;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 10px;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }
        .gallery img {
            width: 100%;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }
        .gallery img:hover {
            transform: scale(1.05);
        }
    </style>
</head>
<body>

 <h1>My Image Gallery</h1>

 <div class="gallery">
      
<img src="https://github.com/Jassmn/CiaoChili/blob/main/IMMG_0001.jpeg?raw=true" alt="Image 1">

      
<img src="https://github.com/Jassmn/CiaoChili/blob/main/IMMG_0002.jpeg?raw=true" alt="Image 2">

  
 <img src="https://github.com/Jassmn/CiaoChili/blob/main/IMMG_0003.jpeg?raw=true" alt="Image 3">

     
 <img src="https://github.com/Jassmn/CiaoChili/blob/main/IMMG_0004.jpeg?raw=true" alt="Image 4">

  <img src="https://github.com/Jassmn/CiaoChili/blob/main/IMMG_0005.jpeg?raw=true" alt="Image 5">

   <img src="https://github.com/Jassmn/CiaoChili/blob/main/IMMG_0006.jpeg?raw=true" alt="Image 6">

  <img src="https://github.com/Jassmn/CiaoChili/blob/main/IMMG_0007.jpeg?raw=true" alt="Image 7">

 <img src="https://github.com/Jassmn/CiaoChili/blob/main/IMMG_0008.jpeg?raw=true" alt="Image 8">

 <img src="https://github.com/Jassmn/CiaoChili/blob/main/IMMG_0009.jpeg?raw=true" alt="Image 9">
    </div>

</body>
</html>

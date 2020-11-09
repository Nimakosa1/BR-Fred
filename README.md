<!DOCTYPE html>
<html>
<head>
   <title> Try It Yourself </title>
   <style type="text/css">
      * {
         box-sizing: border-box;
      }
      html, body {
         margin: 0;
         padding: 0;
      }
      .image-container {
         margin: 0 auto; /* center the image containers */
         width: 80%;
         box-shadow: 0 15px 30px rgba(0,0,0,0.30), 0 11px 8px rgba(0,0,0,0.22); /* material box shadow */
         margin-bottom: 20px;
      }
      /* make the images responsive */
      img {
         width: 100%;
         height: auto;
      }
      .image-description {
         padding: 0 15px 15px 15px;
         text-align: center;
      }
   </style>
</head>
<body>   
   <h1> CSS Image Gallery </h1>
   <div class="gallery">
       	
      <div class="image-container">
         <img src="images/road.jpg" />
         <p class="image-description"> Lorem ipsum dolor sit amet. </p>
      </div>
      
      <div class="image-container">
         <img src="images/snow.jpg" />
         <p class="image-description"> Lorem ipsum dolor sit amet. </p>
      </div>
      
      <div class="image-container">
         <img src="images/city.jpg" />
         <p class="image-description"> Lorem ipsum dolor sit amet. </p>
      </div>
      
      <div class="image-container">
         <img src="images/woman.jpg" />
         <p class="image-description"> Lorem ipsum dolor sit amet. </p>
      </div>
      
   </div>
</body>
</html>

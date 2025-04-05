<!DOCTYPE html>
<html lang = "en">
   <head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>
   Wallpaper Finder
</title>
<style>
   body{
       font-family: Arial, sans-serif;
       margin: 0;
       padding:0;
       background-color: #f4f4f4;
   }
   header
{
   background-color: #333;
   color: white;
   padding: 1em;
   text-align: center;
}
nav{
   display: flex;
   justify-content: center;
   background:#444 ;
   padding: 10px;
}
nav a{
   margin: 0 15px;
   text-decoration: none;
   color: white;
   font-size: 18px;
   padding: 10px;
}
nav a:hover{
   background: #007BFF;
   border-radius: 5px;
}
.container{
   text-align: center;
   padding: 50px;


}
.gallery img {
   width: 100%;
   height: auto;
   border-radius: 5px;
   box-shadow: 0 4px 8px rgba(0, 0,0, 0.2);
   transition: transform 0.3s ease;
}
.gallery img :hover{
   transform: scale(1.05);
}
.wallpaper-table{
   width: 80%;
   margin: 20px auto;
   border-collapse: collapse;
   background: white;
   box-shadow: 0 4px 8px rgba(0, 0,0, 0.2);
}
.wallpaper-table th, .wallpaper-table td{
   padding: 10px;
   text-align: center;
   border: 1px solid #ddd;
}
.wallpaper-table th{
   background: #333;
   color: white;
}
</style>
   </head>
   <body>
       <header>
           <h1>
               Wallpaper Finder
           </h1>
       </header>
       <nav>
           <a href="#">Home</a>
           <a href="#">Trending</a>
           <a href="#">Categories</a>
           <a href="#">contact</a>
       </nav>
           <div class="container">
               <h2>Find your perfect  Wallpaper</h2>
               <p>Explore a wide collection of high-quality Wallpapers.</p>
           </div>
           <div class="gallery">
               <img src="https://i.pinimg.com/736x/0d/75/45/0d7545ba7637f8646218be92016b69a2.jpg" alt="Wallpaper 1">
               <img src="https://i.pinimg.com/474x/6a/1b/4b/6a1b4bb3cae28a3660304db3ed27e583.jpg" alt="Wallpaper 2">
               <img src="https://i.pinimg.com/736x/0a/f5/d2/0af5d2ca5005cc0c80846ac16f3e9854.jpg" alt="Wallpaper 3">
               <img src="https://i.pinimg.com/474x/cb/02/db/cb02dbc732e27b8135ef5b65a81c8e45.jpg" alt="Wallpaper 4">
           </div>
<table class="wallpaper-table"?>
   <tr>
       <th>Wallpaper Name</th>
       <th>Categories</th>
       <th>Resolution</th>
   </tr>
   <tr>
       <td>Nature Bliss</td>
       <td>Nature</td>
       <td>1980*1080</td>
   </tr>
   <tr>
       <td>City Lights</td>
       <td>Urban</td>
       <td>2560*1440</td>
   </tr>
   <tr>
       <td>Abstract Art</td>
       <td>Abstract</td>
       <td>3840*2160</td>
   </tr>
</table>
     
   </body>
       </html>




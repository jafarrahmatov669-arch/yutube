<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mini YouTube</title>
<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#f1f1f1;
}
header{
    background:red;
    color:white;
    padding:15px;
    font-size:25px;
    font-weight:bold;
}
.container{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:20px;
    padding:20px;
}
.card{
    background:white;
    border-radius:10px;
    overflow:hidden;
    box-shadow:0 2px 8px rgba(0,0,0,.2);
}
.card img{
    width:100%;
    height:200px;
    object-fit:cover;
}
.card h3{
    padding:10px;
}
</style>
</head>
<body>

<header>▶ MyTube</header>

<div class="container">

<div class="card">
<img src="https://picsum.photos/500/300?1" alt="">
<h3>Chiroyli Tabiat</h3>
</div>

<div class="card">
<img src="https://picsum.photos/500/300?2" alt="">
<h3>Shahar Manzarasi</h3>
</div>

<div class="card">
<img src="https://picsum.photos/500/300?3" alt="">
<h3>Texnologiya Rasmi</h3>
</div>

<div class="card">
<img src="https://picsum.photos/500/300?4" alt="">
<h3>Motivatsiya</h3>
</div>

</div>

</body>
</html># yutube

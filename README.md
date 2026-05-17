# galeria-mea< 
!DOCTYPE html>
<html lang="ro">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Galeria Mea</title>

<style>

body{
    margin:0;
    background:#111;
    color:white;
    font-family:Arial;
}

header{
    text-align:center;
    padding:25px;
    font-size:35px;
    font-weight:bold;
    background:black;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
    gap:30px;
    padding:30px;
}

.card{
    background:#1c1c1c;
    border-radius:20px;
    overflow:hidden;
}

.card img{
    width:100%;
    height:300px;
    object-fit:cover;
}

.info{
    padding:20px;
}

.title{
    font-size:24px;
    margin-bottom:10px;
    font-weight:bold;
}

.description{
    color:#bbb;
}

</style>
</head>

<body>

<header>
GALERIA MEA
</header>

<div class="gallery">

<!-- POZA 1 -->

<div class="card">

<img src="poza1.jpg">

<div class="info">

<div class="title">
Titlu poză
</div>

<div class="description">
Aici scrii descrierea pozei.
</div>

</div>
</div>

<!-- POZA 2 -->

<div class="card">

<img src="poza2.jpg">

<div class="info">

<div class="title">
Altă poză
</div>

<div class="description">
Altă descriere.
</div>

</div>
</div>

</div>

</body>
</html>
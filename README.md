<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>TheAyazDesigns</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family: 'Poppins', sans-serif;
}

body{
  background:#0f0f0f;
  color:white;
}

/* NAVBAR */
nav{
  display:flex;
  justify-content:space-between;
  padding:15px 50px;
  background:black;
  position:sticky;
  top:0;
}

nav h1{
  color:gold;
}

nav a{
  color:white;
  margin:0 10px;
  text-decoration:none;
}

nav a:hover{
  color:gold;
}

/* HERO */
.hero{
  text-align:center;
  padding:80px 20px;
  background:linear-gradient(45deg,#000,#1a1a1a);
}

.hero h2{
  font-size:40px;
  color:gold;
}

.hero p{
  margin:10px 0;
}

.btn{
  padding:10px 20px;
  background:gold;
  color:black;
  border:none;
  margin-top:15px;
  cursor:pointer;
}

/* SECTION */
.section{
  padding:60px 20px;
  text-align:center;
}

.section h2{
  color:gold;
  margin-bottom:20px;
}

/* CARD */
.cards{
  display:flex;
  flex-wrap:wrap;
  justify-content:center;
  gap:20px;
}

.card{
  background:#1a1a1a;
  padding:20px;
  border-radius:10px;
  width:250px;
}

.card img{
  width:100%;
  border-radius:10px;
}

.price{
  color:gold;
  font-weight:bold;
  margin-top:10px;
}

/* FOOTER */
footer{
  background:black;
  text-align:center;
  padding:20px;
  margin-top:40px;
}

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>SMARTTECHUPHOLSTRY | Automotive Upholstery & Interior Customization</title>

<meta name="description" content="SMARTTECHUPHOLSTRY - Automotive Upholstery & Interior Customization in Eldoret, Kenya. Your Car. Our Craft.">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

html{
    scroll-behavior:smooth;
}

body{
    font-family:Arial, sans-serif;
    background:#fff;
    color:#111;
    line-height:1.6;
}

.container{
    width:92%;
    max-width:1150px;
    margin:auto;
}

/* HEADER */

header{
    position:fixed;
    top:0;
    left:0;
    right:0;
    z-index:1000;
    background:#050505;
    border-bottom:1px solid #c9a227;
}

nav{
    min-height:75px;
    display:flex;
    align-items:center;
    justify-content:space-between;
}

.logo{
    display:flex;
    align-items:center;
    gap:10px;
    color:white;
    text-decoration:none;
}

.logo-symbol{
    width:45px;
    height:45px;
    border:2px solid #d4af37;
    border-radius:10px;
    display:flex;
    align-items:center;
    justify-content:center;
    color:#d4af37;
    font-size:30px;
    font-weight:bold;
    font-style:italic;
}

.logo-text strong{
    display:block;
    font-size:15px;
    letter-spacing:1px;
}

.logo-text small{
    display:block;
    color:#d4af37;
    letter-spacing:3px;
    font-size:9px;
}

.nav-links{
    display:flex;
    gap:25px;
}

.nav-links a{
    color:#fff;
    text-decoration:none;
    font-size:13px;
    font-weight:bold;
}

.nav-links a:hover{
    color:#d4af37;
}

.quote-button{
    border:1px solid #d4af37;
    padding:10px 16px;
    color:#d4af37 !important;
}

.menu{
    display:none;
    color:#fff;
    font-size:28px;
}

/* HERO */

.hero{
    min-height:750px;
    padding-top:75px;
    display:flex;
    align-items:center;
    background:
        linear-gradient(rgba(0,0,0,.86),rgba(0,0,0,.72)),
        url("https://images.unsplash.com/photo-1503736334956-4c8f8e92946d?auto=format&fit=crop&w=1800&q=80")
        center/cover;
}

.hero-content{
    color:white;
    max-width:800px;
}

.eyebrow{
    color:#d4af37;
    font-size:12px;
    font-weight:bold;
    letter-spacing:3px;
    margin-bottom:18px;
}

.hero h1{
    font-family:Georgia,serif;
    font-size:clamp(50px,8vw,90px);
    line-height:1;
}

.hero h1 span{
    color:#d4af37;
}

.hero p{
    max-width:650px;
    margin:25px 0;
    color:#ddd;
    font-size:18px;
}

.buttons{
    display:flex;
    gap:15px;
    flex-wrap:wrap;
}

.btn{
    display:inline-block;
    padding:14px 24px;
    text-decoration:none;
    font-weight:bold;
    font-size:13px;
    border-radius:4px;
}

.gold{
    background:#d4af37;
    color:#000;
}

.outline{
    border:1px solid #d4af37;
    color:#fff;
}

.badges{
    margin-top:30px;
    display:flex;
    gap:20px;
    flex-wrap:wrap;
    color:#ddd;
    font-size:12px;
}

/* STRIP */

.strip{
    background:#111;
    color:white;
}

.strip-grid{
    display:grid;
    grid-template-columns:repeat(4,1fr);
}

.strip-item{
    padding:25px;
    text-align:center;
    border-right:1px solid #333;
}

.strip-item strong{
    color:#d4af37;
    margin-right:8px;
}

/* SECTIONS */

section{
    padding:90px 0;
}

.heading{
    text-align:center;
    max-width:700px;
    margin

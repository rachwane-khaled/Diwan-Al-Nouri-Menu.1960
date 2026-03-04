<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Diwan Al Nouri | Menu-1960</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700;900&family=Cormorant+Garamond:wght@400;600&family=Great+Vibes&display=swap" rel="stylesheet">

<style>
:root{
  --gold:#C6A75E;
  --dark:#1E1A17;
  --cream:#F8F1E5;
  --brown:#2C2118;
}

*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

body{
  background:linear-gradient(rgba(0,0,0,0.85), rgba(0,0,0,0.85)), url('https://images.unsplash.com/photo-1495474472287-4d71bcdd2085');
  background-size:cover;
  background-position:center;
  font-family:'Cormorant Garamond', serif;
  color:var(--cream);
}

.menu-wrapper{
  max-width:1000px;
  margin:60px auto;
  background:var(--dark);
  padding:60px 50px;
  border:1px solid var(--gold);
  box-shadow:0 0 40px rgba(198,167,94,0.4);
  position:relative;
}

.menu-wrapper::before{
  content:"";
  position:absolute;
  top:15px;
  left:15px;
  right:15px;
  bottom:15px;
  border:1px solid var(--gold);
}

.header{
  text-align:center;
  margin-bottom:50px;
}

.logo{
  font-family:'Great Vibes', cursive;
  font-size:64px;
  color:var(--gold);
  letter-spacing:3px;
}

.est{
  font-family:'Playfair Display', serif;
  font-size:14px;
  letter-spacing:4px;
  margin-top:10px;
  color:var(--cream);
}

.tagline{
  margin-top:20px;
  font-style:italic;
  font-size:18px;
  color:#ddd;
}

.section{
  margin-bottom:45px;
}

.section-title{
  font-family:'Playfair Display', serif;
  font-size:28px;
  color:var(--gold);
  margin-bottom:20px;
  text-transform:uppercase;
  letter-spacing:2px;
  border-bottom:1px solid var(--gold);
  padding-bottom:8px;
}

.menu-item{
  display:flex;
  justify-content:space-between;
  padding:12px 0;
  font-size:20px;
  border-bottom:1px solid rgba(255,255,255,0.08);
}

.menu-item span:first-child{
  letter-spacing:1px;
}

.price{
  color:var(--gold);
  font-weight:600;
}

.footer{
  text-align:center;
  margin-top:50px;
  font-style:italic;
  font-size:18px;
  color:var(--gold);
}

@media(max-width:768px){
  .menu-wrapper{
    padding:40px 25px;
  }

  .logo{
    font-size:42px;
  }

  .menu-item{
    font-size:16px;
  }
}

</style>
</head>

<body>

<div class="menu-wrapper">

  <div class="header">
    <div class="logo">Diwan Al Nouri</div>
    <div class="est">SINCE 1981 • TRIPOLI-HAY AL NOURI</div>
    <div class="tagline">A Refined Experience of Lebanese Coffee Heritage</div>
  </div>

  <div class="section">
    <div class="section-title">Hot Drinks</div>
    <div class="menu-item"><span>Espresso</span><span class="price">$0.90</span></div>
    <div class="menu-item"><span>Espresso Doppio</span><span class="price">$1.80</span></div>
    <div class="menu-item"><span>Lebanese Coffee</span><span class="price">$0.50</span></div>
    <div class="menu-item"><span>Turkish coffee</span><span class="price">$1.10</span></div> 
    <div class="menu-item"><span>Macchiato</span><span class="price">$1.70</span></div>
    <div class="menu-item"><span>Americano</span><span class="price">$2.75</span></div>
    <div class="menu-item"><span>Tea</span><span class="price">$1.10</span></div>
    <div class="menu-item"><span>Cappuccino</span><span class="price">$3.50</span></div>
    <div class="menu-item"><span>cortado</span><span class="price">$3.00</span></div>
    <div class="menu-item"><span>Flat white</span><span class="price">$3.50</span></div>
    <div class="menu-item"><span>Mocha</span><span class="price">$3.50</span></div>
    <div class="menu-item"><span>Latte</span><span class="price">$3.75</span></div>
    <div class="menu-item"><span>Latte Add flavours</span><span class="price">$4.50</span></div>
    <div class="menu-item"><span>Spanish Latte</span><span class="price">$4.00</span></div> 
    <div class="menu-item"><span>Latte Macchiato</span><span class="price">$4.50</span></div> 
    <div class="menu-item"><span>Hot Chocolate</span><span class="price">$2.50</span></div>
    <div class="menu-item"><span>Nescafe with milk</span><span class="price">$2.20</span></div>
    <div class="menu-item"><span>Nescafe with coffe mate</span><span class="price">$1.10</span></div>    
  </div>

  <div class="section">
    <div class="section-title">Cold drinks with coffee</div>
    <div class="menu-item"><span>Iced Amircano</span><span class="price">$3</span></div>
    <div class="menu-item"><span>Iced Latte</span><span class="price">$3</span></div>
    <div class="menu-item"><span>Latte Add Flavour</span><span class="price">$3.50</span></div>
    <div class="menu-item"><span>Spanish Iced Latte</span><span class="price">$3.50</span></div>
    <div class="menu-item"><span>Iced Tea</span><span class="price">$3.00</span></div>
    <div class="menu-item"><span>Smoothies</span><span class="price">$3.50</span></div>
    <div class="menu-item"><span>Iced mocha</span><span class="price">$3.25</span></div>
    <div class="menu-item"><span>Water</span><span class="price">$0.55</span></div>
    <div class="menu-item"><span>Espresso Martini</span><span class="price">$4.50</span></div>
  </div>

  <div class="section">
    <div class="section-title">Cold Drinks Without Coffee </div>
    <div class="menu-item"><span>Sparkling Water V7</span><span class="price">$1.00</span></div>
    <div class="menu-item"><span>Pepsi</span><span class="price">$1.00</span></div>
    <div class="menu-item"><span>Juice Extra</span><span class="price">$1.00</span></div>
    <div class="menu-item"><span>Tamarind</span><span class="price">$1.00</span></div>
  </div>

  <div class="section">
    <div class="section-title">Frappe</div>
    <div class="menu-item"><span>Vanilla Frappe</span><span class="price">$4.00</span></div>
    <div class="menu-item"><span>Caramel</span><span class="price">$4.00</span></div>
    <div class="menu-item"><span>Mocha Frappe</span><span class="price">$4.00</span></div>
  </div>

   <div class="section">
    <div class="section-title">Milkshake</div>
    <div class="menu-item"><span>Vanilla</span><span class="price">$4.00</span></div>
    <div class="menu-item"><span>Chocolate</span><span class="price">$4.00</span></div>
    <div class="menu-item"><span>Strawberry</span><span class="price">$4.00</span></div>
    <div class="menu-item"><span>Cookies</span><span class="price">$4.50</span></div>
    <div class="menu-item"><span>Lotus</span><span class="price">$4.50</span></div>
  </div>

  <div class="section">
    <div class="section-title">Shisha</div>
    <div class="menu-item"><span>Appel</span><span class="price">$5</span></div>
    <div class="menu-item"><span></span><span class="price">$5</span></div>
    <div class="menu-item"><span></span><span class="price">$5</span></div>
    <div class="menu-item"><span></span><span class="price">$5</span></div>
    <div class="menu-item"><span>......</span><span class="price">$5</span></div>
  </div>
  

  <div class="footer">
    "Where Tradition Meets Elegance"
  </div>

</div>

</body>
</html>

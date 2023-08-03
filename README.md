<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Cafe Menu</title>
    <style>
          body {
      background: url(https://images.unsplash.com/photo-1447933601403-0c6688de566e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8Y29mZmVlJTIwYmVhbnxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80);
      background-repeat:no-repeat;
      background-size: cover;
      background-color: burlywood;
      margin: 0px;
      padding: 0px;
      height: 111vh;
      
    }

    h1, h2 {
      text-align: center;
      font-family: Impact, sans-serif;
      font-weight: 100;
      font-size: 200%;
    }

    p {
      text-align: center;
      font-family: sans-serif;
      line-height: 0.1;
    }

    .inlar {
      display: flex;

    }

    .menu {
      max-width: 600px;
      background-color: burlywood;
      margin-left: auto;
      margin-right: auto;
      background-blend-mode: thicker;
}
    
    .item {
      text-align: left; 
      width: 75%; 
      padding-left: 15px;
      font-size: 120%;
    }

    .price {
      text-align: right; 
      width: 25%; 
      padding-right: 15px;
      font-size: 120%;
    }

    .secst {
      



    }

    @media (max-width: 900px) {
      body {
      background: url(https://images.unsplash.com/photo-1447933601403-0c6688de566e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8Y29mZmVlJTIwYmVhbnxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80);
      background-repeat:no-repeat;
      background-size: cover;
      background-color: burlywood;
      margin: 0px;ss
      padding: 0px;
      height: 110vh;
      }
    }

    @media (max-width: 700px) {
      body {
      background: url(https://images.unsplash.com/photo-1447933601403-0c6688de566e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Mnx8Y29mZmVlJTIwYmVhbnxlbnwwfHwwfHx8MA%3D%3D&w=1000&q=80);
      background-repeat:no-repeat;
      background-size: cover;
      background-color: burlywood;
      margin: 0px;
      padding: 0px;
      height: 115vh;
      border-color: brown;
      }
      .menu {
        max-width: 90%;
      }
    }
</style>
  </head>


  <body>
    <div class="menu">
      <main>
        <h1 style="padding-top: 20px; font-size: 240%;">CAFE ANDREWS</h1>
        <p style="font-style: italic; line-height: 1;">Est. Today</p>
        <hr style="text-align: auto; width: 90%; height: 3px; background-color: brown; border-color: brown;">
        <section class="secst">
          <h2 style="margin-bottom: 1%;">Coffee</h2>
          <img src="https://www.freepnglogos.com/uploads/coffee-png/coffee-fivesibes-19.png" style="width: 60px; height: 66px; margin-left: auto; margin-right: auto; display: block; margin-bottom: 25px;">
            <article class="inlar">
              <p class="item">French Vanilla</p>
              <p class="price">3.15</p>
            </article> 
            <article class="inlar">
              <p class="item">Unicorn extract</p>
              <p class="price">5.35</p>
            </article>
            <article class="inlar">
              <p class="item">Americano</p>
              <p class="price">2.80</p>
            </article>
            <article class="inlar">
              <p class="item">Mocha</p>
              <p class="price">3.15</p>
            </article>
            <article class="inlar">
              <p class="item">Espresso</p>
              <p class="price">2.00</p>
            </article>
            <h2 style="margin-top: 5%; margin-bottom: 0%;">Desserts</h2>
          <img src="https://images.vexels.com/media/users/3/252259/isolated/lists/23ffdf161baeb254c908d76ee0c862e4-pumpkin-pie-color-stroke.png" style="width: 80px; height: 80px; margin-left: auto; margin-right: auto; display: block; margin-bottom: 25px; margin-top: 0%;">
          <article class="inlar">
              <p class="item">NY Cheesecake</p>
              <p class="price">6.15</p>
            </article> 
            <article class="inlar">
              <p class="item">Scone</p>
              <p class="price">2.40</p>
            </article>
            <article class="inlar">
              <p class="item">Pumpkin Pie</p>
              <p class="price">6.15</p>
            </article>
            <article class="inlar">
              <p class="item">Apple Pie</p>
              <p class="price">6.15</p>
            </article>
            <article class="inlar">
              <p class="item">Cinnamon Roll</p>
              <p class="price">4.45</p>
            </article>
             <hr style="text-align: auto; width: 90%; height: 3px; background-color: brown; border-color: brown; margin-top: 5%;">
             <p style="margin-top: 10%; padding-bottom: 5%;">123 Coffe Land Way</p>


        </section>
      </main>
    </div>
  </body>
</html>

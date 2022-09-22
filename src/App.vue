<template>

  
    <h1>COMIDA RÁPIDA MAGÜIS</h1>
    <br/>
    <nav>
    <ul class="list">
      <li><a href="#">Hamburguesas</a></li>
      <li><a href="#">Pollo frito</a></li>
      <li><a href="#">Bebidas</a></li>
  </ul>
</nav>

  <div class="card-principal">

    <div class="card1">
  <div class="card-h">
    <div class="card_landing">
      <p class="title">Hamburguesa</p>
      <slot>
      <img src="https://www.pequerecetas.com/wp-content/uploads/2013/07/hamburguesas-caseras-receta.jpg" alt="Hamburguesa" slot="Hamburguesa">
    </slot>
    </div>
    <div class="card_info">
        </div>

        <div class="content">
            <p class="titulo">Tradicional</p>
            <p class="precio">$40.00</p>
            <a class="compra" href="" >Comprarlo</a>
        </div>

    </div>

   

    <div class="card-p">
      <div class="card_landing">
        <p class="title">Papas fritas</p>
        <slot>
        <img src="https://mejorconsalud.as.com/wp-content/uploads/2013/07/patatas-fritas-.jpg" alt="Papas fritas" slot="Papas fritas">
      </slot>
      </div>
      <div class="card_info">
          </div>
          
  
          <div class="content">
              <p class="titulo">Con mayonesa y captsup</p>
              <p class="precio">$20.00</p>
              <a class="compra" href="" >Comprarlo</a>
          </div>
  
      </div>
  </div>

  <br/>

  <div class="card-pr">
    <div class="card_landing">
      <p class="title">Pizza de pepperoni</p>
      <slot>
      <img src="https://babycocina.com/wp-content/uploads/2021/02/pizza-pepperoni.jpg" alt="Pizza pepperoni" slot="Pizza pepperoni">
    </slot>
    </div>
    <div class="card_info">
        </div>
        

        <div class="content">
            <p class="titulo">Con salsa y captsup</p>
            <p class="precio">$15.00</p>
            <a class="compra" href="" >Comprarlo</a>
        </div>

    </div>

  </div>
  <br />

<div class="card2">
<div class="card-r">
  <div class="card_landing">
    <p class="title">Refresco Coca-Cola</p>
    <slot>
    <img src="https://as01.epimg.net/diarioas/imagenes/2021/07/12/actualidad/1626075232_785386_1626075400_noticia_normal_recorte1.jpg" alt="Coca-Cola" slot="Refresco coca-cola">
  </slot>
  </div>
  <div class="card_info">
      </div>
      

      <div class="content">
          <p class="titulo">Vaso chico</p>
          <p class="precio">$25.00</p>
          <a class="compra" href="" >Comprarlo</a>
      </div>

  </div>

  <br/>


<div class="card-hd">
  <div class="card_landing">
    <p class="title">Hot Dog</p>
    <slot>
    <img src="https://dam.cocinafacil.com.mx/wp-content/uploads/2019/04/hot-dog-aderezo-tocino.png" alt="Hot Dog" slot="hot dog">
  </slot>
  </div>
  <div class="card_info">
      </div>
      

      <div class="content">
          <p class="titulo">Todos los ingredientes</p>
          <p class="precio">$35.00</p>
          <a class="compra" href="" >Comprarlo</a>
      </div>

<br/>

      <div class="card-tp">
        <div class="card_landing">
          <p class="title">Tacos al pastor</p>
          <slot>
          <img src="https://www.comedera.com/wp-content/uploads/2017/08/tacos-al-pastor-receta.jpg" alt="Tacos al pastor" slot="tacos al pastor">
        </slot>
        </div>
        <div class="card_info">
            </div>
            
      
            <div class="content">
                <p class="titulo">Orden de 6 tacos</p>
                <p class="precio">$40.00</p>
                <a class="compra" href="" >Comprarlo</a>
            </div>
      
        </div>
      </div>
      <br />
      
  </div>

  <div class="footer">
    <h1>Contactanos ya!!</h1>
    <h2>Teléfono: 55 687 962 08</h2>
    <h2>e-mail: comidarapidama@gmail.com</h2>
  </div>

</template>

<style scoped>

  body{
    background-color: rgb(250, 250, 99);
  }

  h1 {
    text-align: center;
    color: black;
  }
  h2  {
    color: black;
  }
  img {
    width: 150px;
    height: 100px;
  }


  nav {

  text-align: center;
}
p {
  color: black;
}

nav ul {
  list-style: none;
  overflow: hidden; 
  text-align: center;
}

nav ul li {
  float: left;
  font-family: Arial, Helvetica, sans-serif;;
  font-size: 20px;  
  text-align: center;
}

nav ul li a {
  display: block; 
  padding: 20px;
  color: black;
  text-decoration: none;
}

nav ul li:hover {
  background: red;
}

.card-principal {
  float: left;
}
.card-h, card-p, card-pr, card-r, card-hd, car-tp {
  
  text-align: center;
  width: 200px;
	padding: 25px 0;
	margin: 0;
  color: black;

}

.compra{
    text-decoration: none;
    padding: 10px;
    font-weight: 50;
    font-size: 10px;
    color: #f4f741;
    background-color: #ee2c2c;
    border-radius: 6px;
    border: 2px solid #b60202;
  }
  .compra:hover{
    color: #ee2c2c;
    background-color: #ffffff;
  }


</style>

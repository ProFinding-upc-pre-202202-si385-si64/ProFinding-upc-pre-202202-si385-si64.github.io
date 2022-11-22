<script>
export default {
  name: 'ProfindingHome',
}
</script>

<template>

  <header class="cabecera">
    <img src="/src/assets/images/logo.png" alt="Logo Profinding" />
    <nav class="navMain">
      <i class="pi pi-bars menuNavegacionPrincipal"></i>
      <ul>
        <Button label="Inicio" class="p-button-text"/>
        <Button label="Sobre Nosotros" class="p-button-text"/>
        <Button label="Servicios" class="p-button-text"/>
        <Button label="Planes" class="p-button-text"/>
        <Button label="Nuestro Equipo" class="p-button-text"/>
        <Button label="Contactanos" class="p-button-text"/>



      </ul>
    </nav>
  </header>


  <div class="lienzo">

    <div class="principal">
      <img class="mainBackground" src="/src/assets/images/home.png" alt="Home principal Profinding" />
      <div>
        <h1>La mejor opción para<br/>hacer tus compras<br/>rápidas y seguras</h1>
        <h2>Descargalo de una vez:</h2>
        <img alt="playstoref" src="/src/assets/images/playstore.png" />
        <img alt="appstoref" src="/src/assets/images/appstore.png" />
      </div>
    </div>
  </div>


  <div class="sobre-nosotros">
    <h1>Acerca de nosotros</h1>
    <div>
      <img src="/src/assets/images/Logo.png" alt="Logo Profinding" />
      <p>
        Pro-Finding, es una app que usa la búsqueda inteligente por fotos y <br>
        filtros. De esta manera, los usuarios pueden encontrar el nombre del <br>
        posible producto y los puntos más cercanos de la venta. Con el fin de <br>
        crear un futuro nuevo y revolucionario. Por lo anterior, consideramos que <br>
        la cooperación del humano con la tecnología es el camino correcto para <br>
        crear un porvenir mejor y más brillante.
      </p>
    </div>
  </div>


  <div class="servicios">
    <h1>Servicios</h1>
    <div class="container-SV">
      <div class="contenedorServicios">
        <img src="/src/assets/images/service1.png" alt="service1" />
        <div>
          <h1>Búsqueda Inteligente y Visual</h1>
          <p>Solo sera necesario tener una imagen para encontrar el producto que quieras por medio de nuestro buscador visual.</p>
          <Button label="Leer mas" class="p-button-raised"/>
        </div>
      </div>
      <div class="contenedorServicios">
        <img src="/src/assets/images/service2.png" alt="service2" />
        <div>
          <h1>Mapa de tiendas</h1>
          <p>En la información detallada de los productos se podra ver tambien los locales de venta del porducto que este buscando y que esten cerca del usuario</p>
          <Button label="Leer mas" class="p-button-raised"/>
        </div>
      </div>
      <div class="contenedorServicios">
        <img src="/src/assets/images/service3.png" alt="service3" />
        <div>
          <h1>Comparacion de Productos similiares</h1>
          <p>Gracias a la información que brindamos a la hora de buscar un producto se podra realizar comparaciones del mismo producto pero de diferentes puntos de venta</p>
          <Button label="Leer mas" class="p-button-raised"/>
        </div>
      </div>
    </div>
  </div>


  <div class="planes">
    <h1>Planes</h1>
    <div class="conenedorPL">
      <div class="contenedorPlanes">
        <div class="orange-box1"/>
        <div class="cajaDeContenidos">
          <h1>Free</h1>
          <h2>Podras realizar  busquedas indefinidas con anuncios.</h2>
          <h3> S/.0  mo* </h3>
          <Button label="Subscribirse" class="p-button-raised"/>
        </div>
      </div>
      <div class="contenedorPlanes">
        <div class="caja-naranja2"/>
        <div class="cajaDeContenidos">
          <h1>Premium</h1>
          <h2>Podras realizar  busquedas indefinidas sin anuncios.</h2>
          <h2>Tendras notificaciones de promociones de productos segun tus busquedas.</h2>
          <h2>Contaras con promociones personalizadas.</h2>
          <h3> S/.16.99 mo* </h3>
          <Button label="Subscribirse" class="p-button-raised"/>
        </div>
      </div>
    </div>
  </div>


  <div class="nuestroEquipo">
    <h1>Nuestro Equipo</h1>
    <div class="container-OT">
      <div class="contenedorNuestroEquipo">
        <img src="/src/assets/images/Rubio.png">
        <div class="cajaDeContenidos-OT">
          <h1>Adrian Rubio</h1>
          <h2>Ingeniero de Software</h2>
        </div>
      </div>
      <div class="contenedorNuestroEquipo">
        <img src="/src/assets/images/Piero.png">
        <div class="cajaDeContenidos-OT">
          <h1>Piero Salinas</h1>
          <h2>Ingeniero de Sistemas de Información</h2>
        </div>
      </div>
      <div class="contenedorNuestroEquipo">
        <img src="/src/assets/images/Luis.png">
        <div class="cajaDeContenidos-OT">
          <h1>Luis Bendezú</h1>
          <h2>Ingeniero de Sistemas de Información</h2>
        </div>
      </div>
      <div class="contenedorNuestroEquipo">
        <img src="/src/assets/images/Giancarlo.png">
        <div class="cajaDeContenidos-OT">
          <h1>Giancarlo Moreno</h1>
          <h2>Ingeniero de Sistemas de Información</h2>
        </div>
      </div>

    </div>
  </div>



  <div class="contactos">
    <h1>Contactanos</h1>
    <div class="container-C">
      <div class="contenedorContactos">
        <div class="contenedorCajaContactos">
          <div class="cajaDeContenidos-C">
              <span class="p-float-label">
	              <InputText class="inputC" id="usuario" type="text" v-model="value" />
                <label for="usuario">Tu nombre</label>
              </span>
            <span class="p-float-label">
	              <InputText class="inputC" id="usuario" type="text" v-model="value" />
                <label for="usuario">Email</label>
              </span>
            <span class="p-float-label">
	              <InputText class="inputC-email" id="usuario" type="text" v-model="value" />
                <label for="usuario">Mensaje</label>
              </span>
            <Button label="Enviar" class="p-button-raised"/>
          </div>
          <div class="cajaDeContenidos-C2">
            <h1>Siguenos</h1>
            <h2>Por</h2>
            <div >

            </div>
            <div class="contenedorDeBotones">
              <Button type="button" class="p-button-outlined p-button-success">
                <img alt="logo" src="/src/assets/images/facebook.png" />
              </Button>
              <Button type="button" class="p-button-outlined p-button-success">
                <img alt="logo" src="/src/assets/images/linkelind.png" />
              </Button>
              <Button type="button" class="p-button-outlined p-button-success">
                <img alt="logo" src="/src/assets/images/twitter.png" />
              </Button>
              <Button type="button" class="p-button-outlined p-button-success">
                <img alt="logo" src="/src/assets/images/google.png" />
              </Button>
              <Button type="button" class="p-button-outlined p-button-success">
                <img alt="logo" src="/src/assets/images/instagram.png" />
              </Button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="figma">
    <a class="buttonmas" href="https://www.figma.com/file/mtN1WEcqOHYoau75ZxGwfQ/Mock-Up_Final?node-id=0%3A1&t=XX6TzUtnBUWKYkQz-0">Mockup</a>
    <a class="buttonmas" href="https://www.figma.com/file/R42kGlSwZjBuCW6PEOQdZo/User-Flow?node-id=0%3A1&t=ohMD65ad0XtE4giC-0">User-Flow</a>
  </div>


  <footer class="pieDePagina">


    <nav class="navMain-footer">
      <ul>
        <div class="c1">

          <Button label="Nosotros" class="p-button-text"/>
          <Button label="Privacidad" class="p-button-text"/>
          <Button label="Terminos y condiciones" class="p-button-text"/>
          <Button label="Contacto y Ayuda" class="p-button-text"/>
          <Button label="Libro de reclamaciones" class="p-button-text"/>

        </div>

          <div class="c2">
            <Button label="Inicio" class="p-button-text"/>
            <Button label="Sobre nosotros" class="p-button-text"/>
            <Button label="Servicios" class="p-button-text"/>
            <Button label="Nuestro equipo" class="p-button-text"/>
            <Button label="Planes" class="p-button-text"/>
            <Button label="Contactanos" class="p-button-text"/>
          </div>
          <div class="c3">
            <h2>Descargalo aqui:</h2>
            <img alt="playstoref" src="/src/assets/images/playstore.png" />
            <img alt="appstoref" src="/src/assets/images/appstore.png" />
            <h2>Redes sociales:</h2>
            <Button type="button" class="p-button-outlined p-button-success">
              <img alt="logo" src="/src/assets/images/facebook.png" />
            </Button>
            <Button type="button" class="p-button-outlined p-button-success">
              <img alt="logo" src="/src/assets/images/linkelind.png" />
            </Button>
            <Button type="button" class="p-button-outlined p-button-success">
              <img alt="logo" src="/src/assets/images/twitter.png" />
            </Button>
            <Button type="button" class="p-button-outlined p-button-success">
              <img alt="logo" src="/src/assets/images/google.png" />
            </Button>
            <Button type="button" class="p-button-outlined p-button-success">
              <img alt="logo" src="/src/assets/images/instagram.png" />
            </Button>

          </div>


      </ul>
    </nav>
    <p>©Profinding  2022 |  Reservados todos los derechos.</p>
  </footer>




</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@300;400&display=swap');

h1, h2, h3, p, Button{
  font-family: 'Roboto', sans-serif;
}

.cabecera{
  width: 100%;
  display: flex;
  align-items: center;
  background: #000000;
  height: 130px;

}
.cabecera img{
  margin-left: 3%;
}
.navMain{
  margin-left: auto;
}
.navMain ul Button{
  margin-left: 20px;
  margin-right: 50px;
  font-size: 22px;
}



.principal{
  display: flex;
  position: relative;
}
.mainBackground{
  width: 100%;
  height: 800px;
}
.principal div {
  display: flex;
  position: absolute;
  margin-left: 5%;
  margin-top: 5%;
  size: auto;
  flex-direction: column;
  justify-content: center;
}
.principal div h1{
  font-size: 92px;
  text-shadow: 3px 3px black;
}
.principal div img{
  width: 25%;
  height: 25%;
  margin-left: 30%;
  margin-top: 2%;
}
.principal div Button{
  width: 35%;
  margin: auto;
  font-size: 24px;
  padding-top: 1%;
  padding-bottom: 1%;
  color: white;
}






.sobre-nosotros{
  background: #8fe2fe;
  text-align: center;
  padding: 3%;
}
.sobre-nosotros h1 {
  margin:0;
  font-size: 70px;
  color: #D6A049;
}
.sobre-nosotros div{
  display:flex;
  flex-direction: row;
  flex-wrap: wrap;
}
.sobre-nosotros div Image{
  flex:30%;
}
.sobre-nosotros div p{
  flex:70%;
  background: white;
  color:black;
  margin: auto 5% auto 5%;
  font-size:28px;
  text-align: left;
  padding: 3%;
}






.servicios{
  background: #8fe2fe;
  text-align: center;
  padding: 3%;
}
.servicios h1 {
  margin:0 0 2% 0;
  font-size: 70px;
  color: #D6A049;
}
.container-SV{
  display: flex;
  flex-direction: row;
  justify-content: center;
  gap: 50px;
  flex-wrap: wrap;
}
.contenedorServicios{
  background: white;
  width: 400px;
  border-radius: 30px;
  display: flex;
  flex-direction: column;
}
.contenedorServicios img{
  border-radius: 25px 25px 0px 0px;
  margin:0;
}
.contenedorServicios div{
  margin: 1% 10% 15% 10%;
  color: black;
}
.contenedorServicios div h1{
  font-size: 24px;
  margin: 5% 0 5% 0;
  color: black;
}
.contenedorServicios div p{
  font-size: 16px;
  text-align: justify;
  margin-bottom: 10%;
  color: black;
}
.contenedorServicios div Button{
  width:100%;
  padding-top: 5%;
  padding-bottom: 5%;
  font-size: 18px;
  color: white;
}
.figma {

  display:grid;
  background: #8fe2fe;
  justify-content:center;

}
.buttonmas{
  font-family: 'Roboto', sans-serif;
  font-size: 20px;
  color: #000000;
 background: #D6A049;
  text-decoration: none;
}




.planes{
  background: #8fe2fe;
  text-align: center;
  padding: 3%;
}
.planes h1 {
  margin:0 0 2% 0;
  font-size: 70px;
  color: #D6A049;
}
.conenedorPL{
  display: flex;
  flex-direction: row;
  justify-content: center;
  gap: 50px;
  flex-wrap: wrap;
}
.contenedorPlanes{
  background: white;
  width: 400px;
  border-radius: 30px;
  display: flex;
  flex-direction: column;
}
.orange-box1{
  border-radius: 25px 25px 0px 0px;
  background: #FFC286;
  width: 100%;
  height: 50px;
  margin:0;
}
.caja-naranja2{
  border-radius: 25px 25px 0px 0px;
  background: #EA9D51;
  width: 100%;
  height: 50px;
  margin:0;
}

.cajaDeContenidos{
  margin: 1% 10% 15% 10%;
  color: black;
}
.cajaDeContenidos h1{
  font-size: 24px;
  text-align: left;
  margin: 5% 0 5% 0;
  color: black;
}
.cajaDeContenidos h2{
  font-size: 16px;
  text-align: left;
  margin-bottom: 10%;
  color: black;
}
.cajaDeContenidos h3{
  font-size: 22px;
  text-align: left;
  margin-bottom: 10%;
  color: black;
}
.cajaDeContenidos Button{
  width:50%;
  padding-top: 5%;
  padding-bottom: 5%;
  margin-right: 80%;
  font-size: 18px;
  color: white;
}





.cajaDeContenidos-PC h1{
  font-size: 24px;
  font-weight: bold;
  text-align: left;
  margin: 5% 0 5% 0;
  color: black;
}
.cajaDeContenidos-PC h2{
  font-size: 20px;
  font-weight: lighter;
  text-align: left;
  margin: 5% 0 5% 0;
  color: black;
}
.cajaDeContenidos-PC h3{
  font-size: 48px;
  text-align: center;
  margin: 5% 0 5% 0;
  color: black;
}

.cajaDeContenidos-PC2 h1{
  font-size: 36px;
  font-weight: bold;
  text-align: center;
  margin: 5% 0 5% 0;
  color: black;
}
.cajaDeContenidos-PC2 h2{
  font-size: 20px;
  font-weight: lighter;
  text-align: center;
  margin: 5% 0 5% 0;
  color: black;
}
.cajaDeContenidos-PC2 h3{
  font-size: 48px;
  text-align: center;
  margin: 5% 0 5% 0;
  color: black;
}
.cajaDeContenidos-PC2 Button{
  width:50%;
  padding-top: 5%;
  padding-bottom: 5%;
  font-size: 18px;
  color: white;
}






.nuestroEquipo{
  background: #8fe2fe;
  text-align: center;
  padding: 3%;
}
.nuestroEquipo h1 {
  margin:0 0 2% 0;
  font-size: 70px;
  color: #D6A049;
}
.container-OT{
  display: grid;
  justify-content: center;
  gap: 100px;
  padding: 0px 200px 0px 200px;
  grid-template-columns: repeat(2,minmax(0,1fr));
}
.contenedorNuestroEquipo{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.contenedorNuestroEquipo img{
  border-radius: 50%;
  width: 50%;
}
.cajaDeContenidos-OT h1{
  justify-content: center;
  color: white;
  font-size: 24px;
}
.cajaDeContenidos-OT h2{
  justify-content: center;
  color: white;
  font-size: 16px;
}






.contactos{
  background: #8fe2fe;
  padding: 3%;
}
.contactos h1{
  color: #D6A049;
  text-align: center;
  font-size: 70px;
}
.container-C{
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
.contenedorContactos{
  width: 100%;
  height: 500px;
  border-radius: 30px;
  display: inline-block;
  flex-direction: column;
  flex-wrap: wrap;
}
.contenedorCajaContactos{
  background: white;
  width: 100%;
  height: 500px;
  border-radius: 5px;
  border: 6px solid #D6A049;
  display: flex;
  flex-direction: row;
}
.cajaDeContenidos-C{
  margin: 1% 10% 15% 10%;
  color: black;
  flex: 50%;
  display: flex;
  flex-direction: column;
}
.p-float-label{
  margin-top: 7%;
}
.inputC{
  width: 100%;
}
.inputC-email{
  width: 100%;
  height: 150px;
}
.cajaDeContenidos-C button{
  margin: 5% 0% 0% 25%;
  width: 50%;
  padding: 4% 0 4% 0;
}
.cajaDeContenidos-C2{
  margin: 1% 10% 15% 10%;
  color: black;
  flex: 50%;
  display: flex;
  flex-direction: column;
}
.cajaDeContenidos-C2 h1{
  text-align: center;
  color: #D6A049;
}
.cajaDeContenidos-C2 h2{
  text-align: center;
  color: #D6A049;
}
.contenedorDeBotones{
  display: grid;
  gap: 20px;
  margin-top: 5%;
  padding: 0px 30px 40px 10px;
  grid-template-columns: repeat(5,minmax(0,1fr));
}
.contenedorDeBotones Button{
  display: flex;
  justify-content: center;

}



.pieDePagina c1 {
  background: #D6A049;
  display:grid;
  padding: 0px 30px 40px 10px;
  grid-template-columns: repeat(3,minmax(0,1fr));

}
.c1{
  display: flex;
 align-items:center;
}
.c2 {
  display: flex;
  align-items: center;

}

.c3 img {
  width: 30%;
  align-items:center;
}


.pieDePagina p{

  text-align: center;
  color: #D6A049;
}
.navMain-footer{
  display: flex;
  justify-content: center;
}

.menuNavegacionPrincipal{
  display:none !important;
}

@media  screen and (max-width: 600px) {



  .menuNavegacionPrincipal{
    display:block !important;
  }
  .cabecera{
    flex-direction:column;
    height: auto;
    justify-content: center;
    align-items: center;
  }

  .navMain{
    margin:0;
    text-align:center;

  }

  .navMain ul{
    display:flex;
    flex-direction: column;
    gap:10px;
  }

  .principal div h1{
    font-size: 60px;
  }

  .contenedorServicios{
    width: 100%;
  }



  .container-OT{
    padding: 10px;
  }

  .contenedorContactos{
    height:auto;
  }

  .contenedorCajaContactos{
    flex-direction: column;
    height: auto;
  }

  .contenedorDeBotones{
    margin-top:0;
    padding: 0;
    grid-template-columns: auto;

  }

  .cajaDeContenidos Button{
    width:auto;
    padding-top: 0;
    padding-bottom: 0;
    margin-right: auto;
  }

}

</style>
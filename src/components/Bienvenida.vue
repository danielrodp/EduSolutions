<style>

.maincontainer {
  /*border-radius: 25px;*/
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: space-between;
  padding: 20px;
  box-shadow: 0px 0px 6px rgba(0, 0, 0, 0.15);
  width: 100%;
  background-color: #31495E;
  height:80vh;

}

.logoHeader {
  float: left;
  width: 12%;
  height: 12%;
}

.footer {
  padding: 20px;
  width: 100%;
  background-color: #31495E;
  padding-bottom: 3%;
}

.titulo {
  color: white;
  margin: auto;
  width: 55%;
  font-weight: bold;
}

.button {
  margin: auto;
  margin-top: 2%;
  margin-bottom: 2%;
  padding: 10px;
  background-color: #a876fe;
}

.splash {
  margin: auto;
  width: 85%;
  height: 85%;
}
</style>

<template>

<b-container fluid>
    <div>
        <div>
            <b-navbar toggleable="lg" type="dark" variant="info">
                <b-navbar-brand href>  <img class="logoHeader" src="..\assets\LogoApp.png" alt="logo"> </b-navbar-brand>
                <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
                <b-collapse id="nav-collapse" is-nav>
                    <!-- Right aligned nav items -->
                    <b-navbar-nav class="ml-auto">
                        <b-navbar-nav>
                            <b-nav-item href="#">Bienvenida</b-nav-item>
                            <b-nav-item href="#">Sobre Nosotros</b-nav-item>
                        </b-navbar-nav>
                    </b-navbar-nav>
                </b-collapse>
            </b-navbar>
        </div>
        <div class="maincontainer">
            <b-container fluid>
                <b-row>
                    <h1 class="titulo">Todo el conocimiento al alcance de tus manos.<br>
                        Inicie a usar cualquier herramienta colaborativa hoy.</h1>
                </b-row>
                <b-row>
                    <b-button class="button" size="lg" >Inicio</b-button>
                </b-row>
                <b-row>
                  <img class="splash" src="..\assets\splash.png" alt="logo">
                </b-row>
            </b-container>
        </div>
    </div>
    <footer class="footer">
    </footer>
</b-container>
</template>

<script>

export default {
    name: 'Bienvenida',
    data() {
        return {

        }
    }
}

</script>

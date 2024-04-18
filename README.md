# Viajes-chile

#1- Primero linkie todo para utilizar Boostrap y Boostrap JS

#2- Igual que el script de jquery para el JS

#3- cree un header dentro de eso uni nav y el carrusel.
  utilice un nav extraido de boostrap al igual ocupo una funcion de este para deja en nav fijo
    que se llama fixed-top para dejar el banner fijo  aparte lo deje transparente y junto el carrusel

#4- siguiendo con el armado de la pagina para el carrusel copie uno de BS y le di un tooltip con BS JS
    eso genera que se mueva solo los Slide

#5- en el main  indique un un container  para que me centrar todo, aca utilice col para genear los 3 parrafos
    para que esten uno de lado del otro y una etiqueta <i>  para los iconos que igual son un <script>


#6- lo mismo que lo anterior utilice unas card de BS y las genere con columnas para centrar

#7- el form igual fue copiado peero modificado de BS el buttom utilice tooltips para que mostrara mensaje ENVIAR

#8- los favicons son un <script> 

que al igual utilice BS JS  para el tooltips 

#9-
    Color : Black y BG-info 
    fonts :font-family: "Raleway";


    <nav
        class="navbar navbar-expand-md navbar-dark fixed-top"
        style="background-color: transparent"
      >
        <div class="container">
          <a
            class="navbar-brand fw-bold"
            href="./index.html"
            title="Logo Viajes Chile"
            ><img
              src="./assets/img/viajes.svg"
              alt="Logo Viajes Chile"
              style="width: 70px"
            />
            Viajes Chile</a
          >
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarText"
            aria-controls="navbarText"
            aria-expanded="false"
            aria-label="Toggle navigation"
          ></button>
          <div class="collapse navbar-collapse" id="navbarText">
            <ul class="navbar-nav ms-auto mb-2 mb-lg-0 me-5">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#"
                  >Inicio</a
                >
              </li>
              <li class="nav-item">
                <a class="nav-link " aria-current="page" href="#quienes"
                  >Quienes Somos</a
                >
              </li>
              <li class="nav-item">
                <a
                  class="nav-link "
                  aria-current="page"
                  href="#destacados"
                  >Destacados</a
                >
              </li>
              <li class="nav-item">
                <a class="nav-link " aria-current="page" href="#contacto"
                  >Contacto</a
                >
              </li>
            </ul>
          </div>
        </div>
      </nav>
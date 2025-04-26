# website-its<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ITS Extension aulica Villa el libertador</title>

    <!-- Latest compiled and minified CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <link rel="stylesheet" href="styles.css">

    <!-- jQuery library -->
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>

    <!-- Popper JS -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>

    <!-- Latest compiled JavaScript -->
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</head>
<body>

    <div class="container fluid">
        <div class="row">
        
            <nav class="navbar navbar-expand-sm bg-blue navbar-white fixed-top">
                <a class="navbar-brand" href="#">
                    <img src="img/logo-azul.jpg" alt="logo-azul" style="width: 50px;">
                </a>    
                <!-- Toggler/collapsibe Button -->
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#collapsibleNavbar">
                    <span class="navbar-toggler-icon"></span>
                </button>

                <!-- Navbar links -->
                <div class="collapse navbar-collapse" id="collapsibleNavbar">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link" href="#">Inicio</a>
                        </li>
                        <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
                             Tecnicatura en desarrollo de Software
                            </a>
                            <div class="dropdown-menu">
                              <a class="dropdown-item" href="#">Plan de estudio</a>
                              <a class="dropdown-item" href="#">Asignaturas</a>
                              <a class="dropdown-item" href="#">Horario de clases</a>
                              <a class="dropdown-item" href="#">Inscripcion a cursadas</a>
                              <a class="dropdown-item" href="#">Fechas de examenes</a>
                              <a class="dropdown-item" href="#">Inscripcion a examenes</a>
                            </div>
                          </li>

                          <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
                             Tecnicatura en Enfermeria
                            </a>
                            <div class="dropdown-menu">
                              <a class="dropdown-item" href="#">Plan de estudio</a>
                              <a class="dropdown-item" href="#">Asignaturas</a>
                              <a class="dropdown-item" href="#">Horario de clases</a>
                              <a class="dropdown-item" href="#">Inscripcion a cursadas</a>
                              <a class="dropdown-item" href="#">Fechas de examenes</a>
                              <a class="dropdown-item" href="#">Inscripcion a examenes</a>
                              <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
                             Estudiantes 
                            </a>
                            <div class="dropdown-menu">
                             <a class="dropdown-item" href="#">Regimen de alumnos</a>
                             <a class="dropdown-item" href="#">Centro de estudiantes</a>
                             <a class="dropdown-item" href="#">Becas</a>
                             <li class="nav-item dropdown">
                            <a class="nav-link dropdown-toggle" href="#" id="navbardrop" data-toggle="dropdown">
                             Ingreso a las carreras
                             </a>
                            <div class="dropdown-menu">
                            <a class="dropdown-item" href="#"> Inscribirse en desarrollo de software</a>
                             <a class="dropdown-item" href="#">Inscribirse en enfermeria </a>
                          </li>
                        
                        </li>
                    </ul>
                </div>
            </nav>
        </div>
        
        <div id="demo" class="carousel slide" data-ride="carousel">

                <!-- Indicators -->
                <ul class="carousel-indicators">
                <li data-target="#demo" data-slide-to="0" class="active"></li>
                <li data-target="#demo" data-slide-to="1"></li>
                <li data-target="#demo" data-slide-to="2"></li>
                <li data-target="#demo" data-slide-to="3"></li>
                </ul>
            
                <!-- The slideshow -->
                <div class="carousel-inner">
                    <div class="carousel-item active">
                        <img src="img/c1.jpg" alt="Los Angeles" width="800" height="400">
                    </div>
                    <div class="carousel-item">
                        <img src="img/c2.jpg" alt="Chicago" width="800" height="400">
                    </div>
                    <div class="carousel-item">
                        <img src="img/c3.jpg" alt="New York" width="800" height="400">
                    </div>
                    <div class="carousel-item">
                        <img src="img/c4.jpg" alt="New York" width="800" height="400">
                    </div>
                </div>
            
                <!-- Left and right controls -->
                <a class="carousel-control-prev" href="#demo" data-slide="prev">
                <span class="carousel-control-prev-icon"></span>
                </a>
                <a class="carousel-control-next" href="#demo" data-slide="next">
                <span class="carousel-control-next-icon"></span>
                </a>
            
            </div>  
        </div>
        </div>  
        </div>

        <div class="row bg-dark text-pink justify-content-center mt-3">
            <span class="display-3">Tecnicaturas</span>
        </div>
        <div class="row mt-3 justify-content-center">
            <div class="col-sm-6">
                <div class="card" style="width:400px">
                    <img class="card-img-top" src="img/software.jpg" alt="Card image">
                    <div class="card-body">
                      <h4 class="card-title">Tecnicatura en desarrollo de software</h4>
                      <p class="card-text">La carrera del Futuro </p>
                      <!-- Button to Open the Modal -->
                      <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#infosoft">
                        Mas info
                      </button>
                    </div>
                </div>

            </div>
            <div class="col-sm-6">
                <div class="card" style="width:400px">
                    <img class="card-img-top" src="img/enfermeria.jpg" alt="Card image">
                    <div class="card-body">
                      <h4 class="card-title">Tecnicatura en Enfermeria </h4>
                      <p class="card-text"> Preparate para ser Trabajador escencial</p>
                      <!-- Button to Open the Modal -->
                      <button type="button" class="btn btn-primary" data-toggle="modal" data-target="#infoenfer">
                        Mas info
                      </button>
                    </div>
                </div>
            </div> 
 </div> 
        <div class="row bg-dark text-pink justify-content-center mt-3">
            <span class="display-3">Informacion</span>
        </div>
        <div class="row mt-3">
            <div class="col-sm-5">
                <div class="list-group">
                    <a  class="list-group-item list-group-item-action active" data-toggle="list" data-target="#Datos">Ubicacion:como llegar</a>
                    <a  class="list-group-item list-group-item-action " data-toggle="list" data-target="#Contacto">Formulario de Contacto</a>
                    
                </div>
            </div>
            <div class="col-sm-6">
                <div class="tab-content">
                    <div class="tab-pane container active" id="Datos">
                        <ul class="list-group">
                            <li class="list-group-item">Escuela <strong> "Marta Juana González".(En  frente diagonal del Hospital Principe de Asturias).</strong></li>
                            <li class="list-group-item">Direccion: Defensa esq.Bermejo 1100. B° Villa el Libertador  </li>
                            <li class="list-group-item">Linea de colectivo: 33</li>
                        </ul>


                    </div>
                                
                    <div class="tab-pane container fade" id="Contacto">
                        <form action="/action_page.php">
                            <div class="form-group">
                              <label for="Nombre">Apellido y Nombre</label>
                              <input type="text" class="form-control" placeholder="Nombre" id="Nombre">
                            </div>
                            <div class="form-group">
                              <label for="Email">E-Mail</label>
                              <input type="email" class="form-control" placeholder="Correo electronico" id="Email">
                            </div>
                            <div class="form-group form-check">
                              <label for="Comentarios">Consulta:</label>
                              <textarea class="form-control" placeholder="Comentarios"></textarea> 
                              
                            </div>
                            <button type="submit" class="btn btn-primary">Enviar</button>
                        </form>

                    </div>
                    
                </div>




            </div>


        <!-- The Modal -->
        <div class="modal" id="infosoft">
            <div class="modal-dialog">
            <div class="modal-content">
        
                <!-- Modal Header -->
                <div class="modal-header">
                <h4 class="modal-title"> Tecnicatura en Desarrollo de software</h4>
                <button type="button" class="close" data-dismiss="modal">&times;</button>
                </div>
        
                <!-- Modal body -->
                <div class="modal-body">

El Técnico Superior en Desarrollo de Software estará capacitado para producir componentes de software, lo que comprende su diseño detallado, construcción y realización de verificación unitaria de los mismos, así como su depuración, optimización y mantenimiento; desarrollando las actividades descriptas en el perfil profesional y cumpliendo con los criterios de realización establecidos para las mismas en el marco de un equipo de trabajo organizado por proyecto.

                </div>
        
                <!-- Modal footer -->
                <div class="modal-footer">
                <button type="button" class="btn btn-danger" data-dismiss="modal">Cerrar</button>
                </div>
        
            </div>
            </div>
        </div>
        <div class="modal" id="infoenfer">
            <div class="modal-dialog">
            <div class="modal-content">
        
                <!-- Modal Header -->
                <div class="modal-header">
                <h4 class="modal-title">Tecnicatura en enfermeria</h4>
                <button type="button" class="close" data-dismiss="modal">&times;</button>
                </div>
        
                <!-- Modal body -->
                <div class="modal-body">
                   Perfil Profesional

Los conocimientos y habilidades desarrolladas durante su formación le permiten a la/el Enfermera/o el ejercicio profesional en relación de dependencia y en forma libre, desarrollando, brindando y gestionando los cuidados de enfermería autónomos e interdependientes para la promoción, prevención, recuperación y rehabilitación de la persona, la familia, grupo y comunidad hasta el nivel de complejidad de cuidados intermedios, en los ámbitos comunitario y hospitalario en las distintas etapas del ciclo vital; gestionando su ámbito de trabajo y participando en estudios de investigación-acción.


 </div>
  

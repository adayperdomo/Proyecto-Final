# index.html

```sh
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rotten Onion</title>
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="https://cdn-icons-png.flaticon.com/512/517/517559.png" type="image/x-icon">
</head>
<body>
    <header>
        <nav>
            <a href="index.html"><img src="logo.png" alt=""></a>
            <ul class="pri">
                <div class="buscar">
                    <input type="text" placeholder="Buscar">
                </div>
                <li class="ante"><a href="#">PELÍCULAS</a>
                    <ul class="sub">
                        <h2>Géneros:</h2>
                        <li><a href="#">Acción</a></li>
                        <li><a href="#">Terror</a></li>
                        <li><a href="#">Drama</a></li>
                        <li><a href="#">Animación</a></li>
                    </ul>
                </li>
                <li class="ante"><a href="#">SERIES</a>   
                    <ul class="sub">
                        <li><a href="#">Acción</a></li>
                        <li><a href="#">Terror</a></li>
                        <li><a href="#">Drama</a></li>
                        <li><a href="#">Animación</a></li>
                    </ul>
                </li>
                <li class="ante"><a href="#">RANKING DE PELÍCULAS</a>    
                    <ul class="sub">
                        <li><a href="#">Las tres mejores</a></li>
                        <li><a href="#">Las cinco mejores</a></li>
                        <li><a href="#">Las diez mejores</a></li>
                    </ul>
                </li>
                <li class="ante"><a href="#">ACTORES / ACTRICES</a>    
                    <ul class="sub">
                        <li><a href="#">Actores más conicidos</a></li>
                        <li><a href="#">Actrices más conocidas</a></li>
                    </ul>
                </li>
                <li class="ante"><a href="#">CINE CLÁSICO</a>    
                    <ul class="sub">
                        <li><a href="#">Años 70</a></li>
                        <li><a href="#">Años 80</a></li>
                        <li><a href="#">Años 90</a></li>
                    </ul>
                </li>
            </ul>
        </nav>
    </header> 

    <div class="espacio"></div>

    <h2 class="titulo">PELÍCULAS 2024</h2>
    <section class="tarjetas">
        <article class="tarjeta">
            <a href="#">
                <img src="https://hips.hearstapps.com/hmg-prod/images/el-especialista-poster-662ba91800a75.jpg?crop=1xw:1xh;center,top&resize=980:*" alt="Especialista"><br><br>
                <h2>EL ESPECIALISTA</h2><br>
            </a>    
        </article>

        <article class="tarjeta">
            <a href="#">
                <img src="https://cineslanzarote.com/wp-content/uploads/2024/10/terrifier_3-141451507-large-360x618_c.jpg" alt="art"><br><br>
                <h2>TERRIFIER 3</h2><br>
                <img class="rate" src="mal-onion.png" alt="">
            </a>     
        </article>

        <article class="tarjeta">
            <a href="#">
                <img src="https://artesiete.es/Posters/deadpoolylobezno.jpg" alt="dead"><br><br>
                <h2>DEADPOOL Y LOBEZNO</h2><br>
            </a>    
        </article>

        <article class="tarjeta">
            <a href="">
                <img src="https://pics.filmaffinity.com/Dune_Parte_Dos-835984588-large.jpg" alt="dune"><br><br>
                <h2>DUNE PARTE 2</h2><br>
            </a>     
        </article>
    </section>
    <h2 class="titulo">SERIES 2024</h2>
    <section class="tarjetas">
        <article class="tarjeta">
            <a href="#">
                <img src="https://resizing.flixster.com/jAlNgPqSQHpxH6ju0Eis-j8cdWE=/206x305/v2/https://resizing.flixster.com/dIDB54V_MjguvAiEPfYlB3_cYfg=/ems.cHJkLWVtcy1hc3NldHMvdHZzZWFzb24vYjExOWI4M2UtZjhiMS00MWUxLWJhN2QtNjMzNjk1ZjFlYjc0LmpwZw==" alt="arcane"><br><br>
                <h2>TEMPORADA 2 – ARCANE</h2><br>
            </a>    
        </article>

        <article class="tarjeta">
            <a href="#">
                <img src="https://pics.filmaffinity.com/shogun-329020163-mmed.jpg" alt="Shogun"><br><br>
                <h2>SHOGUN</h2><br>
                <img class="rate" src="mal-onion.png" alt="">
            </a>     
        </article>

        <article class="tarjeta">
            <a href="#">
                <img src="https://pics.filmaffinity.com/the_penguin-328044903-mmed.jpg" alt="PENGUIN"><br><br>
                <h2>EL PINGüINO</h2><br>
            </a>    
        </article>

        <article class="tarjeta">
            <a href="">
                <img src="https://pics.filmaffinity.com/solo_leveling-428113960-mmed.jpg" alt="solo"><br><br>
                <h2>SOLO LEVELING</h2><br>
            </a>     
        </article>
    </section>

    <h2 class="titulo">PROXIMAMENTE EN CINES</h2>
    <section class="tarjetas">
        <article class="tarjeta">
            <a href="#">
                <img src="" alt=""><br><br>
                <h2></h2><br>
            </a>    
        </article>

        <article class="tarjeta">
            <a href="#">
                <img src="" alt=""><br><br>
                <h2></h2><br>
                <img class="rate" src="mal-onion.png" alt="">
            </a>     
        </article>

        <article class="tarjeta">
            <a href="#">
                <img src="" alt=""><br><br>
                <h2></h2><br>
            </a>    
        </article>

        <article class="tarjeta">
            <a href="">
                <img src="" alt=""><br><br>
                <h2></h2><br>
            </a>     
        </article>
    </section>


    <footer>
        <p id="foo2"></p>
    </footer>
</body>
</html>
```

# Stye.css
```sh
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family:Impact,'Arial Narrow Bold', sans-serif;
}

nav{
    background-color: #B45A82;
    display: flex;
    justify-content: center;
    align-items:end;
    height: 80px;
}

.pri{
    display: flex;
    list-style-type: none;
    height: 3em;
}

nav ul li a{
    display: flex;
    text-decoration: none;
    color: white;
    justify-content: space-between;
    margin-left: 30px;
    transition: 0.5s;
}

.buscar input{
    border-radius: 26px;
    width: 100%;
    padding-left: 20px;
    background: rgba(0, 0, 0, 0.4);
    color: white;
    border: 1px solid white;
    font-size: 20px;
}

nav ul li a:hover{
    display: block;
    color: black;
    background-color: white;
    padding: 5px;
    border-radius: 5px;
    padding-top: 20px;
    padding-bottom: 25px;

}

.sub{
    display: none;
}

.ante:hover > .sub{
    display: block;
    color: white;
    background-color: black;
    border: 1px solid black;
}

img{
    padding-top: 20px;
    height:100px;
    width: 150px;
}

.espacio{
    background-color: black;
    width: 100%;
    height: 20px;
}

.tarjeta{
    border: 1px solid black;
    border-radius: 20px;
    width: 180px;
    height: 376.34;
    background-color: white;
    margin: 10px;

}

.tarjeta a .rate{
    width: 16px;
    height: 16px;
    border: none;
}

.tarjeta a{
    text-decoration: none;
    color: black;
}

.tarjeta:hover{
    background-color: rgba(191, 187, 189, 0.2);
}

.tarjeta img{
    width: 161.66;
    border-radius: 5%;
    border: 1px solid black;
    height: 231.7px;
    padding-top: 0px;
    margin: 10px;
}

.tarjetas p{
    margin: 5px;
}

.por{
    margin-bottom: 20px;
}

.tarjetas{
    display: grid;
    grid-template:
        "cel1 cel2 cel3 cel4" 1fr
        "cel5 cel7 cel8 cel9" 1fr
        "cel10 cel11 cel12 cel13" 1fr/
         1fr   1fr   1fr   1fr;
    text-align: center;
    gap: 10px;
    margin-top: 10px;
    display: flex;
    justify-content: center;
    border: 1px solid black;
    background-color: #B45A82;
}

.titulo{
    padding-left: 20px;
    margin-top: 20px;
    padding-top: 20px;
    display: flex;
    justify-content: center;
}
```

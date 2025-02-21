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

    <h2 class="titulo">Péliculas actuales</h2>
    <section class="tarjetas">
        <article class="tarjeta">
            <a href="#">
                <img src="https://hips.hearstapps.com/hmg-prod/images/el-especialista-poster-662ba91800a75.jpg?crop=1xw:1xh;center,top&resize=980:*" alt="Especialista"><br><br>
                <h2>EL ESPECIALISTA</h2><br>
                <p>El doble de acción Colt Seavers sufre una lesión y abandona la profesión, pero regresa para participar en una película que dirigirá la mujer de la que está enamorado. Todo se complica cuando la estrella del filme, en deuda con narcos, desaparece.</p><br>
            </a>    
        </article>

        <article class="tarjeta">
            <a href="#">
                <img src="https://cineslanzarote.com/wp-content/uploads/2024/10/terrifier_3-141451507-large-360x618_c.jpg" alt="art"><br><br>
                <h2>TERRIFIER 3</h2><br>
                <img class="rate" src="mal-onion.png" alt="">
                <p>Tras sobrevivir a la masacre de Halloween perpetrada por Art, el peor asesino en serie desde Jack el Destripador, Sienna y su hermano tratan de reconstruir sus vidas. Se acercan las fiestas de Navidad e intentan celebrarlas olvidando el pasado.</p><br>
            </a>     
        </article>

        <article class="tarjeta">
            <a href="#">
                <img src="https://artesiete.es/Posters/deadpoolylobezno.jpg" alt="dead"><br><br>
                <h2>DEADPOOL Y LOBEZNO</h2><br>
                <p>Lobezno se recupera de sus heridas cuando se cruza con el bocazas, Deadpool, que ha viajado en el tiempo para curarlo con la esperanza de hacerse amigos y formar un equipo para acabar con un enemigo común.</p><br>
            </a>    
        </article>

        <article class="tarjeta">
            <a href="">
                <img src="https://pics.filmaffinity.com/Dune_Parte_Dos-835984588-large.jpg" alt="dune"><br><br>
                <h2>DUNE PARTE 2</h2><br>
                <p>Paul Atreides se une a Chani y a los Fremen mientras busca venganza contra los conspiradores que destruyeron a su familia. Enfrentándose a una elección entre el amor de su vida y el destino del universo, debe evitar un futuro terrible.</p><br>
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
}

.tarjetas p{
    margin: 5px;
}

.tarjetas{
    display: grid;
    grid-template:
        "cel1 cel2 cel3 cel4" 1fr
        "cel5 cel7 cel8 cel9" 1fr
        "cel10 cel11 cel12 cel13" 1fr/
         1fr   1fr   1fr   1fr;
    text-align: center;
    margin: 10px;
    gap: 10px;
}

.titulo{
    padding-left: 20px;
    margin: 10px;
}
```

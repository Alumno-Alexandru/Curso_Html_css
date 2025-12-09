# **_Curso de HTML_**

## [_Apartado de Html_](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/HTML_CSS)

> Representacion de codigo `HTML`

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

### Tareas echas del apartado del _html_

### [Practica 1](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/HTML_CSS/1.%20practica)

#### Ejemplo del Codigo de la practica 1 del `HTML`.


```html
    <!-- tabla  -->
     <h2>3º  Tablas</h2>

        <table>
        <caption></caption>
        <thead>
            <tr>
                <th></th>
                <th colspan="3"><img src="img/120_ipod.png"></th>
                <th colspan="2"><img src="img/100_ipod.png" width="100px"></th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <th>Capacidad</th>
                <td><p>2GB</p></td>
                <td><p>4GB</p></td>
                <td><p>8GB</p></td>
                <td><p>32GB</p></td>
                <td><p>2GB</p></td>
            </tr>
            <tr>
                <th>Colores</th>
                <th>Blanco</th>
                <td>
                    <ul>
                        <li>Negro</li>
                        <li>Rosa</li>
                        <li>Dorado</li>
                    </ul>
                </td>
                <th>Negro</th>
                <td colspan="2">
                    <ul>
                        <li>Negro</li>
                        <li>Blanco</li>
                    </ul>
                </td>
            </tr>
            <tr>
                <th>Pantalla</th>
                <th colspan="3">3 pulgadas</th>
                <th colspan="2">7 pulgadas</th>
            </tr>
            <tr>
                <th rowspan="2">Tiempo de Carga</th>
                <th colspan="3" rowspan="2">1 hora</th>
                <th colspan="2">5 horas</th>
            </tr>
            <tr>
                <th colspan="2">30 minutos para 75%</th>
            </tr>
        </tbody>
    </table>
```
#### Ejemplo del Codigo de la practica 1 del `CSS`.

```html
    <style>
        table{
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid black;
            padding: 20px;
        }
    </style>
```

### [Practica 2](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/HTML_CSS/2.%20practica/HTML)

> Elementos que sepueden utilizar en un formulario

#### Uso de input :
![Ejemplo_de_proyecto](/UTILIDADES/img/Reform.png)

#### Uso de Select :
![Ejemplo_de_proyecto](/UTILIDADES/img/Reform1.png)

#### Uso de textarea :
![Ejemplo_de_proyecto](/UTILIDADES/img/Reform2.png)

#### Uso de button :
![Ejemplo_de_proyecto](/UTILIDADES/img/Reform3.png)

#### Uso de imput Radio :
![Ejemplo_de_proyecto](/UTILIDADES/img/Reform4.png)

#### Uso de fieldset :
![Ejemplo_de_proyecto](/UTILIDADES/img/Reform5.png)

### [Practica 3](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/HTML_CSS/3.%20Practica)

> Representacion de la practica 3. 

![Ejemplo_de_proyecto](/UTILIDADES/img/Practica3.png)

### [Uso del DOM](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/HTML_CSS/Dom)

> Esta es una representacion del ejercicio del `Dom` con los metodos usados en èl, los puedes verificar en el enlace adjunto en su titulo.

![Ejemplo_de_proyecto](/UTILIDADES/img/dom.png)

### [Uso de flex](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/HTML_CSS/Tarea_flex)

#### Ejemplo de codigo usado de flex

> Este es parte del codigo `html`.

```html
<body>
    <header>
        DISEÑO DE INTERFACES WEB
        UT2 - Uso de estilpos
    </header><br>
    <main>
        <div class="titulo">TAREA 1</div>
        <div class="subtitulo">Crear el siguiente menú usando cajas de tipo flexbox:</div>

        <div class="flexbox-container">
            <div class="flexbox-titulo">Flexbox</div>
            <nav class="menu-flexbox">
                <div class="menu-item">Enlace 1</div>
                <div class="menu-item">Enlace 2</div>
                <div class="menu-item">Enlace 3</div>
                <div class="menu-item">Enlace 4</div>
            </nav>
        </div>
    </main>
</body>
```

> Este es parte del codigo `Css`.

```html
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    padding: 20px;
    background-color: #f5f5f5;
}

.titulo {
    color: #ff9800;
    font-size: 24px;
    font-weight: bold;
    margin-bottom: 10px;
}

.subtitulo {
    color: #333;
    font-size: 16px;
    margin-bottom: 20px;
}


.flexbox-container {
    background-color: #2c2c2c;
    padding: 15px;
    border-radius: 4px;
    margin-bottom: 20px;
}

.flexbox-titulo {
    color: white;
    font-size: 20px;
    margin-bottom: 15px;
}


.menu-flexbox {
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: #d3d3d3;
    flex-flow: row wrap;
    padding: 5px;
    border-radius: 3px;
    gap: 10px;
}
```

### [Proyecto Inicial](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/HTML_CSS/Proyecto_principal/html)

##### Esta es una imagen de como queda el proyecto.

![Ejemplo_de_proyecto](/UTILIDADES/img/Proyecto1.png)

### [Proyecto Web](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/HTML_CSS/Tarea_Pagina_web_info)

##### Esta es una imagen de como queda el proyecto.

![Ejemplo_de_proyecto](/UTILIDADES/img/Proyecto2.png)

### [Creacion del Formulario](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/HTML_CSS/Tarea_Formulario)

> Uno de los diseños que se puede hacer para un formulario.

![Ejemplo_de_proyecto](/UTILIDADES/img/Formulario.png)

## [_Apartado de Sass_](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/SASS)

> Representacion de `SASS`

![Ejemplo_de_proyecto](/UTILIDADES/img/Sass.png)

### - [Ha prendizaje con ejemplos de Sass](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/SASS/Inicio)

#### [Ejemplo 1](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/SASS/Inicio/ejemplo1)

#### Variables :
![Ejemplo_de_proyecto](/UTILIDADES/img/VarSass.png)

#### Class o Id :
![Ejemplo_de_proyecto](/UTILIDADES/img/ClassSass.png)

#### [Ejemplo 2](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/SASS/Inicio/ejemplo2)

> Representacion de Ejemplo con un diseño creado en `Sass`

![Ejemplo_de_proyecto](/UTILIDADES/img/Ejemplo2.png)

#### [Ejemplo 3](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/SASS/Inicio/ejemplo3)

#### Archivo _atroot.scss : 
```Html
%btn{
    border-radius: 2px;
    color: #fff;
    padding: 5px 0;
    margin: 2px autor;
    text-align: left;
    width: 150px;;
}

.btn-error{
    @extend %btn;
    background-color: red;
}

.btn-ok{
    @extend %btn;
    background-color: green;
}
```

#### Archivo _colors.scss :
```Html
$font_color:#00f;
$background-color:#ddd;

body{
    color: $font_color;
    background-color: $background-color;
}
```
#### Archivo _layout.scss :
```Html
$top_maging: 0px;
$row_padding: 20px;

.container{
    width: 80%;
    margin: $top_maging auto;
}

.row{
    padding: $row_padding ;
}
```
#### Archivo _mensajes.scss :
```Html
$test: false;

body {
  @if $test {
    @error "Mensaje de error";
    @debug "Test tiene el siguiente valor: #{$test}";
  } @else {
    @warn "Mensaje de warning";
  }
}
```
#### Archivo main.scss :
```Html
// OR @iport "colors","layout";
@import"colors";
@import"layouts";
@import"botones";
@import"mesajes";
@import"_atroot.scss";
```

### - [Tareas de Sass](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/SASS/Tareas)

#### [Ejercicios 1](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/SASS/Tareas/ejercicio1)

> Este es el ejemplo 2 pero mas simple que el que esta ahi.

![Ejemplo_de_proyecto](/UTILIDADES/img/ejer1.png)

#### [Ejercicios 2](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/SASS/Tareas/ejercicio2)

> Uso de SassDoc :

![Ejemplo_de_proyecto](/UTILIDADES/img/sassdoc.png)

#### [Ejercicios 3](https://github.com/Alumno-Alexandru/Curso_Html_css/tree/564779398c160a1e2c4108669f579b39d3e966b7/SASS/Tareas/ejercicio3/P2.1_maquetacion_landing_abogados)

> Esta es la imagen que hay que realizar con archivo `Sass` y `Html` como tarea 

![Ejemplo_de_proyecto](/UTILIDADES/img/Tarea3.png)
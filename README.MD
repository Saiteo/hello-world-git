# Version del curso
Version actual 1.2.2

# Cabeceras
# Cabecera H1
## Cabecera H2
### Cabecera H3
#### Cabecera H4
##### Cabecera H5
###### Cabecera H6

# Underlines
Underline 1
-----------

Underline 2
===========

# Formatos de enfasis
- formato *italica* de la primer forma.
- formato _italica_ de la segunda forma.
- formato **bold o strong** de la primer forma.
- formato __bold o strong__ de la primer forma.
- formato ~~tachado~~,formato normal.
- aqui podemos usar formato *italico*, pero tambien **bold** y ~~tachado~~.

# Listas
1. Esto es un item.
2. Esto es un item.
3. Esto es un item.
- Esto es un item de lista desordenada.  
- Esto es un item de lista desordenada.  
- Esto es un item de lista desordenada.  

# Links
- <a href="http://google.com">Esto es un link HTML</a>
- [Esto es un link en Markdown](http://www.google.com)
- [Esto es un link en index](index.html)

# Imagenes
![Logo Github](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.freepng.es%2Fpng-oez8r2%2F&psig=AOvVaw1E6cpFL9OAdelrXiiNckeC&ust=1650930335773000&source=images&cd=vfe&ved=0CAwQjRxqFwoTCKi3uPXwrfcCFQAAAAAdAAAAABAJ)

# Code Snipepets
Codigo en JSON
```JSON
{
    "marcadores": [
      {
        "latitude": 40.416875,
        "longitude": -3.703308,
        "city": "Madrid",
        "description": "Puerta del Sol"
      },
      {
        "latitude": 40.417438,
        "longitude": -3.693363,
        "city": "Madrid",
        "description": "Paseo del Prado"
      }
```
Codigo en Javascript
```Javascript
let miImage = document.querySelector('img');
miImage.onclick = function () {
    let miSrc = miImage.getAttribute('src');
    if (miSrc === 'images/firefox-icon.png') {
      miImage.setAttribute('src','images/firefox2.png');
    } else {
      miImage.setAttribute('src', 'images/firefox-icon.png');
    }
}
```

# Tablas
| Nombre | Apellido | Documento |
|--------|----------|-----------|
| Alfredo| Test     | 23424     |
| fRED   | White    | 23432     |


# Citas
Esto es un texto referente a una cita que pondremos debajo:
> Esto es una cita.

Esto es otro texto que no se relaciona con la cita anterior:
> Esto es otra cita.

# Lineas Divisoras
Esto es un texto que sera dividido por guiones medios.

---
Este es otro texto dividido por asteriscos.


***

Esto es otro texto dividido por guiones bajos.

___

# Saltos de linea
Esto es nuestro primer parrafo.

Esto es nuestro segundo parrafo.

Esto es nuestro tercer parrafo.
- Lista

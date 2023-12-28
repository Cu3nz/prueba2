# Esto es un encabezado h1

**texto en negrita**

## Esto es un encabezado h2 

***cursiva y negrita***

### esto es un encabezado h3 donde ya no tiene la linea de separacion 

**texto en negrita** 

#### esto es un encabezado h4 donde ya no tiene la linea de separacion. 

**texto en negrita** 



`$ pwd`

`$ let existeCeldaNombre = document.getElementById("celdaNombres");`

```
function añadirHijoANombres(){

    let existeCeldaNombre = document.getElementById("celdaNombres");

    let nombrePromt = prompt("Introduce el nombre que quieres añadir a la lista");

    if (existeCeldaNombre){ //? Si existe la celda que hemos pulsado hacemos lo siguiente

        let nuevoLi = document.createElement("li"); //? Creo el nuevo elemento li

        /* let textoPromt = document.createTextNode(nombrePromt); */ 

        let listaNombres = document.getElementById("listaNombres");

        nuevoLi.textContent = nombrePromt; //? Al nuevo elemento li le pasamos el texto que quiero almacenar en el li

        

        console.log(nuevoLi);

        listaNombres.appendChild(nuevoLi);


    } else {
        alert("La celda que has pulsado no se encuentra.");
    }
}
```

# Enlaces 

[Enlace para la pagina web](https://markdown.es/sintaxis-markdown/#enfasis)

[Enlace a la pagina web del instituto](https://iesalandalus.org/joomla/)


# Listas ordenadas y desordenadas 

> Lista desordenada
> Añadir más cuando sea necesario por favor 

* lista 1 
* lista 2
* lista 3

> Listas Ordenadas con las provincias de andalucia 

1. Almería
2. Granada
3. Jaén
4. Córdoba
5. Sevilla
6. Huelva
7. Cádiz
8. Málaga






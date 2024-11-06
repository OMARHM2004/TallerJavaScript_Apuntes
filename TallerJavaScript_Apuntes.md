Conocer sintaxis MarkDown

1.- Parrafos [Parrafo 1..]

Parrafo 1..
Lorem Ipsum es simplemente el texto de relleno de las imprentas y archivos de texto. Lorem Ipsum ha sido el texto de relleno estándar de las industrias desde el año 1500, cuando un impresor (N. del T. persona que se dedica a la imprenta) desconocido usó una galería de textos y los mezcló de tal manera que logró hacer un libro de textos especimen. No sólo sobrevivió 500 años, sino que tambien ingresó como texto de relleno en documentos electrónicos, quedando esencialmente igual al original. Fue popularizado en los 60s con la creación de las hojas "Letraset", las cuales contenian pasajes de Lorem Ipsum, y más recientemente con software de autoedición, como por ejemplo Aldus PageMaker, el cual incluye versiones de Lorem Ipsum.

_cursiva_
**negrito**
-tachado-
**_cursiva y negrito_**
_*cursiva y tachado*_
**-negrito y tachado-**
**_-cursiva, negrito y tachado-_**

Encabezados
# Encabezado Nivel 1
## Encabezado Nivel 2
### Encabezado Nivel 3
#### Encabezado Nivel 4
##### Encabezado Nivel 5
###### Encabezado Nivel 6

Diviciones
Un bloque de contenido
---
Esto es otro bloque de contenido

Listas: Podemos utilizar las listas ordenadas y listas desordenadas
1. html5
1. css
1. javascript
1. Ajax
1. Json

- html5
- css
- javascript
- Ajax
- Json

Citas: Podemos dar formato de cita a un texto, anteponiendo a la linea de texto un caracter de mayor que (>)
> La IA en el futuro remplazara muchas profeciones 
> ChatGPT debe potenciar el aprendizaje, no suprimir mi estado autodidacta
> 
>OmarHernandez

Enlaces
[YouTube](https://www.youtube.com)
[Enlace a Google](https://www.google.com)

Imagenes
![Texto Alternativo](URLdelaimagen)

Tablas

|Columna 1|Columna 2|Columna 3|
|---------|---------|---------|
|A        |B        |C        |
|D        |E        |F        |
|G        |H        |I        |

Codigo: Podemos dar formato de codigo a un texto, para ello se usa el acento grave (`).
Esto es `codigo` en linea.

En _JavaScript_ una variable se define asi: 
`left saludo = "Hola Mundo";

Pero si queremos sacar un bloque completo de codigo utilizamos ':
```

```

```
let Peso;
let Estatura;

Estatura=prompt("Ingrese su estatura");
Peso=prompt("Ingrese su peso");
let peso=parseInt(Peso);
let estatura=parseInt(Estatura);

console.log("Tu Indice de Masa Corporal es: " + (Peso / (Estatura * Estatura)));

let iIMC=Peso / (Estatura * Estatura);
if(iIMC <= 18.5){
    console.log("Bajo Peso")
}else{
    iIMC >= 24.9
    console.log("Peso Saludable")
}

if(iIMC >= 25.0){
    console.log("Sobrepeso")
}

if(iIMC >= 30.0){
    console.log("Obesidad")
}
```

```
let estudiante="Juan Perez";
let edad=19;
let isEstudiante=true;
let calificacion=92.2;
```
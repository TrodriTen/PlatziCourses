# Conceptos Básicos de Computación

Las computadoras nacen de que los seres humanos busquemos simplificar nuestro estilo de vida. 

Algunos componentes esenciales para entender cómo funciona un computador:

- Pixel $\longrightarrow$ Fragmento fisico minimo de una pantalla
- Hardware $\longrightarrow$ Componentes fisicos del computador
- Software $\longrightarrow$ Programas y sistemas logicos que controlan y usan el hardware
- Bit $\longrightarrow$ Unidad minima de informacion representada por (0 o 1)

## Bases numericas

- Hexadecimal $\longrightarrow$ numeros del 1 al 15 y es base 16
- Decimal $\longrightarrow$ Contando en base 10 (Cantidad de dedos)
- Binaria $\longrightarrow$ 0 o 1 y es en base 2.


<img src='../Images/Bases_Numericas.png'>

> Fun fact: Un byte tiene 8 bits porque los primeros PCs tenian 8 cables.

### Binarios 
$$
    2^n
$$
$$
    01010100 \longrightarrow 84
$$
$$
    2^2 + 2^4 + 2^6 = 84
$$
- El primer bit $0$ es especial porque determina el signo del valor
- Con ellos se pueden representar:
    + Numeros
    + Texto 
    + Imagenes (Pixeles)
    + Videos (Imagenes por segundo)
    + Musica


### Codificacion y representacion de caracteres

- ASCII $\longrightarrow$ Tabla que permite codificar caratcreres en forma numerica
- UTF $\longrightarrow$ Unicode Transformation Format, es como la version 2 de ASCII, contiene mas caracteres, emojis, alfabetos, etc.

## Seguridad Informatica
+ Hay distintos tipos de virus:
  * De gusano
  * Adware
  * Spyware
  * Ransomware
  * Troyanos
  * Botnet

## Formatos de Archivos

Los archivos se pueden ver de la siguente manera: 

<img src='../Images/Archivo.png'>

Este archivo tiene la representacion en 3 formas:

1. Columna 1 $\Longrightarrow$ Codigo **ASCII**
2. Columna 2 $\Longrightarrow$ Expresion Hexadecimal
3. Columna 3 $\longrightarrow$ Documento (Cabecera posee el tipo de archivo que es)

> Esteganografia (Ocultar archivos en un archivo diferente)
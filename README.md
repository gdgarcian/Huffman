# Huffman
Algoritmo de compresión de Huffman con BASE64

## Funcionamiento

El funcionamiento de este algoritmo se divide en dos fases: La primera, que es la codificación de la imagen en archivo .gif a BASE64; y la segunda, que consiste en la compresión de estos datos utilizando el algoritmo de compresión de Huffman.

### Codificación BASE64  

En este punto se recibe la imagen, y se convierte en un juego de caracteres limitado a 64 caracteres a-z, A-Z, +, / (de aquí el nombre Base 64). Esta conversión se da para manipular la imagen de manera que se puedan modificar los caracteres que la componen. Esto es necesario para el siguiente paso

### Algoritmo de Huffman  

Aquí se aplica el algoritmo de Huffman con el string resultante del paso anterior.

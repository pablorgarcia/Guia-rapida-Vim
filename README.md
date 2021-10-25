# Guía rápida para Vim y Neovim Tutorial ejemplo

Comandos de Vim y Neovim comunes

[pablogarcia.dev/notes/vim](https://pablogarcia.dev/notes/vim)

## Entrar a Vim desde la terminal
`$ vim <nombre-del-archivo>`

## Salir del editor
`:q`

si no hemos guardado y queremos forzar la salida
`:q!`

## Moverse por el editor
Las teclas `h` e `izquierda` deplazará el cursor hacia la **izquirda**
Las teclas `l` y `derecha` deplazará el cursor hacia la **derecha**
Las teclas `k` y `arriba` deplazará el cursor hacia **arriba**
Las teclas `j` y `abajo` deplazará el cursor para la **abajo**

Las teclas `w` y `cntrl + derecha` llevan el cursor al comienzo del **siguiente texto**
Las teclas `b` y `cntrl + izquierda` llevan el cursor al comienzo del **anterior texto**
La tecla `e` lleva el cursor al final del **siguiente texto**
Las teclas `Shift + a` llevan el cursor al final de la linea

## Los modos
### ¿Qué son los modos?
Ej: Si pulsamos la tecla _Shift_ entramos en **el modo** mayuscula.
- Modo **-- INSERT --** para editar el archivo, con las teclas `i` o `a`.

## Para editar el archivo
Para entrar en el modo --INSERT-- podemos entrar de dos formas, con la tecla `i` entraremos a la izquierda del caracter donde estemos, con la `a` nos entraremos a la derecha del caracter donde estemos.
Para salir presionamos la tecla `Esc`

## Para eliminar texto del archivo
En el modo --NORMAL-- `esc` eliminamos caracteres con la tecla `x`

## Para guardar el archivo
En el modo --NORMAL-- `esc` guardamos con `:w`

## Para guardar el archivo y salir del editor 
En el modo --NORMAL-- `esc` guardamos y salimos con `:wq`

## Movernos entre archivos dentro del editor


**Fuentes**:

https://github.com/nschurmann

https://www.udemy.com/course/vim-aumenta-tu-velocidad-de-desarrollo/

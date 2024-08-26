# Encriptador de Texto

Este proyecto es una aplicación web simple que permite encriptar y desencriptar textos utilizando un conjunto de reglas específicas. La encriptación se realiza sustituyendo ciertas letras por secuencias de caracteres, permitiendo intercambiar mensajes secretos con otras personas que conozcan la misma clave.

## Llaves de Encriptación

Las reglas de encriptación son las siguientes:

- La letra `e` se convierte en `enter`
- La letra `i` se convierte en `imes`
- La letra `a` se convierte en `ai`
- La letra `o` se convierte en `ober`
- La letra `u` se convierte en `ufat`

Por ejemplo:

- `gato` se convierte en `gaitober`
- `gaitober` se convierte de nuevo en `gato`

## Características

- **Encriptar texto**: Convierte un texto normal a su versión encriptada usando las llaves de encriptación.
- **Desencriptar texto**: Restaura un texto encriptado a su forma original.
- **Copiar texto**: Puedes copiar el texto encriptado o desencriptado al portapapeles con un solo clic.

## Requisitos

- Solo se permiten letras minúsculas.
- No se admiten letras con acentos ni caracteres especiales.


## Estructura del Proyecto

- `index.html`: Contiene la estructura de la página web.
- `styles.css`: Contiene los estilos de la página web.
- `script.js`: Contiene la lógica de encriptación y desencriptación.

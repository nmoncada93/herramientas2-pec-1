

## Metodologia escogida: **BEM**

*Consultar Apuntes-BEM.md*


# SASS Requisitos de uso:

- Variables
- Anidado
- Funciones
- Parciales
- Importación


## Checklist

- Web resposive
- usar FontAwesome
- Revisar estructura de carpetas


## google fonts

Orbitron
Space Mono
Anton
Press Start 2P (con un estilo retro de juegos espaciales)
Teko

## stylelint config (.stylelintrc)

https://stylelint.io/user-guide/rules/



#### SI FUNCIONA
"selector-class-pattern": "^.[a-z]([a-z0-9-]+)?(__([a-z0-9]+-?)+)?(--([a-z0-9]+-?)+){0,2}$",
"color-named": "never", //NO PERMITIR VALORES CON NOMBRES PARA COLORES
"declaration-empty-line-before": "never", // NO PERMITTIR UNA LINEA VACIAS ANTES DE LA DECLARACIONES
"unit-allowed-list": ["rem", "%", "rgb", "rgba", "hsl", "hsla", "px", "s", "vh"],//UNIDADES PERMIIDAS
"color-no-invalid-hex": true, // NO PERTMITIR COLOES HEXADECIMALES NO VALIDOS
"length-zero-no-unit": true, //DESABILITAR UNIDADES PARA VALORES 0


#### TESTEANDO
"string-no-newline": true, //NO PERMITIR SALTOS DE LINEA NO VALIODS DENTRO DE CADENAS

"color-hex-length": "short", // ESPECIFICA LA NOTACION CORTA DE COLORES HEXADECIMALES. GUIA MDO


"no-irregular-whitespace": true, //NO PERMITIR ESPACIOS EN BLANCO IRREGULARES
"selector-attribute-quotes": "always"//REQUERIR COMILLAS PARA VALOES DE ATRIBUTOS


#### NO TESTEANDO


*/

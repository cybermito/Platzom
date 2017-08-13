# Platzom

Platzom es un idioma inventado para el [Curso de Fundamentos de Javascript](https://platzi.com) de [Platzi](https://platzi.com). Educación Online.

## Descripcion del idioma

- Si la palabra termina en "ar", se le quitan esos dos caracteres
- Si la palabra inicia con Z, se le añade "pe" al final
- Si la palabra traducida tiene 10 o más letras, se debe partir a la mitad y unir con un guión del medio
- Si la palabra original es un palíndromo, ninguna regla anterior cuenta y se devuelve la misma palabra intercalando mayúsculas y minúsculas

## Instalación

```
npm install platzom
```

## Uso
```
import platzom from 'platzom'

console.log(platzom("Programar")) // Program
console.log(platzom("Zorro")) // Zorrope
console.log(platzom("Zarpar")) // Zarppe
console.log(platzom("abecedario")) // abece-dario
console.log(platzom("sometemos")) // SoMeTeMoS
```

## Créditos

- [Antonio Mesa](https://twiter.com/@cybermito)

## Licencia

[MIT](https://opensource.org/licenses/MIT)

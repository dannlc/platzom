# Platzom

Platzom es un idioma inventado para el curso de fundamentos de JS de [Platzi](https://platzi.com/js), un lugar piola para aprender.

## Descripcion del idioma
-Si la palabra termina en "ar", se le quitan esas dos letras.
-Si la palabra inicia con Z, se le añade "pe" al final.
-Si la letra traducida tiene 10 o mas letras, se debe partir en dos por la mitad y unir con un guion medio.
-Por ultimo si la palabra original es un palindromo, ninguna regla anterior cuenta y se le devuelve la misma palabra pero intercalando letras mayusculas y minusculas.

##Instalacion
```
npm install platzom
```

##Uso
```
import platzom from 'platzom'

platzom("Programar") //Program
platzom("Zorro") //Zorrope
platzom("Zarpar") //Zarppe
platzom("abecedario") //abece-dario
platzom("sometemos") // SoMeTeMoS
```

##Creditos
-[Sacha Lifszyc](https://twitter.com/@slifszyc)

##Licencia

[MIT](https://opensource.org/licenses/MIT)
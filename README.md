# platzom
prueba de idioma
## descripcion de idioma (como funciona)

regla 1: si la palabra termina con ar se quitan las ar
regla 2: si inica con z añade ap
3 si tiene 10 o mas letras se debe partir por la mitad y unir con guion
4 si es un palindromono niguna regla cuenta cuenta

## instalacion 
npm install platzom

## Uso
import platzom from 'platzom'

  console.log(platzom("Programar")) // Program
  console.log(platzom("Zorro")) // Zorrope
  console.log(platzom("Zarpar")) // Zarppe
  console.log(platzom("abecedario")) // abece-dario
  console.log(platzom("sometemos")) // SoMeTeMoS 

  ## creditos
  Jorge cortes 

  ## Licencia
  MIT

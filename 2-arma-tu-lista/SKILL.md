---
name: arma-tu-lista
description: "Convierte tu cliente ideal en una lista real de empresas y contactos, con el mini-test de 10 que evita gastar dinero en un nicho que no sirve. Gatillos: arma mi lista, dónde saco leads, necesito prospectos, cómo scrapeo, quiero contactos."
---

# Arma tu lista

Pasas de la definición del cliente a una lista con nombre, empresa y correo.

⚠️ **Antes de nada: nunca compres una lista hecha.** Se la vendieron a otros cien antes que
a ti, viene muerta y te quema el dominio. Una lista se construye.

## Paso 1: el filtro

Toma la definición de `define-tu-cliente` y tradúcela a criterios de búsqueda:

```
Sector:      lo que hace la empresa
País:        uno a la vez, no mezcles
Tamaño:      pon el piso, casi siempre 11 empleados
Puesto:      fundador, CEO, director. Nunca "empleado"
```

**Y lo que casi nadie hace: las palabras que NO quieres.** Si buscas "marketing" te van a
salir escuelas de marketing, software de marketing y freelancers de marketing. Escribe la
lista de exclusión antes de buscar, no después.

## Paso 2: el mini-test de 10. Este paso no se salta

**Antes de sacar mil, saca diez.** Cuesta centavos y te dice si el nicho entero sirve.

De esos 10, cuenta:

- ¿Cuántos son de verdad el cliente que definiste? Si menos de 5, tu filtro está mal.
- ¿Cuántos traen un correo que existe? Si menos de 4, ese nicho está lleno de correos
  genéricos que no llegan a nadie.
- ¿Cuántos son empresas reales y no directorios, escuelas o agregadores?

**Si el mini-test sale mal, para.** No lo arregles sacando más. Más volumen de un pozo
malo es más basura.

## Paso 3: el número que decide

Divide lo que gastaste entre los leads que **de verdad sirven**. No entre los que sacaste.

```
Si sale en centavos  →  el nicho está sano, sigue
Si sale en dólares   →  el nicho está quemado, cámbialo
```

Ese número integra todo lo que puede estar mal a la vez: universo agotado, correos
inalcanzables, nicho equivocado. Es una sola cifra y es barata de medir.

**Cambiar de país no arregla un nicho malo.** Es el error más caro y el más común: cuando
el pozo se seca la reacción es buscar en otro lado, cuando lo que hay que cambiar es a
quién le escribes.

## De dónde sacar los datos

Ordenados de más barato a más caro. **Empieza por el gratis.**

1. **A mano, con búsquedas.** Google, LinkedIn, directorios del sector, listas de
   asociaciones, expositores de ferias. Lento pero gratis, y para las primeras 50 sirve.
2. **Google Maps**, si tu cliente es un negocio con local. Trae nombre, web y teléfono.
3. **Herramientas de scraping de pago** (Apify, Apollo y similares). Solo cuando ya
   validaste el nicho con el mini-test. Pagar por scrapear un nicho sin validar es
   exactamente cómo se quema el presupuesto.

**No necesitas herramientas de pago para empezar.** Necesitas 50 contactos correctos, y
esos los sacas a mano en una tarde.

## Qué entregas

Una tabla, en un archivo `.csv` o en una hoja de cálculo:

```
nombre | apellido | empresa | puesto | web | correo | ciudad | de dónde salió
```

**La columna "de dónde salió" no es opcional.** En un mes no vas a acordarte de qué
búsqueda trajo a quién, y es lo que te dice qué fuente repetir.

## Reglas

- **El nombre de pila se separa.** Vas a escribir "Hola María" y muchas fuentes traen el
  nombre completo en una sola columna. Sepáralo al armar la lista, no después.
- **Un país por lista.** Mezclar husos horarios y formas de hablar arruina las dos.
- **Guarda los descartados en otro archivo.** Es tu memoria de a quién ya miraste.
- Si el usuario no tiene ninguna herramienta contratada, arma la lista a mano con él. El
  mini-test funciona igual y el criterio es el mismo.

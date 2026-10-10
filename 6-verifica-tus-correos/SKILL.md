---
name: verifica-tus-correos
description: "Revisa que cada correo de tu lista exista antes de mandarle nada, y deja entrar solo los buenos. Protege tu dominio de los rebotes. Gatillos: verifica los correos, valida mi lista, cuántos rebotan, million verifier, estos correos existen."
---

# Verifica tus correos

Lleva el 6 pero **conviene correrla justo después de `limpia-tu-lista`**, antes de investigar
a nadie: investigar a alguien cuyo correo no existe es tiempo tirado. Y si ya pasó tiempo,
se corre otra vez justo antes de mandar. Escribirle a un correo que no existe no solo se
pierde: te cobra.

## Por qué no es opcional

Cada correo que rebota le dice a Gmail y a Outlook que no sabes a quién le escribes.
Con pocos rebotes te empiezan a mandar a spam, **y eso pega en todos tus correos, no solo
en los malos.** Una lista sin verificar puede tirar un dominio en una semana.

**"Verificado" en la herramienta de donde sacaste la lista no es lo mismo.** Apollo, Apify y
similares marcan correos como verificados con su propio criterio, a veces de hace meses.
Se verifica otra vez, justo antes de mandar.

## Cómo se hace

Con un verificador de correos (Million Verifier, NeverBounce, ZeroBounce o similar).
Subes la lista y te regresa cada correo en una de tres:

```
GOOD (o valid)      el buzón existe y recibe        → entra
RISKY (o catch-all) el servidor acepta todo, no se sabe → fuera
BAD (o invalid)     no existe                        → fuera
```

**Solo entra GOOD.** RISKY se siente como tirar dinero porque "a lo mejor sí existe". No
entra. Un dominio cuesta más que cualquier lista.

## Cuántos por empresa

Si una empresa trae muchos contactos, **máximo 3 por empresa.** Si le escribes a diez
personas del mismo lugar el mismo día, se reenvían tu correo entre ellos y se ve como lo
que es.

## Qué entregas

La lista con una columna nueva, `verificacion`, y el resumen:

```
Entraron a verificar:  568
GOOD:                  408  (72%)  ← estos van
RISKY:                 104
BAD:                    56
```

## Cómo se lee

- **GOOD arriba del 70%** → la fuente está sana.
- **GOOD abajo del 50%** → la fuente trae correos viejos o inventados. Cambia de fuente
  antes de sacar más.
- **No te alcanza para la meta** → sacas más de la misma fuente y verificas otra vez. **No
  bajas el estándar a RISKY para llegar al número.** Si no llegas, lo dices tal cual.

## Reglas

- **Se verifica justo antes de mandar.** Un correo bueno hace tres meses puede no existir hoy.
- **Guarda los BAD y RISKY** en otro archivo. Si los vuelves a sacar, ya sabes que no.
- El número lo da el verificador, nunca un cálculo. Si Claude te dice "seguro sale el 80%",
  es una suposición hasta que lo corres.

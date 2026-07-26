# Skills de Claude Code para conseguir clientes

El proceso completo para pasar de "no sé a quién escribirle" a tener correos listos para
mandar. Son las mismas que uso yo, simplificadas para que funcionen en tu máquina desde el
primer día.

**No necesitas pagar ninguna herramienta para usarlas.** Si después contratas algo para
scrapear, se integra solo, pero para empezar no hace falta.

**Empieza por la 0.** Te hace un diagnóstico, te dice de frente si el correo en frío te
conviene o no, y deja escrito un `CLAUDE.md` con tu negocio. A partir de ahí las otras
cinco dejan de ser genéricas y trabajan con tu contexto.

---

## Qué es una skill, en una frase

Una instrucción guardada. En vez de explicarle a Claude Code todo el proceso cada vez que
abres una sesión, le dices el nombre y ya sabe qué hacer, en qué orden y qué reglas seguir.

---

## Cómo se instalan (2 minutos)

**1. Instala Claude Code**, si no lo tienes.
Está en <https://claude.com/claude-code>. Funciona en Windows, Mac y Linux.

**2. Bájate las skills.** Si sabes usar git:

```bash
git clone https://github.com/GaelProspectlab21/skills-prospeccion.git
```

Y si no, dale al botón verde de **Code** arriba y luego a **Download ZIP**. Lo
descomprimes y listo, es lo mismo.

**3. Copia las carpetas** a tu proyecto, dentro de `.claude/skills/`.

Si tu proyecto está en `C:\mi-negocio`, las skills van así:

```
C:\mi-negocio\.claude\skills\0-diagnostica-tu-negocio\SKILL.md
C:\mi-negocio\.claude\skills\1-define-tu-cliente\SKILL.md
C:\mi-negocio\.claude\skills\2-arma-tu-lista\SKILL.md
C:\mi-negocio\.claude\skills\3-limpia-tu-lista\SKILL.md
C:\mi-negocio\.claude\skills\4-investiga-tus-leads\SKILL.md
C:\mi-negocio\.claude\skills\5-escribe-el-correo\SKILL.md
```

**4. Abre Claude Code en esa carpeta y escribe `/`.** Deberían aparecer las seis.

Si no aparecen, cierra Claude Code y ábrelo otra vez. Las skills se leen al arrancar.

---

## El orden importa, y mucho

Corren en cadena. Cada una necesita lo que hizo la anterior.

```
0. diagnostica-tu-negocio  →  tu contexto, y tu CLAUDE.md      (una sola vez)
1. define-tu-cliente       →  a quién le escribes
2. arma-tu-lista           →  quiénes son, con nombre y correo
3. limpia-tu-lista         →  quita a los que nunca te van a comprar
4. investiga-tus-leads     →  el dato concreto de cada uno
5. escribe-el-correo       →  el correo, con ese dato
```

**La 0 corre una vez y te ahorra repetirte.** Deja un `CLAUDE.md` con tu negocio que las
demás leen solas, así dejan de darte consejos genéricos. Y te dice de frente si el correo
en frío te conviene, que a veces la respuesta honesta es que no.

**Saltarte la 1 o la 3 es lo que hace que la gente mande mil correos y no le contesten.**
La 3 se siente como que estás tirando trabajo a la basura, y es justo al revés: es donde
dejas de pagar por gente que no te iba a comprar nunca.

---

## Las tres reglas que hacen que esto funcione

**Antes de sacar mil, saca diez.** El mini-test de la skill 2 cuesta centavos y te dice si
el nicho entero sirve. Es la decisión más barata de todo el proceso.

**Divide lo que gastaste entre los leads que de verdad sirven.** Si te sale en centavos, el
nicho está sano. Si te sale en dólares, está quemado y hay que cambiarlo. Cambiar de país
no arregla un nicho malo.

**Sin un dato real de la empresa no hay correo bueno.** Si el correo que escribiste se lo
podrías mandar igual a otra empresa, todavía no está listo.

---

## Lo que estas skills NO hacen

Para que no te lleves una sorpresa:

- No mandan los correos. Eso lo haces tú o con una herramienta de envío.
- No consiguen correos que no estén publicados en algún lado.
- No arreglan una oferta que no le interesa a nadie. Si nadie te compra en caliente,
  tampoco te van a comprar en frío.

---

Hechas por Gael Sosa. Si te sirvieron, cuéntame en los comentarios qué nicho elegiste.

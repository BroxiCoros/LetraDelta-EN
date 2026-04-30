# DELTARUNE · Pack de idioma inglés

Pack de idioma inglés para el mod [*Deltranslate*](https://github.com/Neprim/Deltranslate) de Neprim, distribuido como complemento del proyecto [*LetraDelta*](https://github.com/BroxiCoros/LetraDelta) (traducción al español americano de *DELTARUNE*).

Este repositorio existe por un motivo concreto. *Deltranslate*, en su modo multi-idioma, sustituye los textos del juego por los del paquete de idioma activo en lugar de leerlos del `data.win`. Al instalar la traducción al español, el inglés original deja de estar disponible si no se incluye también un paquete que lo contenga. *LetraDelta-EN* cumple esa función: conserva los textos en inglés tal como aparecen en el juego original, organizados según la estructura que el mod espera.

El contenido se basa en el [*EngDeltranslatePack*](https://github.com/Lazy-Desman/EngDeltranslatePack) de LazyDesman, reorganizado para encajar en el formato multi-idioma de *Deltranslate* (subcarpeta `lang/en/`, código de idioma `en`). No es una variante editorial del inglés, ni una localización a otra región: es el inglés original del juego, empaquetado para que el mod pueda servirlo junto con el español.

**Servidor de Discord del proyecto:** https://discord.gg/ndkjnhXPPr

---

## Para qué sirve este repositorio

En la práctica, los jugadores de *LetraDelta* no instalan este paquete por su cuenta. El [instalador automático](https://github.com/BroxiCoros/LetraDeltaInstaller) lo descarga junto con el pack de español, de modo que el juego termina con los dos idiomas disponibles y se puede alternar entre ellos desde el menú interno del mod.

El repositorio se mantiene aparte, en lugar de incluir el inglés dentro de [`LetraDelta`](https://github.com/BroxiCoros/LetraDelta), por dos razones:

- **Separación de mantenimiento.** El pack de español se actualiza con frecuencia conforme avanza la traducción; el de inglés solo se toca cuando hay cambios estructurales o cuando *DELTARUNE* recibe contenido nuevo. Mantenerlos en repositorios distintos evita que las publicaciones de un pack arrastren al otro.
- **Limpieza del repositorio principal.** El repositorio [*LetraDelta*](https://github.com/BroxiCoros/LetraDelta) contiene exclusivamente material en español, lo que facilita la navegación y la coordinación con el equipo de traducción.

---

## Instalación

Lo habitual es que el [instalador de *LetraDelta*](https://github.com/BroxiCoros/LetraDeltaInstaller) se encargue automáticamente. Se documenta a continuación la instalación manual por completitud.

### Vía recomendada — Instalador automático

El [`InstaladorLetraDelta`](https://github.com/BroxiCoros/InstaladorLetraDelta/releases/latest) descarga este pack y el de español en una sola operación, los aplica al juego y deja los dos idiomas disponibles. No hay que descargar nada de este repositorio a mano.

### Vía manual — Reemplazo directo de archivos

Para quienes ya tengan el mod *Deltranslate* aplicado y deseen añadir el pack de inglés por separado:

1. Descargar `lang.7z` de la [última versión](../../releases/latest).
2. Extraer su contenido en la carpeta del juego (normalmente en `Steam/steamapps/common/DELTARUNE`). El paquete crea o actualiza la subcarpeta `lang/en/` sin afectar al resto.
3. Iniciar el juego.

> El `.7z` está pensado para coexistir con otros paquetes de idioma (multi-idioma). Si solo se desea jugar en inglés, también se distribuye `lang.zip`, que extrae el contenido bajo `lang/` directo y reemplaza cualquier paquete previo.

---

## Repositorios del proyecto

| Repositorio                                                                    | Contenido                                             |
| ------------------------------------------------------------------------------ | ----------------------------------------------------- |
| **[LetraDelta](https://github.com/BroxiCoros/LetraDelta)**                     | Pack de español (`lang/`).                            |
| **[LetraDelta-EN](https://github.com/BroxiCoros/LetraDelta-EN)**               | Este repositorio. Pack de inglés.                     |
| **[DeltranslatePatch](https://github.com/BroxiCoros/DeltranslatePatch)**       | *Fork* del mod *Deltranslate* con un refactor propio. |
| **[InstaladorLetraDelta](https://github.com/BroxiCoros/InstaladorLetraDelta)** | Instalador `.exe` para Windows.                       |

---

## Créditos y reconocimientos

A **Neprim**, por el desarrollo de [*Deltranslate*](https://github.com/Lazy-Desman/DeltranslatePatch).

A **LazyDesman**, por el [*EngDeltranslatePack*](https://github.com/Lazy-Desman/EngDeltranslatePack), del que se toma el contenido en inglés que sirve de base a este pack.

A **Toby Fox** y al equipo de desarrollo de *DELTARUNE*, autores de los textos originales.

---

## Aviso legal

Este proyecto es un complemento no oficial sin vínculo alguno con Toby Fox ni con *DELTARUNE*. Todos los derechos sobre el juego, sus personajes, su música y sus imágenes pertenecen a sus respectivos propietarios.

El repositorio contiene los textos en inglés tal como aparecen en el juego original, organizados con fines de compatibilidad con el mod *Deltranslate*. Para jugar es indispensable poseer una copia legítima de *DELTARUNE*.

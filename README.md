# Calculadora mágica (estilo iPhone)

Calculadora que se comporta como la de iOS y esconde dos efectos. Es una app web instalable (PWA): no necesita cuenta de desarrollador ni App Store.

## Publicar en GitHub Pages
1. Crea un repositorio y sube todo el contenido de esta carpeta.
2. Settings → Pages → Branch: `main` / root → Save.
3. Abre la URL `https://TU_USUARIO.github.io/TU_REPO/` en Safari.
4. Compartir → **Añadir a pantalla de inicio**. Se abre a pantalla completa, sin barra de Safari, y funciona sin conexión.

## Ajustes ocultos
Mantén pulsado 1 segundo el icono de calculadora (arriba a la derecha).

- **Normal**: calculadora real (encadenado, %, ±, borrar, repetir `=`, coma decimal).
- **Forzar**: el primer número que se teclee muestra el valor elegido (cualquier tecla numérica, da igual cuál). Valores: número fijo, fecha de hoy (DDMMAAAA, DDMMAA, DDMM) o hora, con desfase de días.
- **Colectivo**: los espectadores dictan números que tú tecleas con `+`. En el último `+`, mantén pulsado 0,7 s (se registra como un `+` normal); el siguiente número que teclees, con cualquier dígito, mostrará el que falta y `=` dará exactamente el valor elegido.

## Límites conocidos
- Con 8 dígitos la pantalla muestra `15.112.026`; activa «sin puntos de millar» para que parezca una fecha.
- Una fecha con día menor que 10 pierde el cero inicial.
- Pulsa más dígitos de los previstos y se ignoran.

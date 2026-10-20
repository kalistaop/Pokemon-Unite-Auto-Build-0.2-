# Gabi Unite · Acepta (Android)

App "Acepta" (builds meta de Pokémon UNITE) empaquetada con Capacitor. Funciona sin conexión: todo está en `www/`.

## Crear el APK desde el teléfono (sin PC)
1. Descomprime este ZIP.
2. En GitHub crea un repositorio nuevo (por ejemplo `gabi-unite-android`).
3. Sube TODO el contenido a la raíz. Debe verse `.github/workflows/build-apk.yml`.
4. Pestaña **Actions** → **Build Gabi Unite APK** → **Run workflow** (si no arrancó solo).
5. Al terminar en verde, abre la ejecución y descarga **gabi-unite-debug-apk** (Artifacts). Dentro está `app-debug.apk`.
6. Ábrelo en Android y permite instalar desde esa fuente.

## Qué hace
- Elige un Pokémon, "Un clic" equipa la build meta, la copias y la marcas en el juego.
- Interruptor **Aceptar partida automáticamente**: solo actúa dentro de esta app (cola simulada).

## Límites
- No lee la pantalla de Pokémon UNITE, no lo modifica ni toca el juego. No acepta partidas reales.
- Las builds son orientativas; verifícalas contra el parche actual.
- APK de depuración, no firmado para tienda.
- Las fuentes de Google se cargan solo con internet; sin conexión se usa una fuente del sistema.
- No afiliado a Nintendo, The Pokémon Company ni TiMi Studio Group.

# Azbuka — voces

Audios de la app [Азбука](https://github.com/manum876/Azbuka_v3) para aprender ruso.

- Se generan solos con GitHub Actions: **Actions → «Voces» → Run workflow**. Solo se hacen los audios que faltan, y se borran los de textos que ya no están en la app.
- La lista de textos y el generador viven en el repo de la app (`herramientas/voces/`).
- `v1/<voz>/<clave>.m4a`: AAC 48 kbps, mono. `v1/indice.json`: qué audios hay. `v1/paginas/`: qué audios usa cada página.

Voces: [Silero TTS](https://github.com/snakers4/silero-models) (modelo v5_5_ru), licencia **CC BY-NC 4.0**. Solo para uso no comercial.

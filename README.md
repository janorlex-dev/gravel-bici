# GRAVEL BICI

Aplicación web estática para organizar una búsqueda de bicicletas gravel.

## Uso local
Abre `index.html` en un navegador. No requiere instalación, servidor ni dependencias.

## Publicar en GitHub
1. Crea un repositorio, por ejemplo `gravel-bici`.
2. Sube `index.html` y `README.md` a la raíz.
3. En GitHub entra en **Settings → Pages**.
4. En **Build and deployment**, selecciona **Deploy from a branch**.
5. Elige `main` y `/ (root)`, guarda. GitHub Pages publicará la aplicación.

## Datos
- Las candidatas se guardan en `localStorage` del navegador/dispositivo.
- Usa **Exportar copia JSON** para guardar una copia y versionarla en Git.
- Usa **Importar JSON** para recuperar los datos en otro navegador.
- El repositorio contiene el programa; los datos del navegador no se sincronizan automáticamente con Git.

## Alcance de la búsqueda
Los enlaces laterales abren búsquedas externas en Milanuncios, Wallapop y tiendas. La aplicación no hace scraping ni comprueba disponibilidad en segundo plano. Los anuncios deben verificarse y añadirse manualmente. Solo se guardan candidatas que superen los filtros introducidos.

## Criterios iniciales
- Presupuesto máximo: 1.300 €
- Ámbito: 300 km desde Valladolid
- Estatura: 167 cm; talla orientativa XS/S, según geometría
- Transmisión: 2x
- Frenos: disco hidráulicos
- Mercado: nueva y segunda mano
- Marcas preferidas: BH, Orbea, Giant, Trek, Specialized y MMR
- Uso: mixto, carretera y caminos

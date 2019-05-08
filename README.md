# Propuesta MVC para Data-Lovers

- Habiendo tenido una reunión previa con todo el equipo, llegamos a la conclusión de los temas tech que las estudiantes deben saber si o si terminando el CC.

- Los temas son los siguientes:

### Tech

| Habilidad |
|-----------|
| **Computer Science** |
| Lógica |
| Arquitectura |
| **Source Control Management** |
| Git |
| GitHub |
| **JavaScript** |
| Estilo |
| Nomenclatura/semántica |
| Funciones/modularidad |
| Peticiones HTTP |
| Estructuras de datos |
| Tests |
| **HTML** |
| Validación |
| Estilo |
| Semántica |
| **CSS** |
| DRY |
| Responsive |

- Teniendo encuenta esto, propongo una nueva estructura de archivos más orientada a un Modelo-Vista-controlador (MVC). Este enfoque ayudara a las estudiantes a entender todo el proceso que hay detras de un click. Llegando así a utilizar cada herramienta requerida anteriormente, para luego no solo crear una Single Page Application (SPA) sino tambien entender el ¿Por qué? de este concepto y porque es tan requerido actualmente. 

```text
.
├── package.json
├── README.md
├── src
│   ├── css
│   │   ├── index.css
│   ├── data (según con qué data trabajes)
│   │   ├── injuries
│   │   │   ├── injuries.js
│   │   │   └── injuries.json
│   │   ├── lol
│   │   │   ├── lol.js
│   │   │   └── lol.json
│   │   ├── pokemon
│   │   │   ├── pokemon.js
│   │   │   └── pokemon.json
│   │   ├── steam
│   │   │   ├── steam.js
│   │   │   └── steam.json
│   │   └── worldbank
│   │       ├── worldbank.js
│   │       └── worldbank.json
│   ├── lib
│   │   ├── controller
│   │   │   ├── index.js
│   │   ├── view
│   │   │   ├── index.js
│   │   ├── view-controller
│   │   │   ├── index.js
│   ├── index.html
│   ├── main.js
└── test
    └── data.spec.js

13 directories, 19 files
```
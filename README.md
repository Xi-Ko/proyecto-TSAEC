# Proyecto TSAEC

## Estructura del Proyecto

```
proyecto TSAEC/
├── src/                    # Código fuente
│   ├── assets/            # Recursos estáticos
│   │   ├── images/        # Imágenes
│   │   ├── fonts/         # Fuentes
│   │   └── pdfs/          # Documentos PDF
│   ├── styles/            # Estilos CSS
│   │   ├── base/         # Estilos base
│   │   ├── components/   # Estilos de componentes
│   │   └── pages/        # Estilos específicos de páginas
│   ├── js/               # JavaScript
│   │   ├── components/   # Componentes JS
│   │   ├── utils/        # Utilidades
│   │   └── config/       # Configuraciones
│   └── pages/            # Páginas HTML
├── public/               # Archivos públicos
│   └── index.html        # Página principal
├── dist/                 # Archivos compilados (para producción)
├── docs/                 # Documentación
├── tests/               # Pruebas
├── .git/                # Control de versiones
├── .vscode/             # Configuración de VS Code
├── node_modules/        # Dependencias
├── package.json         # Configuración del proyecto
└── README.md           # Documentación principal
```

## Descripción

Este proyecto es una aplicación web para el Transporte Sustentable y Accesible para Estudiantes de la Ciudad (TSAEC).

## Características

- Diseño responsive
- Interfaz moderna con efectos de glassmorphism
- Visor de PDF integrado
- Sistema de comentarios
- Documentación interactiva

## Tecnologías Utilizadas

- HTML5
- CSS3
- JavaScript
- PDF.js
- Node.js

## Instalación

1. Clonar el repositorio:

```bash
git clone [URL_DEL_REPOSITORIO]
```

2. Instalar dependencias:

```bash
npm install
```

3. Iniciar el servidor de desarrollo:

```bash
npm run dev
```

## Estructura de Archivos

- `src/`: Contiene todo el código fuente del proyecto

  - `assets/`: Recursos estáticos (imágenes, fuentes, PDFs)
  - `styles/`: Archivos CSS organizados por componentes
  - `js/`: Archivos JavaScript y configuraciones
  - `pages/`: Páginas HTML del proyecto

- `public/`: Archivos públicos accesibles directamente
- `dist/`: Archivos compilados para producción
- `docs/`: Documentación del proyecto
- `tests/`: Pruebas unitarias y de integración

## Contribución

1. Fork el proyecto
2. Crear una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abrir un Pull Request

## Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

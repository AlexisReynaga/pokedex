# 🔴 Mini Pokédex

Una aplicación web interactiva que permite buscar información detallada sobre Pokémon utilizando la **PokéAPI**.

## 📋 Descripción

Mini Pokédex es una aplicación simple y elegante que demuestra el uso de APIs externas. Permite buscar cualquier Pokémon por nombre o ID y obtener información completa sobre él, incluyendo tipos, altura, peso y estadísticas base.

## ✨ Características

- 🔍 **Búsqueda por nombre o ID** - Encuentra Pokémon escribiendo su nombre o número Pokédex
- 🎨 **Interfaz moderna** - Diseño responsivo y atractivo con Tailwind CSS
- 📱 **Responsive** - Funciona perfectamente en dispositivos móviles y desktop
- ⚡ **Búsqueda en tiempo real** - Resultados instantáneos al buscar
- 📊 **Información detallada** - Muestra tipos, estadísticas, altura, peso y imagen oficial

## 🛠️ Tecnologías

- **HTML5** - Estructura semántica
- **CSS (Tailwind)** - Estilos modernos y responsive
- **JavaScript vanilla** - Lógica de la aplicación
- **[PokéAPI](https://pokeapi.co/)** - API de datos de Pokémon

## 🚀 Uso

1. Abre [index.html](index.html) en tu navegador
2. Escribe el nombre o ID de un Pokémon en el campo de búsqueda (ej: `pikachu` o `25`)
3. Presiona el botón "Buscar" o Enter
4. Visualiza la información del Pokémon encontrado

## 📖 Ejemplos de búsqueda

- `pikachu` - Búsqueda por nombre
- `25` - Búsqueda por ID (número Pokédex)
- `charizard` - Otro Pokémon por nombre
- `1` - Bulbasaur

## 🎯 Casos de uso

Este proyecto es ideal para:
- Aprender a trabajar con APIs externas
- Practicar JavaScript vanilla
- Entender fetch y promesas asincrónicas
- Diseño responsivo con Tailwind CSS
- Manejo de errores en solicitudes HTTP

## 📁 Estructura

```
Pokedex/
├── index.html       # Aplicación completa (HTML, CSS, JS)
├── README.md        # Este archivo
└── .git/            # Control de versiones
```

## 🔗 API Utilizada

[PokéAPI](https://pokeapi.co/) - API pública y gratuita que proporciona datos completos sobre Pokémon, incluyendo imágenes, estadísticas y más.

**Endpoint utilizado:**
```
https://pokeapi.co/api/v2/pokemon/{name-or-id}
```

## ⚙️ Funcionalidades técnicas

- **Búsqueda flexible** - Soporta búsquedas por nombre (cualquier caso) o número
- **Manejo de errores** - Valida resultados y muestra mensajes claros si no encuentra el Pokémon
- **Demo inicial** - Carga automáticamente datos de Pikachu al abrir la página
- **Menú móvil** - Hamburguesa funcional para navegación en dispositivos pequeños

## 👨‍💻 Autor

Creado por [Alexis Saúl López Reynaga](https://alexisreynaga.github.io/portafolio/)

## 📄 Licencia

© Todos los derechos reservados.

## 🤝 Contribuciones

Este es un proyecto educativo del portafolio. Las sugerencias y mejoras son bienvenidas.

---

**Nota:** Este proyecto requiere conexión a Internet para acceder a la API de PokéAPI.

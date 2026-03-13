# 🧵 Hilos Finos — Tienda React

Proyecto de práctica construido con **React + Vite** que simula una tienda artesanal de hilos finos. Incluye navegación con React Router, diseño inspirado en la estética Loisa (naranja / crema), y una página interactiva de estados con múltiples ejercicios de React.

---

## 🚀 Tecnologías

| Tecnología | Versión |
|---|---|
| React | ^19.2.0 |
| React Router DOM | ^7.13.1 |
| Vite | ^7.3.1 |
| Google Fonts | Playfair Display + DM Sans |

---

## 📁 Estructura del proyecto
```
rutas-react/
├── src/
│   ├── components/
│   │   ├── Navbar.jsx / Navbar.css      # Barra de navegación + anuncio
│   │   ├── Hero.jsx / Hero.css          # Sección hero de la tienda
│   │   ├── ProductCard.jsx / .css       # Tarjeta individual de producto
│   │   ├── ProductList.jsx / .css       # Grilla de productos destacados
│   │   ├── Footer.jsx / Footer.css      # Pie de página con links
│   │   ├── Card.jsx                     # Wrapper de card para ejercicios
│   │   ├── Contador.jsx                 # Ejercicio: contador avanzado
│   │   ├── Formulario.jsx               # Ejercicio: formulario con estados
│   │   └── ListaTareas.jsx              # Ejercicio: lista de tareas completa
│   ├── pages/
│   │   ├── Home.jsx / Home.css          # Página de inicio (presentación)
│   │   ├── Productos.jsx / .css         # Catálogo completo de hilos
│   │   ├── Contacto.jsx / .css          # Formulario de contacto
│   │   ├── Pagina.jsx                   # Tienda: Hero + productos + footer
│   │   ├── Estados.jsx                  # Página de ejercicios de useState
│   │   └── Ejercicios.css              # Estilos globales para ejercicios
│   ├── App.jsx                          # Router principal
│   ├── index.css                        # Variables globales y reset
│   └── main.jsx                         # Punto de entrada
├── index.html
├── vite.config.js
└── package.json
```

---

## ⚙️ Instalación y uso
```bash
# 1. Clonar o descomprimir el proyecto
cd rutas-react

# 2. Instalar dependencias
npm install

# 3. Iniciar servidor de desarrollo
npm run dev

# 4. Abrir en el navegador
# http://localhost:5173
```

### Otros comandos
```bash
npm run build    # Compilar para producción
npm run preview  # Vista previa del build
npm run lint     # Revisar errores de ESLint
```

---

## 🗺️ Rutas disponibles

| Ruta | Página | Descripción |
|---|---|---|
| `/` | Home | Presentación de la tienda y categorías |
| `/productos` | Productos | Catálogo completo con filtros por categoría |
| `/contacto` | Contacto | Formulario de contacto validado |
| `/pagina` | Tienda | Hero + productos destacados + footer |
| `/Estados` | Ejercicios | Práctica de `useState` en React |

---

## 🎨 Sistema de diseño

### Colores
```css
--orange:      #E8521A   /* Color principal */
--orange-dark: #c4420f   /* Hover / activo  */
--cream:       #F5F0E6   /* Fondo general   */
--ink:         #2C1A0E   /* Texto principal */
--brown:       #6B3A1F   /* Texto secundario */
--brown-light: #9B6240   /* Texto suave     */
```

### Tipografía
- **Playfair Display** — títulos, logo, números grandes
- **DM Sans** — cuerpo, botones, etiquetas

---

## 🧪 Ejercicios de useState (`/Estados`)

### 🔢 Contador
- Color dinámico: azul (par), morado (impar), naranja (>10), rojo (negativo)
- Mensaje dinámico según el valor: Bajo / Medio / Alto
- Límite máximo de 20, mínimo de 0
- Botones: Aumentar, +2, Disminuir, Aleatorio, Reset
- Alerta visual al llegar a 10 o al máximo
- Contador de clics totales en la sesión

### 📝 Formulario
- Dos inputs: nombre y correo
- Contador de caracteres en tiempo real (límite 50)
- Vista previa del contenido en vivo
- Botón deshabilitado si el input está vacío
- Mensaje de éxito temporal (3 segundos)

### ✅ Lista de Tareas
- Texto se convierte a mayúsculas al agregar
- Fecha y hora de creación en cada tarea
- Marcar como completada con checkbox (cambia color)
- Editar tarea inline con doble click en ✏️
- Eliminar tarea individual 🗑️
- Borrar todas las tareas / Marcar todas como completadas
- Filtros: Todas / Completadas / Pendientes
- Ordenar alfabéticamente A-Z
- Ocultar / mostrar lista
- Animación de entrada al agregar
- Indicador de carga (spinner 600ms)
- Contador: total, completadas, pendientes
- `document.title` cambia según tareas pendientes
- Componente `ItemTarea` separado

### 🌙 Modo oscuro / claro
- Botón en la parte superior alterna el tema completo de la página

---

## 📦 Productos del catálogo

El catálogo incluye 12 hilos organizados en 4 categorías:

- **Seda** — Seda Pura, Seda Salvaje, Mouliné 6 cabos
- **Lana** — Merino Superfino, Baby Alpaca, Mohair con Seda
- **Algodón** — Pima Peruano, Bambú Ecológico, Lino Fino
- **Metálico** — Dorado 24K, Plateado, Multicolor tornasolado

---

## 👤 Autor

**Johan Romero**
Aprendiz de Desarrollo Web — Ibagué, Colombia


---

> *"Si no sirve conectelo."*

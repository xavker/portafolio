# 🤖 Portafolio Leonardo Xavier Ramón Poma

**Portafolio de habilidades actualizado 2026** - Un sitio web interactivo y futurista que presenta la trayectoria profesional, formación académica y competencias técnicas.

---

## 📋 Descripción General

Este es un **portafolio profesional de una sola página (SPA)** construido con **HTML5 puro** e integrado con:

- **Tailwind CSS** - Framework de estilos moderno y responsive
- **Font Awesome** - Iconografía profesional
- **Google Fonts** - Tipografías personalizadas (JetBrains Mono, Orbitron, Plus Jakarta Sans)
- **Canvas API** - Fondo neural interactivo
- **Animaciones CSS3** - Efectos dinámicos y robóticos

### 🎯 Propósito

Mostrar de manera visual e interactiva el perfil de un **Magíster en Automatización Industrial** e **Ingeniero en Electrónica y Control** con más de 12 años de experiencia en EP Petroecuador.

---

## 🏗️ Estructura del Proyecto

```
portafolio/
├── index.html          # Archivo principal (218 KB)
├── foto.png            # Foto de perfil del usuario
└── README.md           # Este archivo
```

### 📦 Contenido del Archivo HTML

El archivo `index.html` es un documento monolítico que contiene:

1. **Metadatos y SEO** (líneas 3-15)
   - Título, descripción, palabras clave
   - Open Graph para compartir en redes sociales
   - Información del autor

2. **Importaciones Externas** (líneas 17-26)
   - Google Fonts: Tipografías especializadas
   - Tailwind CSS CDN: Framework de estilos
   - Font Awesome CDN: Iconos vectoriales

3. **Configuración Tailwind** (líneas 28-54)
   - Colores personalizados: Tema "cyberpunk" (cian, púrpura, esmeralda)
   - Familias de fuentes personalizadas
   - Modo oscuro habilitado

4. **Estilos CSS Personalizados** (líneas 56-193)
   - Efectos de brillo neón (`.neon-glow`, `.neon-box-glow`)
   - Grid ciber decorativo (`.cyber-grid`)
   - Vidrio esmerilado con desenfoque (`.cyber-glass`)
   - Animaciones 3D del brazo robótico
   - Escaneo láser holográfico
   - Estilos para impresión

---

## 🎨 Secciones Principales

### 1️⃣ **Encabezado (Header)** - Líneas 204-259

**Características:**
- Barra de navegación "sticky" (fija en pantalla)
- Logo con iniciales "LXR"
- Estado en vivo: "SISTEMA ACTIVO" con indicador pulsante
- Menú de navegación numerado (01-06)
- Botones de acción:
  - Imprimir CV (para impresión)
  - Conectar por WhatsApp
  - Menú móvil responsive

### 2️⃣ **Sección Hero** - Líneas 265-512

**Lado Izquierdo:**
- Presentación principal con gradiente cyan-purple
- Nombre y título profesional
- Descripción de especialización
- Tags con competencias principales
- Botones de CTA (Call To Action)

**Lado Derecho - 🤖 Brazo Robótico 3D:**
- **SVG Interactivo** del manipulador robótico K-6
- Articulaciones con cinemática inversa simulada
- Animaciones fluidas de 9 segundos
- Foto del usuario en "frame 3D" suspendido
- Escáner láser holográfico animado
- Efecto de vidrio especular
- Botones de control:
  - Pausar/Reanudar animación
  - Subir foto personalizada
  - Telemetría en tiempo real (X, Y, θ)

**Tarjeta de Datos:**
- Información técnica del titular
- Cargo actual, ubicación, años de trayectoria

### 3️⃣ **Sección KPI/Métricas** - Líneas 514-536

Cuatro tarjetas con estadísticas principales:
- **12+ años** de trayectoria
- **104** capacitaciones completadas
- **2** títulos de alto nivel
- **100%** cumplimiento operativo

### 4️⃣ **Perfil Profesional** - Líneas 539-594

- Descripción de especialista en automatización
- Terminal Linux simulada con comandos estilizados
- Hashtags de competencias
- Estado del sistema y permisos de seguridad

### 5️⃣ **Experiencia Laboral** - Líneas 596-683

Timeline vertical con **3 cargos**:
1. **Técnico Líder de Depósito** (En curso - 1 año 2 meses)
   - EP Petroecuador, Depósito La Toma
   
2. **Técnico Líder de Instrumentación y Control** (Principal - 11 años)
   - Sistemas DCS DeltaV, IBM Maximo, calibración
   
3. **Técnico Líder de Control** (2 meses 31 días)
   - Control automático de potencia

Cada tarjeta incluye:
- Indicador visual de estado (punto coloreado)
- Período de tiempo con icono de calendario
- Lista de responsabilidades principales

### 6️⃣ **Formación Académica** - Líneas 685-736

Tres cards informativas:
- 🎓 **Maestría**: Automatización Industrial (Cuarto Nivel)
- 🎓 **Ingeniería**: Electrónica, Automatización y Control (Tercer Nivel)
- 🌐 **Idiomas**: Suficiencia en Inglés (Certificado)

### 7️⃣ **Matriz de Competencias** - Líneas 739-807

Cuatro columnas especializadas:

| Columna | Competencias |
|---------|--------------|
| 🎚️ **Automatización & DCS** | DeltaV, PID, PLC, SCADA, Telemetría |
| 🏭 **Operaciones & Mantenimiento** | IBM Maximo, Depósitos, Pérdidas, Inspección |
| 🛡️ **HSE & Normativa** | ART, ISO 14001, ISO 45001, ISO 37001, Brigadas |
| 💻 **Tecnología & Innovación** | IoT, Arduino, Android Studio, AutoCAD, BD |

### 8️⃣ **Capacitaciones & Cursos** - Líneas 810-Fin

**Sistema interactivo con 104 cursos registrados:**

**Funcionalidades:**
- 🔍 **Búsqueda en tiempo real** - Filtra por palabra clave
- 🏷️ **Filtros por categoría**:
  - `all` - Todos los cursos
  - `control` - Automatización y control
  - `maximo` - IBM Maximo & EAM
  - `hse` - Seguridad y salud ocupacional
  - `tech` - Tecnología e innovación
  - `legal` - Normativa y gestión

**Estructura de cada tarjeta:**
```
REG #01 | [Categoría]
├─ Icono temático
├─ Número de registro
└─ Título del curso
```

**Categorías por Color:**
- 🔵 Normativa & Gestión (gris)
- 🟡 Seguridad / HSE (amarillo)
- 🔵 Automatización (cian)
- 🟢 IBM Maximo & EAM (esmeralda)
- 🟣 Tecnología & IT (púrpura)

---

## 🛠️ Tecnologías Utilizadas

### Frontend
| Tecnología | Versión | Propósito |
|------------|---------|----------|
| HTML5 | - | Estructura semántica |
| CSS3 | - | Estilos, animaciones, responsive |
| Tailwind CSS | v3 (CDN) | Framework de utilidades |
| JavaScript | ES6+ | Interactividad y DOM |
| Canvas API | Nativa | Fondo neural animado |

### Librerías Externas
| Recurso | Función |
|---------|---------|
| Google Fonts | Tipografías avanzadas |
| Font Awesome 6.5.1 | Iconografía |
| SVG Inline | Brazo robótico 3D |

### Colores Personalizados (Tema Cyberpunk)
```javascript
cyber: {
  bg: '#070b14',           // Fondo oscuro
  card: '#0d1527',         // Tarjetas
  border: '#1e293b',       // Bordes
  neon: '#00f2fe',         // Cian neón
  electric: '#4facfe',     // Azul eléctrico
  emerald: '#10b981',      // Esmeralda
  purple: '#8b5cf6',       // Púrpura
  accent: '#38bdf8'        // Acento azul
}
```

---

## 🎮 Características Interactivas

### 1. **Brazo Robótico Animado 3D**
- **Modelo SVG** con 5 articulaciones (base, J1, J2, J3, pinzas)
- **Cinemática** simulada con rotaciones 3D
- **Animación continua** de 9 segundos
- **Control manual**: Pausar/Reanudar con botón
- **Telemetría**: Muestra coordenadas X, Y, ángulo θ en tiempo real

```css
@keyframes robotArmKinematics {
  0% { transform: rotateX(6deg) rotateY(-4deg) translateY(0px); }
  /* ... 20%, 45%, 70%, 85% ... */
  100% { transform: rotateX(6deg) rotateY(-4deg) translateY(0px); }
}
```

### 2. **Foto de Perfil 3D**
- Frame mecánico con esquinas de sujeción
- Escaneo láser holográfico animado (mueve línea de arriba a abajo)
- Verificación biométrica con ROL y estado
- Carga personalizada de imagen
- Efecto de vidrio con brillo especular

### 3. **Búsqueda de Cursos**
```javascript
// Búsqueda dinámica
document.getElementById('course-search').addEventListener('input', (e) => {
  const query = e.target.value.toLowerCase();
  document.querySelectorAll('.course-card').forEach(card => {
    const text = card.textContent.toLowerCase();
    card.style.display = text.includes(query) ? 'flex' : 'none';
  });
});
```

### 4. **Filtrado por Categoría**
- Botones interactivos con estado activo
- Anima transiciones suave entre categorías
- Contador de elementos visible

### 5. **Efectos Visuales**
- **Neón brillante**: Texto con sombras de brillo
- **Vidrio esmerilado**: Tarjetas con desenfoque de fondo
- **Grid ciber**: Fondo con rejilla de líneas neón
- **Pulso de luz**: Elementos luminosos que palpitan
- **Hover effects**: Cambios de escala y color en interacción

### 6. **Canvas Neural**
```javascript
// Fondo interactivo con líneas aleatorias
const canvas = document.getElementById('neural-canvas');
const ctx = canvas.getContext('2d');
// Dibuja puntos y líneas conectadas en movimiento
```

### 7. **Impresión CSS**
- Estilos especiales para impresión
- Fondo blanco, texto negro
- Oculta elementos interactivos
- Expande grid de cursos para visualización completa

---

## 📱 Responsive Design

### Breakpoints Tailwind
- **Móvil**: Por defecto (< 640px)
- **sm**: 640px - Tablets pequeñas
- **md**: 768px - Tablets
- **lg**: 1024px - Laptops
- **xl**: 1280px - Pantallas amplias

### Características Responsive
- Navegación móvil colapsable
- Grid de competencias: 1 col → 2 cols → 4 cols
- Brazo robótico oculto en móviles pequeños
- Tamaños de fuente escalonados
- Espaciado adaptativo

---

## ♿ Accesibilidad

- Etiquetas semánticas HTML5 (`<header>`, `<main>`, `<section>`)
- Atributos `alt` en imágenes
- Contraste de colores WCAG AA+
- Navegación por teclado (enlaces, botones)
- Metaetiquetas OpenGraph para compartición
- `lang="es"` para idioma español

---

## 📊 Estadísticas del Código

| Métrica | Valor |
|---------|-------|
| Tamaño total | ~218 KB |
| Líneas de código | > 2000 |
| Secciones principales | 8 |
| Cursos documentados | 104 |
| Animaciones CSS | 6+ |
| Elementos SVG | 1 (brazo robótico) |
| Interacciones JS | 5+ |

---

## 🚀 Cómo Usar

### Visualización Local
1. Descarga o clona el repositorio
2. Abre `index.html` en un navegador moderno
3. Explora las secciones con scroll
4. Interactúa con el brazo robótico, busca cursos, filtra contenido

### Compartir
- **WhatsApp**: Botón "Conectar" en header
- **Imprimir**: Botón "Imprimir CV" (genera PDF)
- **Social Media**: Metaetiquetas OpenGraph automáticas

### Personalización
Para actualizar la foto de perfil:
1. Edita `foto.png` o sube una nueva imagen
2. Modifica la línea 440:
   ```html
   <img src="https://raw.githubusercontent.com/xavker/portafolio/main/foto.png" ... />
   ```

---

## 📝 Metadatos Principales

| Campo | Valor |
|-------|-------|
| **Autor** | Leonardo Xavier Ramón Poma |
| **Título** | M.Sc. Automatización & Control Industrial |
| **Empresa** | EP Petroecuador |
| **Ubicación** | Depósito La Toma, Catamayo, Loja, Ecuador |
| **Idioma** | Español (es) |
| **Año** | 2026 |

---

## 🔗 Enlaces Útiles

- **Email**: xavier.ramon@eppetroecuador.ec
- **WhatsApp**: +593 97 9724195
- **Ubicación**: Celica/Catamayo, Loja, Ecuador

---

## 📄 Licencia

Portafolio personal - Derechos reservados © 2026 Leonardo Xavier Ramón Poma

---

## 🎯 Últimas Actualizaciones

✅ **2026** - Portafolio completamente rediseñado con tema cyberpunk  
✅ Animaciones 3D del brazo robótico  
✅ Sistema de búsqueda y filtrado de cursos  
✅ 104 capacitaciones documentadas  
✅ Diseño completamente responsive  
✅ Optimizado para impresión  

---

**Portafolio de mis habilidades actualizado 2026** 🚀

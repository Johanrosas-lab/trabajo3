# 🧑‍💻 Hoja de Vida Web — Trabajo 3  
**Presentado a:** _Ing. Melendez Olivera Adriana_  
**Autor:** **Johan Rosas**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572b6?style=for-the-badge&logo=CSS3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=JavaScript&logoColor=F7DF1E)
![Responsive](https://img.shields.io/badge/Responsive-Yes-0ea5e9?style=for-the-badge)
![A11y](https://img.shields.io/badge/Accessibility-A11y-22c55e?style=for-the-badge)

> Proyecto de **hoja de vida** con enfoque **UX/UI**, **responsive**, animaciones limpias y buenas prácticas de HTML, **CSS (Flexbox/Grid)** y **JavaScript**.

---

## ✨ Características principales
- 🎯 **UX/UI**: jerarquía tipográfica clara (**Poppins + Inter**), alto contraste y espaciados cómodos.  
- 📱 **Responsive**: layout **Grid** (sidebar + contenido) → **1 columna** en pantallas pequeñas.  
- 🧩 **Componentes reutilizables**: tarjetas, chips de contacto, tags de habilidades.  
- 🧭 **Header flotante (sticky)** con blur y **sombra dinámica** al hacer scroll.  
- ✨ **Microinteracciones**: `:hover` en chips/tags y elevación sutil de tarjetas.  
- 🌀 **Animación de fondo** (loop) **“código cayendo”** con `canvas` tipo Matrix (fade-out de estelas).  
- 🎬 **Reveal on scroll**: aparición **fade/slide** por sección usando **IntersectionObserver**.  
- ♿ **Accesibilidad**: respeta `prefers-reduced-motion`, enlaces con `mailto:`, `tel:` y `target=_blank` con `rel="noopener"`.

---

## 🎨 Paleta de colores (inspiración _colorhunt_)
- Fondo oscuro: `#0b1220`  
- Panel/surface: `#0f172a`  
- Primario (azul): `#3b82f6`  
- Acento (cian): `#06b6d4`  
- Texto principal: `#e6edf6`  
- Texto secundario: `#9fb0c6`

> La paleta mantiene **consistencia visual**, buen contraste y funciona igual de bien en **modo oscuro**.

---

## 🛠️ Tecnologías y buenas prácticas
- **HTML5 semántico**: `header`, `main`, `aside`, `section`, `footer`.  
- **CSS3**:
  - **Grid/Flexbox** para layout responsive.
  - Variables CSS y sombras controladas.
  - Estados `:hover` y `:focus` suaves (microinteracciones).
- **JavaScript (ES6)**:
  - **Sticky header**: sombra al hacer scroll.
  - **IntersectionObserver**: agrega `.show` para el **fade/slide** progresivo.
  - **Canvas**: animación en loop tipo “código cayendo”.
- **Accesibilidad**:
  - Respeto de `prefers-reduced-motion`.
  - Enlaces de contacto útiles: `mailto:`, `tel:`, **WhatsApp** y **Maps**.

---

## 🧩 Animaciones (detalle)
- **Fondo “código cayendo”** (Canvas):
  - Lluvia de caracteres (mezcla alfanumérica y símbolos) con **estelas** que se desvanecen (fade-out).
  - **Loop infinito** mediante reinicio aleatorio de columnas.
  - Ajuste a **DPR** y **resize** para nitidez y rendimiento.
- **Fade/Slide Reveal**:
  - Clases `.reveal` + `.show` animadas con `@keyframes fadeUp`.
  - Activación con **IntersectionObserver** al entrar en el viewport.
- **Microinteracciones**:
  - Elevación y sombra en tarjetas (`transform/box-shadow`) y **chips** de contacto.
  - Transiciones cortas para sensación de **fluidez**.

---

## 📂 Estructura del proyecto
trabajo3/
├─ cv.html # Página principal (Hoja de Vida)
├─ cv.css # Estilos (paleta, layout Grid/Flex, animaciones)
└─ img/
└─ foto.jpg # Foto (puedes usar "Retrato acuático con luces de neón.png")
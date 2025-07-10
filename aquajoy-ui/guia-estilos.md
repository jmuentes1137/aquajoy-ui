# Guía de Estilos - Biblioteca UI Aquajoy

Esta guía describe las convenciones visuales y de codificación aplicadas a la biblioteca de componentes UI de Aquajoy.

---

## 🎨 Variables CSS

Se definen en `:root` para mantener coherencia y facilitar el mantenimiento:

```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --success-color: #28a745;
  --danger-color: #dc3545;
  --warning-color: #ffc107;
  --light-color: #f8f9fa;
  --dark-color: #343a40;

  --font-base: 'Poppins', sans-serif;
  --font-size-base: 16px;

  --spacing-sm: 8px;
  --spacing-md: 16px;
  --spacing-lg: 32px;

  --border-radius: 12px;
  --box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
}
```

---

## 🔠 Tipografía

- Fuente principal: **Poppins**, sans-serif
- Tamaño base: **16px**

---

## 🎨 Paleta de colores

| Nombre        | Código     |
|---------------|------------|
| Primario      | `#007bff`  |
| Secundario    | `#6c757d`  |
| Éxito         | `#28a745`  |
| Peligro       | `#dc3545`  |
| Advertencia   | `#ffc107`  |
| Claro         | `#f8f9fa`  |
| Oscuro        | `#343a40`  |

---

## 📐 Espaciados y Bordes

- Espaciado pequeño: `--spacing-sm` (8px)
- Espaciado medio: `--spacing-md` (16px)
- Espaciado grande: `--spacing-lg` (32px)
- Radio de borde: `--border-radius` (12px)
- Sombra base: `--box-shadow`

---

## 📏 Convención de Nombres BEM

Se utiliza la convención BEM para nombrar clases de componentes:

- `.btn` (Bloque)
- `.btn--primary`, `.btn--secondary` (Modificadores)
- `.modal__content` (Elemento del bloque)

---

## 📱 Media Queries

La biblioteca es responsive, usando esta regla base:

```css
@media (max-width: 768px) {
  /* Ajustes móviles */
}
```

---

## 🧩 Componentes Cubiertos

- Botones
- Tarjetas
- Formularios
- Navbar
- Modal
- Tooltip
- Alertas
- Tabs

Todos organizados bajo `/componentes/`.

---
# 💪 GymPlan PWA

> Plan de entrenamiento personal basado en la **Guía de los Movimientos de Musculación** de Frédéric Delavier (6ª Edición), empaquetado como Progressive Web App instalable en Android.

---

## 📱 Demo

Accedé a la app desde Chrome en Android y tocá **"Instalar app"** cuando aparezca el banner.

---

## 🎯 Objetivo

Aplicación personal de seguimiento de rutina de gym, diseñada para:

- 🔥 Quema de grasa
- 💪 Ganancia muscular
- ⚡ Desarrollo de fuerza
- 🫁 Resistencia cardiovascular

**Perfil:** 143 kg · 175 cm · Inicio: 4 Mayo 2026  
**Meta:** Perder 12 a 16 kg en 3 meses

---

## 📅 Estructura del Plan

| Día | Grupo Muscular | Ejercicios |
|-----|---------------|------------|
| Lunes | Pecho + Tríceps | 8 ejercicios |
| Martes | Espalda + Bíceps | 8 ejercicios |
| Miércoles | Piernas + Glúteos | 8 ejercicios |
| Jueves | Hombros + Trapecios | 8 ejercicios |
| Viernes | Abdominales + Core | 8 ejercicios + 15-20 min cardio |

---

## 🚀 Funcionalidades

- ✅ Navegación por día con tabs
- ✅ Marcar ejercicios como completados con un tap
- ✅ Barra de progreso por día
- ✅ Funciona **offline** (Service Worker)
- ✅ Instalable en Android como app nativa (PWA)
- ✅ Referencia de página del libro Delavier por ejercicio

---

## 🗂️ Estructura del Proyecto

```
gymplan/
├── index.html       # App principal (single file)
├── manifest.json    # Configuración PWA
├── sw.js            # Service Worker (cache offline)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

---

## ⚙️ Instalación en Android

1. Desplegá el repositorio en **GitHub Pages**:
    - Settings → Pages → Branch: `main` → Save
2. Abrí la URL `https://tu-usuario.github.io/gymplan` en **Chrome para Android**
3. Aparece el banner **"Instalar app"** → tocá instalar
4. Listo, aparece en tu pantalla de inicio 🎉

---

## 🛠️ Tecnologías

- HTML5 / CSS3 / JavaScript vanilla
- PWA (Web App Manifest + Service Worker)
- Google Fonts: Bebas Neue + Inter
- Sin frameworks, sin dependencias externas

---

## 📖 Fuente de los Ejercicios

Todos los ejercicios están referenciados con su número de página del libro:

> **Guía de los Movimientos de Musculación**  
> Frédéric Delavier — 6ª Edición  
> Editorial Paidotribo

---

## ⚠️ Disclaimer

Este plan es de carácter orientativo. Consultar con un médico o nutricionista ante cualquier duda sobre el entrenamiento o la alimentación.
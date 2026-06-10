# Sistema Automatizado SVA LAW

Plataforma web de cumplimiento PLD para SVA LAW. Hecha con Node.js, Express, EJS y Supabase.

---

## Requisitos

- [Node.js](https://nodejs.org) 18 o superior (incluye npm)

---

## Instalación

```bash
# 1. Entrar a la carpeta del proyecto
cd Prototipo_Funcional

# 2. Instalar dependencias
npm install
```

La conexión a la base de datos (Supabase) ya viene configurada en `config/supabase.js`, no requiere pasos extra.

---

## Arranque

```bash
# Modo normal
node index.js

# Modo desarrollo (se reinicia solo al guardar cambios)
npx nodemon index.js
```

Abre el navegador en **http://localhost:3000**

---

## Acceso de prueba

| Rol | Correo | Contraseña |
|-----|--------|------------|
| Oficial de Cumplimiento | oficial@sofom.mx | oficial123 |
| Analista | ana.torres@sofom.mx | analista123 |
| Cliente | carlos.h@email.com | cliente123 |

---

## Problemas comunes

- **`Cannot find module`** → falta correr `npm install`
- **Error de conexión a la base de datos** → revisa que tengas internet (Supabase es en la nube)
- **Puerto 3000 ocupado** → cierra el otro proceso o cambia `app.listen(3000, ...)` en `index.js`

---

Para conocer cómo usar el sistema, revisa [MANUAL_USUARIO.md](MANUAL_USUARIO.md).

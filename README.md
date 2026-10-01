# Battle Tracker: Pokémon Champions & PP Counter

![Version](https://img.shields.io/badge/Version-1.0.0-red.svg)
![Format](https://img.shields.io/badge/Format-Doubles%20%7C%20Singles-blue.svg)
![API](https://img.shields.io/badge/Data-Pok%C3%A9API-yellow.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

**Battle Tracker (BT)** es una herramienta web interactiva diseñada para ayudarte a rastrear y llevar el control en tiempo real del equipo rival durante tus combates competitivos en **Pokémon Champions**. Permite monitorear slots activos, movimientos, estados de objetos, habilidades y el conteo exacto de **PPs** adaptado al metagame.

---

## 📸 Características Principales

- **Ajuste Dinámico por Formato:**
  - **Formato Doubles:** 4 slots de Pokémon activos.
  - **Formato Singles:** 3 slots de Pokémon activos.
  - Cambio de formato instantáneo preservando la información del combate.

- **Gestión Precisa de PPs (Pokémon Champions):**
  - Sistema de PPs adaptado a los límites y balance de Pokémon Champions (ej. *Protect* con 10 PPs).
  - Botones intuitivos (`+1` / `-1`) para ajustar uso durante el combate y botón `PP Max`.
  - Indicador visual con barra de color dinámica según el porcentaje de PPs restantes.

- **Soporte Multilingüe:**
  - Selector de idioma en tiempo real: **English**, **Español (España)** y **Español (Latinoamérica)**.
  - Identidad visual unificada con nombre e insignia (*Battle Tracker BT - Pokémon Champions & PP Counter*) universales.

- **Información Flotante (Tooltips / Hover):**
  - Muestra detalles, categoría, efecto y precisión al pasar el cursor sobre **Movimientos**, **Habilidades** u **Objetos**.

- **Soporte para Formas y Variantes:**
  - Selector rápido para cambiar entre formas base, variantes regionales (*Alola*, *Galar*, *Hisui*, *Paldea*), *Megas* y *Gigamax*, actualizando tipos y sprites automáticamente.

- **Gestión de Objetos Equipados:**
  - Control interactivo del estado del objeto: **Activo**, **Desarmado** (*Knock Off / Trick*) o **Consumido** (*Bayas / Banda Focus*).

- **Persistencia de Datos:**
  - Sincronización automática con `localStorage` para no perder la información al recargar o cerrar la pestaña.

---

## 🛠️ Tecnologías Utilizadas

- **HTML5 & JavaScript (ES6+):** Lógica nativa sin dependencias pesadas.
- **Tailwind CSS:** Diseño moderno, responsivo y adaptado a tema oscuro (*Dark Mode*).
- **PokéAPI:** Fuente de datos oficial para estadísticas, imágenes, habilidades, tipos y descripciones.
- **FontAwesome:** Iconografía intuitiva.

---

## 🚀 Cómo Ejecutar Localmente

No se requiere ningún servidor backend ni instalación previa de Node.js:

1. Clona o descarga este repositorio en tu equipo.
2. Abre el archivo `index.html` en tu navegador preferido (Chrome, Firefox, Edge, Brave, Safari).
3. ¡Listo! Ya puedes empezar a trackear tus combates.

---

## 🌐 Despliegue en GitHub Pages

Puedes alojar esta app totalmente gratis usando GitHub Pages siguiendo estos pasos:

1. Ve a los **Settings** (Configuración) de este repositorio en GitHub.
2. Busca la sección **Pages** en el menú lateral izquierdo.
3. En la sección **Build and deployment > Branch**, selecciona la rama `main` (o `master`) y la carpeta `/ (root)`.
4. Haz clic en **Save**. En un par de minutos obtendrás tu enlace público `https://<tu-usuario>.github.io/<tu-repositorio>/`.

---

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - consulta el archivo [LICENSE](LICENSE) para más detalles.

*Pokémon y todos los nombres de personajes relacionados son marcas registradas de Nintendo, Game Freak y Creatures Inc. Este proyecto no está afiliado ni respaldado por Nintendo o The Pokémon Company.*
# ✔️ To-Do App con React

Esta aplicación es una lista de tareas (To-Do List) desarrollada con **React**, que permite agregar, marcar como completadas y eliminar tareas. Usa **IndexedDB** a través de la librería `idb` para almacenar los datos de forma local y persistente, y está estilizada con **Material UI**.

Es un código simple, que fue realizado como requisito para pasar una entrevista técnica en la [Consultoría Global](https://www.consultoriaglobal.com.ar/cgweb/).

---

## 🚀 Tecnologías utilizadas

- ⚛️ React
- 🔴 Material UI (MUI)
- 💾 IndexedDB (a través de `idb`)
- 🟩 JavaScript

## ⭐ Funcionalidades

- Agrega nuevas tareas.
- Marca tareas como completadas (con tachado visual).
- Contador de tareas pendientes.
- Elimina tareas completadas.
- Persistencia de datos en el navegador con IndexedDB (no se borran al recargar).

## 🧠 Estructura del código
- `useState` y `useEffect`: para manejar el estado de tareas y su carga inicial.
- `idb`: permite interactuar con IndexedDB y guardar las tareas de forma local.
- `Material UI`: permite crear estilos visuales (botones, campos, listas).

## 📦 Instalación

```bash
npm install
npm start
```

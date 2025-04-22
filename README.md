# 🛠️ Salesforce Utils

Una herramienta web diseñada para acelerar tareas comunes de desarrollo en Salesforce. Ideal para administradores, desarrolladores y consultores que trabajen con `package.xml`, `Permission Sets`, `Picklists` dependientes y más.

## 📦 Características actuales

### 🔁 Unificador de `package.xml`
Sube múltiples archivos `package.xml` y la herramienta:
- Agrupa todos los `<types>` y `<members>` sin duplicados.
- Genera un único archivo consolidado.
- Selecciona automáticamente la **versión más baja** entre todos los archivos.
- Permite descargar el resultado como un nuevo `package.xml`.

### 🧩 Generador de código para `PermissionSet`
Agrega a tu `PermissionSet` secciones para ApexClass, CustomField y RecordTypes de manera masiva

### 🔄 Asistente para Picklist Dependientes
Genera código para tu picklist dependiente de manera fácil y dinamica

## ⚙️ Tecnologías utilizadas
- HTML5
- JavaScript
- DOMParser para procesar XML en el navegador
- Blob API para descarga de archivos
- Lib Jexcel
- Bootstrap


## 🚀 Cómo usar

1. Clona el repositorio:

```bash
git clone https://github.com/tuusuario/salesforce-dev-toolbox.git

2. Abre index.html directamente en tu navegador.
No se necesitan servidores ni dependencias externas.
```
*Otra opción es ingresar directamente en [SFUtils](https://wachuleru.github.io/SFutils)

🧑‍💻 Autor
Desarrollado por Emilio Sepúlveda (wachuleru) – Salesforce Developer y entusiasta de la automatización.

📄 Licencia
MIT License. Libre para usar, modificar y compartir.

¡Que lo disfrutes y contribuya a tu productividad con Salesforce! 🚀

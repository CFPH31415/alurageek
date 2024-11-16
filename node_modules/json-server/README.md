# AluraGeek
![Descripción de la imagen](https://i.imgur.com/FGgbtl3.png) 

**AluraGeek** es una aplicación web que permite a los usuarios gestionar una lista de productos. Los usuarios pueden **visualizar**, **agregar** y **eliminar** productos utilizando tecnologías modernas de frontend y un servidor JSON simulado.

## 🔥 Funcionalidades

- **Visualizar** productos existentes.
- **Agregar** nuevos productos proporcionando nombre, precio e imagen.
- **Eliminar** productos de la lista.
- Manipulación dinámica del DOM para actualizar los productos sin recargar la página.
- Conexión con un servidor simulado utilizando **json-server** para realizar operaciones **CRUD**.

## 💻 Tecnologías Utilizadas

- **HTML5/CSS3**: Estructura y diseño.
- **JavaScript (ES6 Modules)**: Lógica e interacción.
- **json-server**: API RESTful simulada.
- **Fetch API**: Realización de solicitudes HTTP.
- **BEM (Block Element Modifier)**: Metodología para nombrar clases CSS.

## 🚀 Instalación

### Requisitos previos

- **Node.js** instalado.

### Pasos

1. Clona este repositorio:

   ```bash
   git clone https://github.com/CFPH31415/alurageek.git


2. Accede al directorio del proyecto:

   ```bash
   cd alurageek
   ```

3. Instala las dependencias:

   ```bash
   npm install
   ```

4. Inicia el servidor JSON:

   ```bash
   npm start
   ```

5. Abre index.html en tu navegador.

## 🗂️ Estructura del Proyecto

- **index.html**: Estructura de la aplicación.
- **styles/reset.css**: Reinicio de estilos.
- **styles/style.css**: Estilos personalizados.
- **js/controllers/main.js**: Lógica para agregar y eliminar productos.
- **js/services/product-services.js**: Solicitudes HTTP (GET, POST, DELETE).
- **db.json**: Base de datos simulada para json-server.**json-server**.
- **package.json**: Dependencias y scripts.

## 🛠️ API Simulada

**json-server** simula una API RESTful con las siguientes rutas:

- `GET /products`: Lista los productos.
- `POST /products`: Crea un nuevo producto.
- `DELETE /products/:id`:  Elimina un producto.

## 📋 Uso de la Aplicación

1. **Visualizar Produtos**: Los productos se cargan automáticamente desde el servidor simulado al abrir la página.
   
2. **Adicionar Produto**: Rellena el formulario con el nombre, precio y URL de la imagen y haz clic en **"Enviar"**.
   
3. **Remover Produto**: Haz clic en el ícono de la papelera para eliminar un producto.

---
Desarrollado por Carlos Portillo

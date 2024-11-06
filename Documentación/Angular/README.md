<h1 align="center"> DEFINICIONES </h1>
<p align="center"><img src="https://github.com/user-attachments/assets/6d11ff73-5454-478e-b095-396c226713d4"/></p>
Angular no es simplemente un framework frontend con el que se pueden construir SPA (Single Page Applications) Aplicaciones de Página Única, sino que también es una plataforma de desarrollo completa construida en TypeScript que incluye:

* Framework basado en componentes para construir aplicaciones web escalabales.
* Una colección de bibliotecas bien integradas que cubren una amplia variedad de características, incluyendo enrutamiento, gestión de formularios, comunicación cliente-servidor, aplicaciones web progresivas y más.
* Un conjunto de herramientas para desarrolladores, que ayudan a contruir, probar y actualizar código a través de **Angular CLI**.
-----------------------
<h3> Páginas generadas por el servidor</h3>

* La presentación y los datos de cada página son generadas por el servidor antes de entregarlos al cliente.
* Generalmenmte son stateful, que quiere decir que los datos se comparten durante la navegación de la página usando sesiones y cookies.
* La interfaz de usuario y lógica del negocio están acopladas.
* El cuerpo de respuesta generalmente es más pesado porque contiene tanto la interfaz de usuario como los datos.
* También son llamadas aplicaciones de múltiples páginas (MPA) Multiple Pages Applications, porque cada vista está representada por una página separada.
* Algunos ejemplos de frameworks y lenguajes de programación que desarrollan este tipo de páginas son: **PHP, Symphiny, JSP, Tapestry, ASP Razor pages**.
  
<p align="center"><img src="https://github.com/user-attachments/assets/4e4b2713-87ac-4860-8d58-aa885757c40b" width="400" height="250"/></p>
 
<h3> Páginas SPA + API</h3>

* La interfaz de usuario consiste en un único archivo HTML estático. El archivo se considera estático porque el servidor no modifica la página antes de entregarla.
* Los datos se obtienen dinámicamente desde el servidor cuando el cliente los necesita.
* El contenido de la página es alterado por el cliente a través de la manipulación del DOM (Document Object Model) el modelo de objeto de documento representa los elementos HTML de la página en el navegador, actualizando de manera dinámica sin recargar la página completa, permitiendo que la aplicación sea más rápida y eficiente.
* El cliente utiliza JavaScript para obtener datos dinámicos y manipular el DOM.
<p align="center"><img src="https://github.com/user-attachments/assets/0f46fdfe-ca3b-40d8-8090-000a7e371616" width="400" height="250"/></p>

---------------------
<h1 align="center">  INSTALAR NODE.JS Y ANGULAR </h1>

----------

<h2 align="center"> Instalar Node.js </h2>

Ir al link: https://nodejs.org/en/download/package-manager 

<p align="center"><img src="https://github.com/user-attachments/assets/548f3048-e861-4e1f-b7cd-7f05941ec1ba" width="500" height="250"/></p>

<br>

Node.js es un entorno de ejecución de **JavaScript**. En el desarrollo web se usa JavaScript para programar y es leído por los navegadores en tiempo de ejecución.

Una vez instalado verificar la versión en el **cmd**:

```bash
node --version
```

<p align="center"><img src="https://github.com/user-attachments/assets/3786af2e-c624-4f5c-b2ad-5cf7b9864227"/></p>

<br>

Al instalar Node.js viene incluido el **npm** __(Node package manager)__, el cual permite descargar distintas librerías, gestionar dependencias y otorga la herramienta de construcción de **Angular CLI**.

<h2 align="center"> Instalación de Angular </h2>

<p align="center"><img src="https://github.com/user-attachments/assets/4129a86a-8a5b-4cc2-9b5d-408979ce09ae" width="400" height="250"/></p>
<br>

**CLI** __(Command Line Interface)__ instala Angular para utilizarlo desde consola, copiar el comando y pegarlo en consola.

```bash
npm install -g @angular/cli
```

Al finalizar la instalación ya podemos utilizar la interfaz de línea de comando de Ángular en cualquier lugar del sistema. El **-g** permite instalar la librería de manera global.

Para verificar que esté bien instalado **Angular CLI**, colocamos este comando:

```bash
ng version 
```
<p align="center"><img src="https://github.com/user-attachments/assets/579bdcf6-09c3-4cb7-a4f2-138ca5eb008a" width="400" height="250"/></p>
<br>

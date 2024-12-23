<h1 align="center"> CREAR EL PROYECTO STOCKMaster</h1>
Para crear el proyecto se abre una consola y se ejecuta el siguiente comando:

```bash
ng new STOCKMasterProyecto
```
Allí se proceden a instalar todas las dependencias que se van a necesitar para trabajar con Angular.

<p align="center"><img src="https://github.com/user-attachments/assets/4a68634c-b664-4997-b061-e2b4e6203a3a" width="450" height="300"/></p>

Ahora se abre el proyecto en el editor de código, en este caso Visual Studio Code:

<p align="center"><img src="https://github.com/user-attachments/assets/e2a41b15-158e-41d9-8b9c-30e213c1046d" width="500" height="250"/></p>

Ahora, para inicializar el proyecto, abrimos una terminal y escribimos:

```bash
npm start
```
<p align="center"><img src="https://github.com/user-attachments/assets/87ada03a-864e-415a-ad35-00c5fbe8a8ea"/></p>

Se copia la dirección que nos provee dicho comando y la abrimos en un navegador:

<p align="center"><img src="https://github.com/user-attachments/assets/14ad2ad1-3c3b-467b-b990-d554373257df"/></p>

Y obtenemos la siguiente web:
<p align="center"><img src="https://github.com/user-attachments/assets/9384f37b-1e61-4484-9981-05353ddb3bcb" width="350" height="250"/></p>

---------------------
<h1 align="center"> Angular Material </h1>

Angular Material es una biblioteca de componentes de interfaz de usuario (UI) que se utiliza para crear aplicaciones de Angular con un diseño atractivo y consistente. 

Para instalar Angular Material en el proyecto se ingresa a este link: https://material.angular.io/guide/getting-started

<p align="center"><img src="https://github.com/user-attachments/assets/1052ae91-c7ae-4ba5-8d2c-26b25f1bdbc9" width="450" height="250"/></p>

Se copia el siguiente comando:

```bash
ng add @angular/material
```
Se coloca el comando en consola y se ejecuta:

<p align="center"><img src="https://github.com/user-attachments/assets/6227553e-0e34-4f16-9010-456d0a83236e"/></p>

------------------

<h1 align="center"> Bootstrap </h1>

Bootstrap es un framework que permite a los desarrolladores web construir páginas web responsives de una forma más rápida y sencilla. En este sentido, proporciona un conjunto de componentes y plantillas CSS, HTML y JavaScript que cualquiera puede utilizar o modificar de manera gratuita.

Colocar el siguiente comando en la ruta del proyecto:

```bash
npm install bootstrap-grid-only-css --save
```
<p align="center"><img src="https://github.com/user-attachments/assets/00d63e69-3a59-438c-864e-73122dd4b92f"/></p>

---------------------

<h1 align="center"> Creación componentes</h1>
Ahora se procede a la creación de la carpeta **components** y la carpeta **pages**:

```bash
mkdir components
```

```bash
mkdir pages
```

<p align="center"><img src="https://github.com/user-attachments/assets/e29f9f6f-be33-417d-9181-791c1f0d32a6"/></p>

Dentro de la carpeta **components** se creará el componente **navbar**.

```bash
ng g c navbar
```
<p align="center"><img src="https://github.com/user-attachments/assets/1f13fbe0-c64d-42ce-b114-2d495ab00826"/></p>

**ng** es la interfaz de línea de comandos de Angular (Angular CLI), cualquier comando de Angular comienza con **ng**, **g** es la abreviatura de **generate** (generar), **c** es la abreviatura de **component** (componente), y **navbar** es el nombre del componente que se está creando.
<p align="center"><img src="https://github.com/user-attachments/assets/7b494fc1-b5a4-403a-b0cf-a0844587907e"/></p>

Dentro de la carpeta **pages** se creará el componente **signup**:
```bash
ng g c signup
```
<p align="center"><img src="https://github.com/user-attachments/assets/bd982e45-8945-4dd6-a795-86f8b53d6eb4"/></p>

Dentro de la carpeta **pages** creamos otro componente llamado **login**:
```bash
ng g c login
```
<p align="center"><img src="https://github.com/user-attachments/assets/a368b190-2fe8-4462-aea4-af18215ab23d"/></p>

--------------------------------

<h1 align="center"> Formulario de Registro </h1>
Se comienza con el diseño del formulario de registro en HTML:

```bash
<div class = "bootstrap-wrapper">
    <div class= "container">
        <div class= "row" style ="margin-top: 20px;">
            <div class = "col-md-6 offset-md-3">
                <div class = "container text-center">
                    <img src = "../../../assets/login.png" width="100" height="100">
                </div>
                
                <h1 class = "text-center">REGISTRATE aquí</h1>
                <form action="">

                    <mat-form-field class = "full-width" appearance="outline">
                        <mat-label>Nombre de Usuario</mat-label>
                        <input matInput placeholder="Digite su Nombre de Usuario">
                    </mat-form-field>
                    
                    <mat-form-field class = "full-width" appearance="outline">
                        <mat-label>Contraseña</mat-label>
                        <input type= "password" matInput placeholder="Digite su contraseña">
                    </mat-form-field>

                    <mat-form-field class = "full-width" appearance="outline">
                        <mat-label>Nombre</mat-label>
                        <input matInput placeholder="Digite su Nombre">
                    </mat-form-field>

                    <mat-form-field class = "full-width" appearance="outline">
                        <mat-label>Apellido</mat-label>
                        <input matInput placeholder="Digite su Apellido">
                    </mat-form-field>

                    <mat-form-field class = "full-width" appearance="outline">
                        <mat-label>Email</mat-label>
                        <input type="email" matInput placeholder="Digite su Email">
                    </mat-form-field>

                    <mat-form-field class = "full-width" appearance="outline">
                        <mat-label>Teléfono</mat-label>
                        <input type="email" matInput placeholder="Digite su Teléfono">
                    </mat-form-field>

                    <div class = "container text-center">
                        <button mat mat-raised-button color="primary">Registrar</button>
                        <button style = "margin-left: 20px;"  mat mat-raised-button color="accent">Cancelar</button>
                    </div>

                </form>
                <br><br><br>
            </div>
        </div>
    </div>
</div>
```


<p align="center"><img src="https://github.com/user-attachments/assets/57e15459-5f46-49f0-89d3-a29d17a89210"/></p>







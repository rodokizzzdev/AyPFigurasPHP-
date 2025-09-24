# Figuras Geométricas - Área y Perímetro con PHP 📐

Este es un proyecto web sencillo que te permite calcular el área y el perímetro de figuras geométricas básicas: un cuadrado, un círculo y un triángulo.

---
### Tecnologías

* **HTML5**
* **CSS3**
* **PHP7**
* Imágenes **PNG**

---
### Características Principales

* **Pase de datos por URL (método GET)**: Desde la página principal (`index.html`), se pasa una variable a través de la URL para identificar la figura seleccionada por el usuario.
* **Formulario dinámico**: El archivo `operacion.php` recibe el dato del método GET y construye de manera dinámica el formulario con los campos de entrada (`<input>`) necesarios para realizar los cálculos.
* **Procesamiento de datos (método POST)**: Los datos capturados en el formulario son enviados y procesados con el método POST. Un campo oculto (`<input type="hidden">`) almacena el identificador de la figura para que la función de cálculo correcta sea llamada.
* **Cálculo y visualización**: Una función parametrizada se encarga de realizar los cálculos de área y perímetro, y los resultados se muestran directamente en la pantalla.

---
### Instalación

#### Opción A: Servidor Local (Recomendado)

Se requiere un servidor web local como **XAMPP** o **WAMPPserver** previamente instalado.

1.  Coloca la carpeta de este proyecto en el directorio de salida de tu servidor:
    * **XAMPP**: `c:/xampp/htdocs`
    * **WAMPPserver**: `c:/wamp64/www`

#### Opción B: Servidor de Hosting

1.  Asegúrate de que tu servidor de hosting soporte **PHP7** o superior.
2.  Utiliza un cliente FTP o el panel de control (CPANEL) para subir la carpeta del proyecto al directorio público de tu servidor, que suele llamarse `public_html`, `www`, o `public`.

---
### Uso

#### Opción A: Local

1.  Inicia el servicio de tu servidor web (XAMPP o WAMPPserver).
2.  Abre tu navegador y navega a la siguiente dirección, reemplazando `NombreDeLaCarpetaDelProyecto` con el nombre de tu carpeta:
    ```
    http://localhost/NombreDeLaCarpetaDelProyecto
    ```
    * **Nota**: Si tu servidor utiliza un puerto diferente al 80, deberás especificarlo en la dirección (ej. `http://localhost:8080/NombreDeLaCarpetaDelProyecto`).

#### Opción B: Hosting

1.  Abre tu navegador y accede a la dirección de dominio donde implementaste el proyecto. Por ejemplo:
    ```
    [https://www.miDominio.com/figurasGeometricas](https://www.miDominio.com/figurasGeometricas)
    ```

---
### Contribuciones

¡Las contribuciones son bienvenidas! Si deseas ayudar a mejorar este proyecto, por favor sigue los siguientes pasos:

1.  **Haz un *fork* del repositorio:** Crea una copia del repositorio en tu cuenta de GitHub.
2.  **Clona el repositorio:** Clona tu *fork* a tu máquina local.
    ```bash
    git clone [https://github.com/rodokizzzdev/AyPFigurasPHP.git](https://github.com/rodokizzzdev/AyPFigurasPHP.git)
    ```
3.  **Crea una nueva rama:** Trabaja en una rama separada para tus cambios.
    ```bash
    git checkout -b nombre-de-tu-rama
    ```
4.  **Haz tus cambios y *commit***: Realiza las modificaciones y describe claramente tus cambios.
    ```bash
    git add .
    git commit -m "Descripción clara de tus cambios"
    ```
5.  **Envía los cambios a tu repositorio:** Sube tus cambios a tu *fork* en GitHub.
    ```bash
    git push origin nombre-de-tu-rama
    ```
6.  **Abre un *pull request***: Desde tu repositorio en GitHub, abre un *pull request* hacia la rama `main` del repositorio original. Explica tus cambios y por qué crees que deberían ser integrados.

Una vez que envíes tu *pull request*, lo revisaré lo antes posible. ¡Gracias por tu interés en mejorar este proyecto!

---
### Licencia

Este proyecto está bajo la Licencia **MIT**. Para más detalles, consulta el archivo `LICENSE` en este repositorio.

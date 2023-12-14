![Adalab](https://beta.adalab.es/resources/images/adalab-logo-155x61-bg-white.png)

# Evaluación final módulo 1: We Love Run

Este proyecto es la maquetación de una página de deporte a la que he llamado **We Love Run** aparentemente sencilla en la que se muestran las diferentes ofertas tanto de un plan de entrenamiento como una pequeña introducción que debería llevar a una tienda. En este proyecto los botones *"comprar"* y *"Empezar ahora"* no tienen ninguna función. El resto de enlaces que aparecen en la página, tanto el menú como los enlaces del footer todos redirigen a la página de [Adalab](https://adalab.es/).

### Herramientas utilizadas 🛠️

Para realizar este proyecto se ha trabajado con **SASS**, para el diseño de la página se ha utilizado en ocasiones **flexbox** y **grid** que ha servido para poder adaptar la página a los diferentes formatos de dispositivos en los que se pueda visualizar. 
> **NOTA:** Las medidas utilizadas para diferenciar los dispositivos son 320px para móvil, 768px para tablet y 1200px para desktop.

También se ha utilizado el [Adalab Web Starter Kit](https://github.com/Adalab/adalab-web-starter-kit) que nos ha ofrecido todos los ficheros y carpetas necesarios para realizar el proyecto. Esta plantilla usa **Vite** para la ejecución de tareas.

### Pasos a seguir si queremos arrancar el proyecto desde nuestro VSC ⚙️

1. Descarga el proyecto. 
   - No recomendamos que clones este repo ya que no podrás añadir commits.
1. **Abre una terminal** en la carpeta raíz donde le hayas guardado.
1. **Instala las dependencias** locales ejecutando en la terminal el comando:

```bash
npm install
```
> **NOTA:** Esto generará una carpeta llamada node_modules y sólo hay que ejecutarlo una vez. En el momento que aparezca la carpeta ya no será necesario volver a ejecutarlo. 

1. Una vez hemos instalado las dependencias, vamos a arrancar el proyecto. **El proyecto hay que arrancarlo cada vez que te pongas a programar.** Para ello ejecuta el comando:

```bash
npm run dev
```

Este comando:

- **Abre una ventana del navegador y muestra la página web**, al igual que hace el plugin de VS Code Live Server (Go live).
- También **observa** todos los ficheros que hay dentro de la carpeta `src/`, para que cada vez que modifiques un fichero **refresca tu página en Chrome**.
- También **procesa los ficheros** HTML, SASS / CSS y JS. Por ejemplo:
   - Convierte los ficheros SASS en CSS.
   - Combina los diferentes ficheros de HTML y los agrupa en uno o varios ficheros HTML.

Después de ejecutar `npm run dev` ya puedes empezar a editar todos los ficheros que están dentro de la carpeta `src/` y programar cómodamente.


## Estructura de carpetas

La estructura de carpetas donde está la inormación tiene esta pinta:

```
public
 └─ images //contiene todas las imágenes utilizas en el proyecto//

src
 ├─ scss
 |  ├─ core
 |  ├─ layout
 └─ partials
    └─ //archivos html de las diferentes partes del proyecto//
```

> **NOTA:** Los partials de HTML y SASS del proyecto son orientativos. Te recomendamos usar los que quieras, y borrar los que no uses.

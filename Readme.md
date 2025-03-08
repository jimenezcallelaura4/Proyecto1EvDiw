# Memoria del Proyecto 2ª Evaluacion 

`Curso:` Diseño Aplicaciones Web 
`Asignatura:` Diseño de Interfaces Web

## Introduccion
Este proyecto consiste en el diseño y desarrollo de un siito web para una agencia de viajes, donde se pueden explorar destinos, experiencias, contactar con la empresa y leer un blog con consejos e información de viajes.
El objetivo principal es ofrecer una interfaz atractiva y funcional, además de poer en práctica los conocimientos de HTML, CSS, Bootstrap y la implementación de un tema claro/oscuro.

## Metodología
Para la organización y el desarrollo del proyecto, se ha optado por:
- **Planificación** con un análisis inicial de requisitos, esctructura de archivos y secciones del sitio.
- **Uso de HTMAL semántico** para la mejora de la accesibilidad y la organización del contenido.
- **Maquetación y estilos** con una combinación de:
   - **Bootstrap** para componentes y utilidades.
   - **CSS Grid y Flexbox** para el posicionamiento y la disposición responsiva.
   - **SCSS(Sass)** para una estructura modular y la posibilidad de definir variables y anidado de reglas.
   - **Metodología BEM** para nombrra las clases y mantener un estilo escalable y mantenible.

## Justificación de las Soluciones Adoptadas
- **HTML semántico**: Facilita la lectura del código, la accesibilidad y el posicionamiento en buscadores
- **Bootstrap**: Acelera el desarrollo con estilos y componentes predefinidos, a la vez que se puede sobrescribir para adaptarlo a nuestro diseño.
- **Flexbox y CSS Grid**: permiten un diseño responsivo, moderno y más simple que las técnicas tradicionales de posicionamiento.
- **SCSS**: Hace más eficiente la gestión de estilos, permitiendo variables, mixins, anidado y archivos parciales
- **Metodología BEM**: Aporta un sistema claro para nombrar clases y separar bloques, elemento y modificacdores, evitando conflictos y mejorando la escalabilidad.
- **Tema Claro/Oscuro**: Ofrece una experiencia personalizada al usuario permitiendo distintas condiciones de luz.

## Guía de Estilos

### Tipografía
- Se utiliza la fuente Poppins(Google Fonts) con diferentes medidas (400 y 600) 
- El tamaño de fuente base es `16px`

### Colores
- **Tema Claro:** 
  - **Fondo principal:** `#ffffff`
  - **Texto principal:** `#333333`
  - **Navbar:** `linear-gradient(90deg, #3D3936, #9E6944)`
  - **Botones:** `#007bff`(hover:`#0056b3)`
  
- **Tema Oscro:**
  - **Fondo principal:** `#333333`
  - **Texto principal:** `#f1f1f1`
  - **Navbar:** `linear-gradient(90deg, #000000, #222222)`
  - **Botones:** `#0056b3`(hover:`#003366)`

### Disposición del Contenido
- **CSS Grid**: Se utiliza en las secciones de destinos para mostrar las tarjetas en filas responsivas.
- **Flexbox**: Se emplea en la sección de beneficios y en la lista de iconos de contracto para alinear elementos de manera flexible y responsiva.

### Metodología BEM
- **Block** se utiliza para los contenedores principales, `.card`, `.navbar`, `.beneficios`.
- **Element** se representa con `__`, `.card__title`, `.card__body`.
- **Modifier** se representa con `--`, `btn--primary`, en este caso no se usa porque se usa bootstrap para los botones.

## Estadísticas de Uso
- **Tamaño de pantallas**:
  - 50%: Pantallas de escritorio (1366x768 o mayores).
  - 40%: Dispositivos móviles.
  - 10%: Tablets.


- **Sistemas operativos**:
  - 55%: Windows.
  - 30%: Android.
  - 10%: iOS.
  - 5%: Otros.


- **Países consumidores**:
  - 40%: España.
  - 25%: México.
  - 15%: EEUU.
  - 20%: Otros.


## Requerimientos del Cliente
- **Logo**: Proporcionado por el cliente.
- ![Imagen logo](img/logo2.png) 
- **Colores y tipografías**: Aprobados por el cliente tras una revisión inicial.



### Instalaciones
1. **Visual Studio Code (VSC)**:
   - Extensiones:
     - `Live Server`: Para visualizar cambios en tiempo real.

2. **GitHub**:
   - Creación de Respoitorio 
     - `git init`: Inicializar repositorio.
     - `git add .`: Añadir cambios al área de preparación.
     - `git commit -m "mensaje"`: Confirmar cambios.
     - `git push`: Subir cambios al repositorio remoto.
     - https://github.com/jimenezcallelaura4/Proyecto1EvDiw


### Frameworks y Librerías
- **Bootstrap**: Para estilos y componentes responsivos.
- **Google Fonts**: Para tipografías personalizadas.


## Consideraciones
### Colores
- Las combinaciones se eligieron teniendo en cuenta:
  - Contraste suficiente para mejorar la legibilidad.
  - Asociación emocional con viajes y aventura.

### Tipografías
- Uso de fuentes que llamen la ateción por su claridad.


## Conclusión
Este proyecto demuestra cómo una correcta planificación, diseño y el uso de herramientas puede dar lugar a una página web funcional y atractiva. La implementación de secciones específicas como "Experiencias" y "Blog de Viajes" añade valor al usuario final, promoviendo el interés y la interacción.
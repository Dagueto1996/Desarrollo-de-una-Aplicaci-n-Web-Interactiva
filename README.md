# DataFlow Planner - Tarea 3 Momento 7

## 1. Nombre de la aplicación
**DataFlow Planner: Gestión Ágil de Proyectos de Datos**

## 2. Tema elegido
La aplicación está relacionada con Ingeniería Informática, Ciencia de Datos e Inteligencia Artificial. Su propósito es permitir la organización básica de tareas dentro de un proyecto de datos, simulando un tablero ágil donde se registran actividades, responsables, prioridades, estados y avance general.

## 3. Objetivo general
Desarrollar una aplicación web interactiva usando HTML, CSS y JavaScript que permita gestionar tareas de un proyecto académico o profesional de datos, aplicando principios de usabilidad, dinamismo e interactividad.

## 4. Funcionalidades principales
- Registrar nuevas tareas mediante un formulario interactivo.
- Asignar responsable, prioridad y estado a cada tarea.
- Visualizar tareas en tarjetas dinámicas.
- Filtrar tareas por estado: Todas, Pendiente, En proceso y Finalizada.
- Eliminar tareas registradas.
- Cargar datos de ejemplo.
- Calcular automáticamente indicadores del proyecto.
- Mostrar barra de avance general.
- Guardar información en el navegador usando LocalStorage.
- Diseño responsive para computador y celular.

## 5. Estructura de páginas y archivos
```text
tarea3-momento7-dataflow/
├── index.html
├── README.md
└── public/
    ├── styles.css
    └── script.js
```

## 6. Diseño inicial de la aplicación
La aplicación se divide en las siguientes secciones:

1. **Encabezado principal:** Presenta el nombre de la aplicación, objetivo y botón para ingresar al tablero.
2. **Sección informativa:** Explica objetivo, interactividad y área académica relacionada.
3. **Dashboard de métricas:** Muestra total de tareas, pendientes, en proceso y finalizadas.
4. **Formulario:** Permite registrar nuevas tareas.
5. **Panel de tareas:** Lista las tareas creadas y permite filtrarlas o eliminarlas.
6. **Avance general:** Muestra una barra de progreso calculada automáticamente.

## 7. Plan de trabajo
| Fase | Actividad | Resultado esperado |
|---|---|---|
| 1 | Elección del tema | Tema definido: gestión ágil de proyectos de datos |
| 2 | Diseño inicial | Estructura visual y funcionalidades planeadas |
| 3 | Desarrollo HTML | Maquetación de secciones principales |
| 4 | Desarrollo CSS | Estilos visuales, tarjetas, responsive y animaciones |
| 5 | Desarrollo JavaScript | Formulario, filtros, métricas, eliminación y LocalStorage |
| 6 | Pruebas | Validación de creación, filtrado, eliminación y persistencia |
| 7 | Optimización | Código organizado y carga rápida sin librerías externas |
| 8 | Publicación | Subida del proyecto a GitHub o entrega en ZIP |

## 8. Tecnologías utilizadas
- HTML5
- CSS3
- JavaScript
- LocalStorage del navegador
- GitHub para publicación

## 9. Pruebas realizadas
| Prueba | Resultado |
|---|---|
| Registrar tarea con datos completos | Correcto |
| Validar campos requeridos | Correcto |
| Filtrar tareas por estado | Correcto |
| Eliminar una tarea | Correcto |
| Cargar datos de ejemplo | Correcto |
| Actualizar indicadores automáticamente | Correcto |
| Guardar datos al recargar la página | Correcto |
| Visualizar en pantalla pequeña | Correcto |

## 10. Optimización
La aplicación no utiliza librerías externas, por lo tanto carga rápidamente. Los archivos están separados por responsabilidad: HTML para estructura, CSS para diseño y JavaScript para comportamiento. Además, se usa LocalStorage para evitar depender de una base de datos externa.

## 11. Cómo ejecutar la aplicación
1. Descargar o clonar el repositorio.
2. Abrir el archivo `index.html` en un navegador web.
3. Interactuar con el formulario, filtros y tablero.

## 12. Cómo publicar en GitHub
1. Crear un repositorio nuevo en GitHub.
2. Subir los archivos del proyecto.
3. Activar GitHub Pages desde Settings > Pages.
4. Seleccionar la rama principal y la carpeta raíz.
5. Copiar el enlace generado por GitHub Pages como entregable.

## 13. Conclusión
DataFlow Planner demuestra el uso de HTML, CSS y JavaScript para crear una aplicación web interactiva, visualmente atractiva y funcional. La propuesta está conectada con el área de Ingeniería Informática y Ciencia de Datos, ya que permite planificar y controlar tareas de un proyecto tecnológico usando métricas, estados y seguimiento de avance.

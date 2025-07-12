<p align="center">
  <img src="CARATULA%20DJANGO.png" alt="Carátula del Proyecto" width="1000"/>
</p>

⚠️Proyecto en creación aún no es la versión final ⚠️
# CRUD_Django_MaribelGutierrezRamirez


**1. ¿Qué es un CRUD y cuál es su propósito en el desarrollo de aplicaciones web?**


✍️ Añade un ejemplo de aplicación web que use una estructura de CRUD


CRUD es un acrónimo que representa las cuatro operaciones fundamentales para el manejo de bases de datos:
- Create (Crear registros)
- Read / Retrieve (Leer registros)
- Update (Actualizar registros)
- Delete / Destroy (Borrar registros)
Su función es permitir al desarrollador manipular los datos de acuerdo con las necesidades específicas del producto que está construyendo.
Gracias a este trabajo, los usuarios pueden interactuar con los datos de forma ordenada, estructurada y segura, a través de interfaces diseñadas para facilitar estas operaciones.

**Ejemplo de CRUD:
Notion:**

Imaginemos que estoy creando una base de datos de mis proyectos en curso:
- Create: Añado un nuevo proyecto con nombre, fecha y estado.
- Read: Abro la base para ver todos los proyectos y su progreso.
- Update: Cambio el estado de un proyecto de "En progreso" a "Completado".
- Delete: Elimino un proyecto cancelado.

---

**2 . ¿Qué son los patrones de arquitectura en desarrollo de software?**

Los patrones de arquitectura son soluciones reutilizables y probadas para problemas comunes que aparecen al diseñar la estructura de una aplicación. No son fragmentos de código que se copian y pegan, sino plantillas conceptuales que guían cómo organizar los componentes principales de un sistema de software.

Estos patrones ayudan a los desarrolladores a:

- Separar responsabilidades dentro de la aplicación.
- Facilitar el mantenimiento y escalabilidad del proyecto.
- Mejorar la comprensión del código para nuevos integrantes del equipo.
- Promover buenas prácticas de diseño.

  Un patrón de arquitectura define cómo se comunican las partes de una aplicación: bases de datos, interfaces de usuario, lógica de negocio, controladores, etc. Sirve como un modelo mental que los equipos pueden adaptar a sus necesidades.

📌***En resumen, los patrones de arquitectura son como mapas de organización que ayudan a construir software de manera ordenada, clara y eficiente.***

  
---

**¿Qué es el patrón MVC (Modelo–Vista–Controlador)?**
 - ¿Qué es el patrón MVT (Modelo–Vista–Template)?

El patrón de arquitectura de software MVC (Modelo–Vista–Controlador) separa la lógica de la aplicación en tres componentes principales:

**M**odelo: Gestiona la lógica de los datos y representa la estructura de la información.

**V**ista: Se encarga de la presentación, generando la interfaz en HTML que verá el usuario.

**C**ontrolador: Procesa la solicitud del usuario (request), interactúa con el modelo para obtener o modificar datos, y luego llama a la vista, pasándole la información necesaria para ser mostrada.


 - **Diferencias entre MVC y MVT.**
   
**MVC** (Modelo-Vista-Controlador) y **MVT** (Modelo-Vista-Template) son dos formas de organizar el código cuando desarrollo una aplicación. Ambos patrones dividen la aplicación en tres partes para que sea más fácil de entender y trabajar. La diferencia principal está en quién se encarga de la parte que controla cómo se conectan los datos con lo que el usuario ve.
Cuando usamos MVC, tenemos que escribir todo el código que indica cómo se toman los datos y se muestran en la pantalla. Es decir, tener el rol de del "controlador", que conecta el modelo, los datos, con la vista.
En cambio, si usamos MVT, el framework ya hace ese trabajo. Django se encarga automáticamente de esa parte del proceso, así que ya no necesitamos escribir tanto código.

 - **¿Cuál de estos dos patrones se usa en Django?**
   
   Django utiliza el patrón MVT (Modelo-Vista-Template).
___

**3. ¿Cómo se estructura un proyecto en Django? Explicar brevemente el rol de los modelos, vistas, templates y URLs.**

Un proyecto de Django se organiza en apps (aplicaciones), cada una con una función específica. Dentro de cada app hay cuatro componentes clave:
Componentes principales:
- 1. Modelos (models.py): Definen la estructura de la base de datos. Cada modelo es una tabla con campos como CharField, DateField, etc.
- 2. Vistas (views.py): Contienen la lógica que se ejecuta cuando un usuario hace una solicitud. Se conectan con los modelos y envían datos a los templates.
- 3. Templates (carpeta templates/): Archivos HTML con marcadores especiales que permiten insertar datos dinámicos.
- 4. URLs (urls.py): Definen las rutas de la aplicación y qué vista debe ejecutarse para cada URL.
___
     
- **¿Para qué se usa el signo “%%” en los templates?**
El signo {% ... %} se usa en Django Templates para ejecutar sentencias de control, como estructuras de flujo (condicionales, bucles) o instrucciones del lenguaje de plantillas.
  ___
4. ¿Cuál es el flujo de datos entre un formulario HTML y la base de datos en Django?
   ___
6. ¿Qué herramientas o comandos ofrece Django para facilitar el desarrollo de un CRUD, para qué es cada una? (Por ejemplo: startapp, makemigrations, migrate, runserver, ModelForm, admin, etc.)
   ___
8. ¿Cómo funciona el Admin de Django? 




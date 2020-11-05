
[![](https://secure.webtoolhub.com/static/resources/icons/set56/ed85b9d.png)]({{site.data.cv.enlace_campusULL}})


## Información del contacto
* **Nombre y Apellidos:** {{site.data.cv.nombre}} {{site.data.cv.apellidos}}
* **Fecha de Nacimiento:** {{site.data.cv.fecha_de_nacimiento}}
* **Profesión:** {{site.data.cv.titulo}}
* **Formación adicional:** {{site.data.cv.formacion_adicional}}
* **Enlace Campus Virtual ULL:** :point_right: [Click me!]({{site.data.cv.enlace_campusULL}})
* **Cita favorita:** 
  > {{site.data.cv.cita_favorita}}
* **Cursos recibidos:**
  {% for curso in site.data.cv.cursos_recibidos %}
  * {{curso}}
  {% endfor %}
* **Código de ejemplo:**
   ```javascript
   function HolaMundo(){
       alert( '¡Hola, Mundo!' );
   }
   ```
* **Experiencia en el máster** :blue_book: [Click me!](./master.md)
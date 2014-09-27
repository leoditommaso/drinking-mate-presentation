!SLIDE center
# Content Delivery Networks (CDN) #
## Caso de análisis: La Bioguía ##


!SLIDE smbullets transition=uncover
# Temas
* ¿Qué es La Bioguía?
* Problemática inicial.
* Optimización del servicio.
* Implementación de la CDN.
* Problemática actual.
* Conclusiones.


!SLIDE smbullets transition=uncover
# ¿Qué es La Bioguía? #
"[La Bioguía](http://www.labioguia.com) es el portal y la comunidad digital más grande de habla hispana de
la nueva cultura sustentable."

![La Bioguía](bioguia-face.png)


!SLIDE smbullets transition=uncover
# Problemática inicial

* El máximo de visitantes simultáneos del sitio no superaba los 60.
* Se necesitaba soportar 4.000 visitantes simultáneos.
* Página de Facebook con más de 1.000.000 de me gusta.
* Picos importantes en períodos breves de tiempo (al publicar un enlace en
  Facebook).


!SLIDE smbullets transition=uncover
# Optimización del servicio

* Contratar un servidor más grande (16GB RAM, 6 núcleos).
* Adquirir ancho de banda adicional (35Mbps de subida).
* Realizar ajustes a la página para disminuir su tamaño.
* Instalar Nginx, PHP-FPM, Varnish y optimizar varios parámetros de la BBDD y
  del sistema operativo.


!SLIDE smbullets transition=uncover
# Un cliente feliz

Con todo el trabajo realizado se logran alcanzar los 4.000 visitantes
simultáneos, pero el techo cambió.

* Se satura el ancho de banda al tiempo que la memoria y la capacidad de cómputo
  del servidor se desperdician.


!SLIDE center
# ¿Preguntas? #


# Creación de la infraestructura cliente-servidor

Uno de los problemas que se tuvieron a lo largo del desarrollo de la solución es que para hacer la inferencia en las GAN era necesario utilizar Python, mientras que el simulador está implementado en C#, lenguaje de programación utilizado por Unity. Para solucionar el problema de hacer la inferencia en tiempo real y mostrar las imágenes mientras se conduce, se optó por hacer un servidor en Python que se encargara de las inferencias. Este servidor sería utilizado por Unity, el cual actuaría como cliente.

Se hicieron varias versiones de esta infraestructura hasta conseguir una que permitía obtener las imágenes de manera fluida

## Primera versión de la infraestructura cliente-servidor

<a href="https://youtu.be/LGSpM6oxXFw" title="Primera versión de la infraestructura cliente-servidor"><img src="../Imagenes/Video-Version1Server.PNG" alt="Primera versión de la infraestructura cliente-servidor" width="500"/></a>

**Enlace del vídeo:** https://youtu.be/LGSpM6oxXFw

## Versión final de la infraestructura cliente-servidor

<a href="https://youtu.be/9qm00Rm1gy0" title="Versión final de la infraestructura cliente-servidor"><img src="../Imagenes/Video-Version2Server.PNG" alt="Versión final de la infraestructura cliente-servidor" width="500"/></a>

**Enlace del vídeo:** https://youtu.be/9qm00Rm1gy0

## Comparación entre las dos versiones anteriores

<a href="https://youtu.be/uWq46nQ-_xQ" title="Comparación entre las dos versiones de la infraestructura cliente-servidor"><img src="../Imagenes/Video-ComparacionServer.PNG" alt="Comparación entre las dos versiones de la infraestructura cliente-servidor" width="500"/></a>

**Enlace del vídeo:** https://youtu.be/uWq46nQ-_xQ

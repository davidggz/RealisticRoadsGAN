# Síntesis de imágenes realistas

La síntesis de imágenes realistas ha sido una de las claves en las que se ha centrado el trabajo. Para encontrar el **data set** que diera los mejores resultados, se ha hecho una gran experimentación en la que se han visitado varias arquitecturas que componen el estado del arte en la síntesis de imágenes realistas. A continuación se muestran algunos de los resultados obtenidos con distintos modelos, desde los más arcaicos a los más modernos.


## Modelo de Pix2Pix entrenado con *Cityscapes*
<a href="https://youtu.be/tyI7m_BB-Zw" title="Inferencia en diferido con Pix2Pix entrenado con Cityscapes"><img src="../Imagenes/Video-Pix2PixImage.PNG" alt="Inferencia en diferido con Pix2Pix entrenado con Cityscapes" width="500"/></a>

**Enlace del vídeo:** https://youtu.be/tyI7m_BB-Zw

## Modelos de Pix2PixHD y GAUGAN entrenados con *Cityscapes*

<a href="https://youtu.be/NddVFGO_A1k" title="Inferencia en diferido con Pix2PixHD y GAUGAN entrenados con Cityscapes"><img src="../Imagenes/Pix2PixHDGAUGANComparison.PNG" alt="Inferencia en diferido con Pix2PixHD y GAUGAN entrenados con Cityscapes" width="500"/></a>

**Enlace del vídeo:** https://youtu.be/NddVFGO_A1k

## Modelo multimodal de GAUGAN entrenado con *Transient Attributes*, ADE20K y *Cityscapes*

En este modelo se puede apreciar uno de los grandes problemas que tiene el acercamiento que se está utilizando. Al ir infiriendo imagen a imagen, apenas hay coherencia temporal, haciendo que por ejemplo a veces aparezcan imágenes de día en la sección de noche u otros problemas. Cabe destacar que este modelo no es capaz de transmitir la nieve, pero sí es capaz de mostrar unos colores más fríos en general en esa sección.

<a href="https://youtu.be/A0huYdWoSY4" title="Inferencia en diferido con GAUGAN entrenado con Transient Attributes, ADE20K y Cityscapes"><img src="../Imagenes/Video-InferenciaTAADECity.PNG" alt="Inferencia en diferido con GAUGAN entrenado con Transient Attributes, ADE20K y Cityscapes" width="500"/></a>

**Enlace del vídeo:** https://youtu.be/A0huYdWoSY4

# Conducción autónoma con el uso de imágenes sintetizadas con Redes Generativas Adversarias

**Link de la memoria:** https://e-archivo.uc3m.es/ (Actualizado cuando esté disponible)

La conducción autónoma es un tema latente actualmente y cualquier tipo de mejora y nuevo acercamiento que se pueda ofrecer puede llegar a ser determinante. En este trabajo de fin de carrera se muestra un nuevo enfoque que consiste en la utilización de **Redes Generativas Adversarias** para generar imágenes de **carreteras realistas** que puedan ser utilizadas como apoyo para conjuntos de imágenes de Conducción Autónoma. Esto puede **acortar los tiempos de obtención de conjuntos de imágenes etiquetadas**, permitiendo que conjuntos de imágenes previamente muy escasos, comiencen a tener una buena cantidad de imágenes y variabilidad.

Para poder llevar a cabo este proyecto, ha sido necesario utilizar como base el simulador que el usuario de GitHub **tawnkramer** ofrece en su repositorio (https://github.com/tawnkramer/sdsandbox). Se han hecho múltiples modificaciones a este simulador entre las que destacan la **generación de circuitos aleatorios con mapas de Kohonen** y la implementación de una **infraestructura cliente-servidor que permite transmitir imágenes de gran tamaño**.

Por último, el trabajo de fin de carrera termina con la **implementación de un sistema de conducción autónoma** capaz de conducir en algunos circuitos aleatorios utilizando las imágenes generadas por la GAN.

## Modelos de síntesis de carreteras realistas

Los modelos que se muestran en la siguiente tabla han sido entrenados con distintos conjuntos de imágenes que se explican en la memoria del trabajo de fin de grado. Algunos de ellos son ampliamente conocidos, como *Cityscapes* o ADE20K, pero igualmente se van a puntualizar algunos datos.

- ***Cityscapes***: *Cityscapes* es un conjunto de imágenes que contiene tanto la propia imagen realista como su par segmentado. Todas las imágenes son de carreteras alemanas desde el frontal del coche.
- **PaisajeSeco**: Este conjunto de imágenes ha sido obtenido a mano mediante la obtención de *frames* de distintas secciones del siguiente <a href="https://youtu.be/ZOZOqbK86t0">vídeo</a>.
- **roadsAmericanas**: Este conjunto de imágenes ha sido generado mediante la obtención de un *frame* cada 30 frames del mismo vídeo mencinado en el conjunto de PaisajeSeco.
- **ADE20K**: Este conjunto de datos tiene muchísimas imágenes. Para acotarlo y solo utilizar imágenes relacionadas con paisajes, se utiliza un subconjunto utilizado por un trabajo llamado <a href="https://hucvl.github.io/attribute_hallucination/">Attribute Hallucination</a>.
- ***Transient Attributes***: Este conjunto de datos es un conjunto de imágenes de distintas *webcam* repartidas en distintos lugares del mundo a lo largo de las estaciones. Gracias a esto, se puede obtener un mismo mapa segmentado pero con distintos estilos. El trabajo del que se ha obtenido este conjunto de imágenes se llama <a href="http://transattr.cs.brown.edu/files/TransientAttributes-paper.pdf">Transient Attributes</a>.


## Tutorial de uso de los modelos de síntesis de carreteras realistas


## Autor
David González González <a href="https://www.linkedin.com/in/david-gonzalez-gonzalez/">LinkedIn</a>

## Tutor
Juan Manuel Alonso Weber <a href="https://www.inf.uc3m.es/component/comprofiler/userprofile/jmaw">Perfil de la universidad</a>

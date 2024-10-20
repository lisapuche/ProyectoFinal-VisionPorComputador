# Proyecto Final - Vision Por Computador

En un restaurante líder en la preparación de hamburguesas, la experiencia del cliente es fundamental. Su comunidad ha crecido tanto que las reseñas y fotos compartidas por los usuarios en su sitio web se han convertido en una parte esencial del éxito de la marca. Sin embargo, el desafío no solo es gestionar ese flujo de contenido, sino también asegurar que las imágenes publicadas sean relevantes y atractivas, eliminando cualquier ruido o contenido inapropiado.

El equipo del restaurante busca ofrecer una experiencia impecable a los clientes, donde cada foto cuente una historia deliciosa sobre sus productos. Sin embargo, entre tantas reseñas, pueden aparecer imágenes irrelevantes o inapropiadas que afecten la calidad del sitio web.

Es así como el equipo de analítica se propone entrenar un modelo de inteligencia artificial capaz de clasificar las imágenes de comida subidas por los usuarios, garantizando que solo se muestren fotos alineadas con los valores del restaurante. La misión del modelo es clara: reconocer hamburguesas y otros productos clave, pero también rechazar imágenes no deseadas como fotografías borrosas, memes, o elementos no relacionados con la comida. A este proyecto deciden llamarlo 'SnapTaste', emulando el proceso rápido de compartir una foto de su experiencia gastronómica. 

## Dataset
El equipo comienza recopilando miles de imágenes relacionadas con hamburguesas y papas fritas junto con algunas otras imágenes de comida, extraídas del Dataset Food-101 que contiene un total de 101,000 imágenes de comida, distribuidas en 101 categorías diferentes, con 1000 imágenes por cada clase.

## Entrenamiento del modelo
El modelo seleccionado es InceptionV3, una arquitectura potente para tareas de clasificación de imágenes. Sin embargo, el entrenamiento en las primeras imágenes reveló desafíos:

- Ruido en las predicciones y sobreajuste.
- Tiempo de entrenamiento elevado.

## Trabajo futuro
Aunque se realizaron ajustes en los hiperparámetros para un segundo modelo, este mostró signos de sobreajuste y no logró clasificar correctamente en esta primera fase del proyecto. Por ello, en la siguiente etapa se planea implementar nuevas técnicas y utilizar infraestructura más potente, con el objetivo de mejorar significativamente la precisión del modelo.



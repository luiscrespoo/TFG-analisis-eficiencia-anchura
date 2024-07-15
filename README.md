# Análisis de Arquitectura de Redes Neuronales

## Resumen

En este trabajo, se realiza un análisis global de varios aspectos relacionados con la arquitectura de las redes neuronales. Nos centraremos en las Redes Neuronales Totalmente Conectadas, que constituyen la raíz de todo el avance posterior en el campo. Se analizarán varios Teoremas de Aproximación Universal desde diferentes perspectivas.

El primero de ellos es el Teorema de Cybenko, un resultado clásico que nos da una intuición sobre la potencia expresiva de las redes neuronales que cuentan únicamente con una capa oculta en su arquitectura.

Más tarde, analizaremos el Teorema de Aproximación Universal para redes ReLU limitadas por anchura, que si bien no acota el número de capas, esto es, su profundidad; sí que establece un límite en el número de neuronas de las mismas, es decir, en su anchura, en función del tamaño de la entrada. Además, utiliza la función de activación ReLU, de amplia popularidad en la actualidad, y la noción de aproximación en el espacio L1 de las funciones integrables, la cual desarrollamos constructivamente partiendo de los fundamentos.

Poniendo en común todas las reflexiones anteriores, junto con algunos resultados más, formulamos algunos argumentos preliminares sobre el posible rol de la anchura y la profundidad en las redes neuronales, y la eficiencia de las distintas disposiciones de las neuronas. También identificamos los casos en los que podría producirse una pérdida sustancial de expresividad.

Para finalizar, conducimos algunos experimentos en los que se hace uso de las arquitecturas construidas en las demostraciones de los teoremas. Establecemos condiciones concretas en las que es plausible implementarlas, y hacemos un análisis de sus ventajas y desventajas. Estudiamos su funcionamiento y su capacidad de generalización en entornos controlados definidos por funciones lipschitzianas, utilizando algoritmos iterativos de optimización de parámetros, y distintas inicializaciones de dichos parámetros. Esta línea de investigación nos llevará a extraer una serie de conclusiones muy interesantes que fortalecerán nuestro entendimiento de las redes neuronales y reafirmarán empíricamente algunas de las ideas expuestas anteriormente. El código de los experimentos se encuentra en `red_explicita.ipynb`.

El trabajo se plantea en la búsqueda de puntos en común entre la Informática y las Matemáticas, tratando de ofrecer un marco teórico sólido de análisis que pueda dar luz a futuras investigaciones y mejorar las arquitecturas existentes.

## Contenidos

1. Fundamentos Matemáticos
2. Fundamentos de Redes Neuronales
3. Capacidad de Cómputo de las Redes Neuronales
4. Construcción Explícita de Redes Neuronales
5. Comentarios Finales

## Autor

- Luis Crespo Orti

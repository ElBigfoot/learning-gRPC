# learning-gRPC
Aprendiendo el uso de gRPC, junto con algo de Python y Go.

gRPC( remote procedure call) es un formato de intercambio creado por Google. Basado en un formato de serialización conocido
como protocol buffers, los cuales son neutrales en lenguaje, neutrales en paltaforma y extendibles a estrucutración de datos.
Una vez definido como se quieren estructurar los datos, se usa un generados especial de codigo fuente, el cual hara que los datos estructurados
sean faciles de leer y de escribir tanto de un agran variedad de fuentes de datos , asi como en varios lenguajes de programación.

Los Protocol buffers soportan codigo generado en Go y Python.

El codigo generado por los protocol buffers usan HTTP2 como medio de transporte. Otra ventaja es quer una vez escrito el mensaje de definición, las ataduras 
generadas para cada lenguaje desde el codigo fuente quedan disponibles y en concordancia con el formato de mensajes. Dando la ventaja de  que varios 



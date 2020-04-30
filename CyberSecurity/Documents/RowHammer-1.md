# RowHammer: 
RowHammer  cambia el contenido de los bits individuales en la memoria basada en chips DRAM (_Dynamic Random Access Memory_ o RAM Dinamica) para proteger la integridad de los códigos de corrección de errores o _Error-Correcting Code_ (ECC) 
La vulnerabilidad de `RowHammer` puede distorsionar el contenido de los bits mediante la lectura cíclica de los datos de las celdas vecinas

[![RowHammer](https://www.linuxadictos.com/wp-content/uploads/row-Hammer.png)](https://www.youtube.com/watch?v=X8-X_52rg80&feature=emb_title)

__DRAM__ (_Dynamic Random Access Memory_ o RAM Dinamica): Tambien denotado     `Memoria Dinamico de Acceso Aleatorio`, es un tipo de tecnología de memoria RAM basada en condensadores, los cuales pierden su carga progresivamente, necesitando de un circuito dinámico que en ratos revisa la carga y repone en un ciclo de refresco. Dicho esto, tambien existe su contraparte de tipo estatico denotado SRAM o Static RAM.
Su uso comun principalmente como módullo de memoria principal RAM de ordenadores y otros dispositivos. Su principal ventaja es la __posibilidad de construir memorias con una gran densidad de posiciones__ y que funcionen a una velocidad alta.
La `celda de memoria` es la unidad básica de cualquier memoria, capaz de __almacenar un Bit en los sistemas digitales__. La construcción de la celda define el funcionamiento de la misma, en el caso de la DRAM moderna, consiste en un transistor de efecto de campo y un condensador. El principio de funcionamiento básico es: una carga almacenada en el condensador significando 1 y sin carga 0. El trasistor funciona como un interruptor.

Para acceder a una posición de memoria se necesita una dirección de 4 bits, pero en las `DRAM` las direcciones estan multiplexadas en tiempo. Las entradas marcadas como  a<sub>0</sub> y a<sub>1</sub> son el bus de direcciones y por el mismo entra la dirección de las filas y depués la de la columna. Las direcciones se diferencian por medio de señales de sincronización llamadas `RAS` (*Row Address Strobe*) y `CAS` (*Column Address Stroke*) que indica la entrada de cada parte de la dirección.

![DRAM](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e8/Memoria_RAM.JPG/800px-Memoria_RAM.JPG)]
>Memoria DRAM.


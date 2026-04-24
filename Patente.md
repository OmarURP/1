Medidor de flujo de velocidad por amplificación de estructuras turbulentas (MFAET)
DESCRIPCIÓN
La presente invención consiste en un medidor de velocidad de flujo denominado Medidor de flujo de
velocidad por amplificación de estructuras turbulentas (MFAET), que opera bajo el principio del
5 comportamiento de la turbulencia presente en forma natural en un fluido incompresible y analiza la dinámica
de desprendimiento de las calles de von Kármán. El dispositivo permite determinar la velocidad del flujo al
correlacionar la frecuencia de vórtices Eddie [22] generados por la velocidad exterior a una cavidad. El
dispositivo comprende dos elementos principales que interactúan con la dirección de flujo [9]:
Obstáculo generador de vórtices Eddie: Consiste en un cuerpo con una sección transversal de perfil
10 hidrodinámico. Este perfil se caracteriza por tener una cuerda de perfil NACA 2313 [1] en su parte superior
lisa, y una cuerda asimétrica [7] en la parte inferior con dos escalones [5] y [6]. Estos escalones funcionan
como una Cavidad de Medición (CM) diseñada específicamente para alojar y mantener vórtices Eddie en
un espacio controlado, permitiendo que estos cambien su frecuencia de manera proporcional a la velocidad
del flujo exterior (𝑈 0 ) [9].
15 Sistema de adquisición y procesamiento: Se integra por un par de sensores de presión piezoresistivos
situados dentro de la cavidad de medición [6], el arreglo incluye un primer sitio de medición de presión mediante [3]
y un segundo sitio de medición de presión [4], cuya separación puede cambiar, pero siempre dentro de la
cavidad [6] y para cada separación debe ser validado modelación experimental. La conexión
hacia la unidad de procesamiento externa se realiza mediante líneas de alimentación y comunicación
20 electrónicas [2]. Estos sensores detectan las variaciones temporales de presión causadas por el paso de
los vórtices. Las señales son procesadas por una unidad electrónica (microcontrolador) que aplica
algoritmos de compresión cruzada y transformada de Fourier para determinar la frecuencia característica
(𝑓𝑐) del vórtice Eddie [22] presente en la cavidad.
A diferencia de los medidores convencionales, este dispositivo no requiere partes móviles, lo que reduce
el mantenimiento y el riesgo de obstrucción. La ha demostrado una valoración lineal (𝑅^2 = 0. 968 )
entre la frecuencia detectada y la velocidad del flujo, validada mediante modelación numérica que resuelve
las ecuaciones de Navier-Stokes con un modelo de turbulencia de largas escalas tipo LES y con mediciones
de la velocidad instantánea para frecuencias de muestreo de 100 Hz, realizadas con un velocímetro de
efecto Doppler (ADV). La visualización tridimensional de Eddies [22] generada en el modelo numérico
30 OpenFOAM confirma el desprendimiento controlado del MFAET.
El procesamiento de la señal analógica de los sensores [3] y [4] se gestiona mediante un sistema
electrónico de adquisición. Este sistema integra un multiplexor con protocolo I2C [2 3 ], encargado de
conmutar y gestionar la transmisión de datos digitales desde los múltiples sensores de presión.
Posteriormente, la señal es recibida por un microcontrolador [2 4 ], el cual ejecuta el algoritmo de

procesamiento para determinar la frecuencia característica detectada por el par de sensores de presión
internos del MFAET [13].
CAMPO TÉCNICO
5 La presente invención se relaciona con el campo de la hidrometría y la instrumentación para la medición
puntual de la velocidad en un fluido. Específicamente, se trata de un dispositivo que mide la velocidad
puntual de un fluido mediante el análisis del comportamiento de la turbulencia, ya sea en un conducto con
flujo a superficie libre (canal abierto) o a presión (tubería).
10 ANTECEDENTES
En la medición del gasto volumétrico en conductos a superficie libre oa presión, es común el uso de
medidores de velocidad puntual. Sin embargo, los dispositivos de medición de velocidad puntual que
utilizan partes móviles, como son los molinetes de copas Price AA, pierden su calibración con el tiempo
debido al desgaste en su mecanismo.
15 El estado de la técnica incluye diversas soluciones basadas en la generación de vórtices (Vortex Shedding),
diseñadas mayoritariamente para flujos confinados en tuberías a presión, las cuales presentan limitaciones
técnicas cuando se intentan adaptar a condiciones de superficie libre.
Se tiene conocimiento de la patente US 4807481 A, correspondiente a un medidor de flujo que incorpora
un ala que detecta la frecuencia aguas abajo del generador de vórtices. Dicha ala oscila mecánicamente
20 para transmitir la fuerza a un sensor externo. No obstante, este sistema depende de una transmisión
mecánica y de piezas móviles que pueden fallar debido a la presencia de sedimentos.
Por otro lado, existen soluciones orientadas a la medición no intrusiva o de alta tecnología para la industria
petrolera o química. Tal es el caso de la patente CA 2673114 A1, que describe el uso de sensores de fibra
óptica (redes de Bragg) embebidos en el cuerpo del generador para medir deformaciones; y la patente DE
25 102012015887 A1, que propone la detección del movimiento de un cuerpo deflector mediante radar o
microondas desde el exterior del conducto. En este caso el elemento que genera los vórtices tiene una
forma de baja hidrodinámica, lo cual produce pérdidas locales de energía.
Con el objetivo de estabilizar la señal, la patente CN 1118623 A se centra en la optimización geométrica
del cuerpo generador (en forma trapezoidal y triangular), para estabilizar el número de Strouhal a bajos
30 números de Reynolds. Aunque mejora la linealidad, esta referencia no resuelve el problema de la baja
amplitud de la señal en flujos lentos, limitándose a la forma del obstáculo sin proponer mecanismos de
amplificación de la presión.
Finalmente, la patente CN 112654842 A presenta un medidor con sensores piezoeléctricos ubicados en el
interior del cuerpo de obstrucción para evitar fugas al exterior. Si bien este enfoque es útil para contener
35 fluidos peligrosos en tuberías, la detección de la deformación interna del cuerpo rígido resulta ineficiente
para captar las señales débiles generadas por vórtices en corrientes de agua de baja velocidad, típicas en

canales de tierra o concreto, donde la energía del vórtice no es suficiente para deformar significativamente
la estructura del sensor. En este caso la forma hidrodinámica que genera los vórtices produce pérdidas
locales de energía.
La problemática técnica no resulta por el conjunto de estos documentos reside en su ineficacia operativa
5 ya sea contar con partes móviles o elementos que generan pérdidas locales de energía cinematográfica. Existe,
por tanto, la necesidad de un dispositivo capaz de amplificar hidrodinámicamente la señal mediante una
cavidad resonante, con bajas limitaciones de sensibilidad y bajas pérdidas locales de energía cinematográfica, menor
costo operativo de uso.
La problemática técnica no resulta por el conjunto de estos documentos reside en su ineficacia operativa
10 ya sea por contar con partes móviles o elementos que generan pérdidas locales de energía cinética. Por lo
anterior, se propone un dispositivo con la capacidad de amplificar hidrodinámicamente la señal mediante
una cavidad resonante, con baja limitación de sensibilidad y baja pérdida local de energía cinética, lo último
produce un menor costo operativo de uso.

15 DESCRIPCIÓN DE LA INVENCIÓN
Se propone un equipo de medición de velocidad puntual basado en un principio físico de los fluidos
incompresibles al que se denominará “Medidor de flujo de velocidad por amplificación de estructuras
turbulentas” (MFAET). Puede aplicarse en canales prismáticos regulares con flujo de superficie libre o en
tuberías a presión. Este equipo de medición de la velocidad es el elemento primario para calcular el
20 volumen circulante en una sección transversal mediante el método de área-velocidad, tal y como se indica
en el estándar ISO 748:2007.

DESCRIPCIÓN DE LAS FIGURAS
La Figura 1 es una vista en perspectiva isométrica del cuerpo del medidor, apreciándose la geometría
25 general del perfil hidrodinámico y el escalón generador de Eddies.
La Figura 2 ilustra los puntos de muestreo utilizados en el análisis experimental y numérico, detallando la
ubicación de los sensores en la cavidad de medición.
La Figura 3 es una gráfica que muestra el comportamiento lineal de la velocidad 𝑈 0 respecto a la frecuencia
característica (𝑓𝑐) del prototipo.
30 La Figura 4 presenta las gráficas de compresión cruzada y espectro de energía para la frecuencia
característica encontrada con los sensores de presión en la cavidad de medición.
La Figura 5 presenta las gráficas de manipulación cruzada y espectro de energía para la frecuencia
característica obtenida mediante simulación numérica en la cavidad de medición.
La Figura 6 muestra el espectro de potencia de la frecuencia característica encontrada con el equipo ADV
35 en la cavidad de medición.

La Figura 7 es una visualización tridimensional de las estructuras turbulentas generadas por el dispositivo
mediante modelación numérica.
La Figura 8 es un diagrama esquemático de la instalación electrónica del sistema de adquisición de datos,
incluyendo la conexión entre sensores, multiplexor y microcontrolador.
5
MEJOR MÉTODO CONOCIDO PARA REALIZAR LA INVENCIÓN
Calibración Experimental y Linealidad en Canal Hidráulico: para validar el funcionamiento del dispositivo
MFAET y determinar su curva de calibración, se realizaron pruebas experimentales en un canal de
pendiente fija con sección rectangular en un laboratorio. Se instaló un prototipo del medidor MFAET
10 sumergido en el centro de la sección del canal. Como instrumento patrón de referencia se utilizó un equipo
ADV ubicado en el sitio de medición de velocidad [8]. Se varió el caudal del canal para obtener diferentes
velocidades de flujo controlados, a indicar un rango operativo desde 0, 20 ms−^1 hasta 0,66 ms−^1. Para
cada escenario de velocidad, se registraron simultáneamente la velocidad medida (𝑼𝑨𝑫𝑽) [8], la frecuencia
de vórtices (𝒇𝒄) detectada por el par de sensores de presión internos del MFAET [13], complementados
15 con ensayos en modelo numérico [14] y la detección de frecuencia característica mediante el equipo ADV
[12] en la cavidad de medición. Los resultados obtenidos se presentan en la Tabla 1 a continuación:

𝑼𝑨𝑫𝑽 (m/s) 𝒇𝒄 (Hz)
0.20 1.
0.30 1.
0.41 2.
0.505 3.
0.62 3.
0.66 4.
A partir de estos datos experimentales, se graficó la curva de respuesta mostrada en la Figura 3. En el eje
20 [11] se representa la frecuencia detectada en Hz, mientras que en el eje [10] se muestra la velocidad en
m s−^1. Los datos experimentales se ajustan a una línea de ajuste lineal de calibración [15]. Se realizó un
análisis de regresión lineal obteniendo la siguiente ecuación característica para el prototipo:
𝑈 0 =𝐾⋅𝑓𝑐+𝐶
donde la constante de proporcionalidad (𝐾), se relaciona inversamente con el número de Strouhal, mostró
25 una alta estabilidad en todo el rango de medición. El coeficiente de determinación obtenido fue de 𝑅^2 >

96 , lo que demuestra que el dispositivo es capaz de medir la velocidad del flujo basándose únicamente
en la frecuencia presente en la cavidad.
Adicionalmente, se analizó la calidad de la señal mediante la Transformada de Fourier (FFT). En las
comparativas espectrales se observó la energía de espectro FFT de MFAET [ 16 ] identificando claramente
la frecuencia característica de MFAET [17]. Estos valores se contrastaron con la energía de espectro FFT
de velocidad medida 𝑼𝑨𝑫𝑽 [20] y su frecuencia característica [21], así como con la energía de espectro FFT
del modelo numérico [ 18 ] y su frecuencia característica [ 19 ]. Demostrando que el dispositivo es capaz de
medir la velocidad del flujo basándose en la frecuencia generada por el MFAET. Lo anterior hace válido el
5 principio fundamental del funcionamiento de la invención para diferentes velocidades del fluido.

REIVINDICACIONES
Habiendo descrito de manera suficiente y clara mi invención, considero como una novedad y, por lo tanto,
reclamo como de mi exclusiva propiedad, lo contenido en las siguientes cláusulas:
5 1. Medidor de velocidad de flujo de agua por medio de la amplificación de estructuras turbulentas, del
tipo que emplea un cuerpo sumergido en el fluido para generar perturbaciones medibles,
caracterizado por que comprende un cuerpo generador de estructuras turbulentas con un perfil
hidrodinámico de sección transversal tipo NACA modificado, el cual presenta en su parte inferior al
menos un escalón que conforma una cavidad de medición, configurado para alojar y estabilizar
10 vórtices Eddie periódicos; y además un sistema de detección de la frecuencia de los vórtices, que
incluye al menos dos sensores de presión dispuestos dentro de dicha cavidad de medición, para
registrar las fluctuaciones de presión con un corrimiento temporal generadas por la presencia del
vórtice Eddie.

Medidor de velocidad de flujo de agua por medio de la amplificación de estructuras turbulentas, de
15 conformidad con la reivindicación 1, caracterizado porque los sensores de presión son del tipo
piezoresistivo y están configurados para operar con una tasa de muestreo que permite identificar
la frecuencia característica de los vórtices Eddie, mediante una medición cruzada de las señales.
Medidor de velocidad de flujo de agua por medio de la amplificación de estructuras turbulentas, de
conformidad con la reivindicación 1, caracterizado porque el cuerpo generador está fabricado
20 mediante fabricación en material rígido, con un acabado superficial liso para limitar la generación
de turbulencias secundarias.
Medidor de velocidad de flujo de agua por medio de la amplificación de estructuras turbulentas, de
conformidad con la reivindicación 2, caracterizado porque el sistema electrónico de adquisición
incluye un multiplexor con protocolo I2C y un microcontrolador programado para calcular la
velocidad del flujo exterior en función lineal de la frecuencia característica.
CURRÍCULUM
La presente invención se refiere a un medidor de velocidad puntual para fluidos incompresibles, aplicable
en canales a superficie libre o conductos a presión. El medidor consiste en un obstáculo sumergible con
un perfil hidrodinámico que induce la generación controlada de vórtices Eddie, dentro de una cavidad de
5 mediciones integrada en el perfil con una geometría escalonada [1]. El sistema incorpora sensores de presión
piezoresistivos alojados en dicha cavidad, que registran las fluctuaciones de presión. Mediante el
procesamiento de estas señales, se determina la frecuencia característica de los vórtices, la cual es
directamente proporcional a la velocidad del flujo. Este dispositivo tiene una medición lineal entre la
frecuencia y la velocidad del fluido.
Sistemas de energía más limpios 3 (2022) 100017
Los índices de contenidos están disponibles en ScienceDirect.
Sistemas de energía más limpios
Página principal de la revista: http://www.elsevier.com/locate/cles
Modelado y optimización de una turbina Kaplan: un estudio exhaustivo.
Estudio teórico y de CFD
Chamil Abeykoon a^ ,^ b^ ,^ ∗^
a (^) Centro de Materiales Compuestos del Noroeste, Departamento de Materiales, Facultad de Ciencias e Ingeniería, Universidad de Manchester, Oxford Road, Manchester M13 9PL,
Reino
Unido b (^) Facultad de Ciencias e Ingeniería, Instituto de Investigación Aeroespacial, Universidad de Manchester, Oxford Road, Manchester M13 9PL, Reino Unido

información del artículo
Palabras clave:
Generación de energía
Turbina
Energía hidroeléctrica
Ángulo de las palas
Velocidad tangencial
Diseño y optimización
Modelado
CFD

abstracto
Sin duda, el mundo entero se ha visto obligado a aumentar el uso de fuentes de energía limpias/renovables, en particular
debido a las alarmantes preocupaciones ambientales que han sido causadas por las emisiones/contaminación basadas en combustibles fósiles y
también con el agotamiento previsto de esas reservas de combustibles fósiles. En las últimas décadas, el combustible fósil global
El consumo ha aumentado significativamente (es decir, 136.761 TWh en 2019, lo que supone un aumento del 45% desde 2000) con la
rápida industrialización de muchas economías y también con el aumento de la intensidad energética de la industria doméstica
estilo de vida. Por lo tanto, cambiar a fuentes de energía renovables es una prioridad global clave actual para restaurar el equilibrio de la naturaleza.
De las reservas de energía renovable, la energía hidroeléctrica ha sido una de las principales fuentes que se remontan a la década de 1770.
La eficiencia de las turbinas hidroeléctricas se ve muy afectada por el rendimiento de su rueda de rodadura, ya que esta sirve como
la unidad principal que se encarga de extraer la energía del agua que fluye. Por lo tanto, esta investigación tiene como objetivo
Investigar los enfoques de diseño y optimización para una rueda de rodete de una turbina Kaplan. Inicialmente, un detallado
Se realizó un diseño teórico para definir las características principales del corredor y se obtuvo una eficiencia teórica.
de alrededor del 94%. Por lo general, los diseños teóricos se basan en numerosas suposiciones simplificadoras y, por lo tanto, estos diseños...
Las señales podrían proporcionar solo una solución aproximada. Este hecho se estableció como el modelo CFD implementado para
El mismo diseño teórico alcanzó una eficiencia de tan solo el 59,98%. Por lo tanto, se utilizó CFD para un análisis más profundo.
y también modificar el diseño propuesto teóricamente donde los efectos de las velocidades tangenciales de entrada/salida
Se evaluaron y modificaron las palas, la distribución de la presión a través del rodete y el número de palas.
para mejorar la capacidad de extracción de energía del corredor. Los resultados de CFD mostraron que la teoría original
El diseño del sistema de alimentación podría optimizarse para alcanzar una eficiencia del 93,01% con modificaciones realizadas cuidadosamente.
En general, los ángulos de entrada y salida de las palas tuvieron un impacto significativo en la potencia de la turbina Kaplan.
rendimiento de generación. Finalmente, una comparación exhaustiva de los modelos teóricos, teóricos y de CFD-
Se presentan diseños optimizados con posibles recomendaciones para mejorar la eficiencia de la generación de energía.
de una turbina Kaplan.
1. Introducción
Hoy en día, la gente está muy orgullosa de afirmar que tiene una vida lujosa,
maravillosas innovaciones tecnológicas, e incluso la capacidad de explorar
otros planetas y galaxias. Sin embargo, en los últimos siglos, ha habido
No se prestó mucha atención al daño que la gente ha estado causando a la
el medio ambiente mientras transforman sus vidas desde el llamado
Desde la Edad de Piedra hasta la era digital moderna. Con la observación de algunos cru-
problemas sociales como el calentamiento global (disolución de los glaciares, aumento del nivel del mar)
nivel), extinción de algunas especies (plantas, animales), contaminación extrema
condiciones (aire, aguas, tierra), escasez de recursos naturales, pan-
demics, etc. durante las últimas 2-3 décadas, la gente se dio cuenta de que sus actividades
∗ (^) Correspondencia a: Northwest Composites Centre, Departamento de Materiales, Facultad de Ciencias e Ingeniería, Universidad de Manchester, Oxford Road, Manch-

éster M13 9PL, Reino Unido.
Dirección de correo electrónico: chamil.abeykoon@manchester.ac.uk
han estado causando graves impactos adversos en el equilibrio de la naturaleza.
y el bienestar de esta planta. Finalmente, están empezando a comprender...
soportan el nivel de destrucción que causaron y ahora buscan soluciones.
acciones para restaurar el equilibrio de la naturaleza que fue dañado por nosotros mismos.
en nombre del desarrollo. En esta misión, una de las consideraciones clave es...
El objetivo es reemplazar las fuentes de energía no renovables basadas en combustibles fósiles.
con posibles alternativas de energía verde. Aunque el aumento del uso
Las energías renovables podrían no resolver rápidamente los problemas predominantes.
que los seres humanos crearon en los últimos cientos de años, sería
ser una de las medidas más necesarias para resolver o controlar la situación predominante
problemas a largo plazo. En lo que respecta a la limpieza y restauración de la naturaleza, el
los recientes confinamientos mundiales debido a la pandemia de COVID-19 (que es uno
https://doi.org/10.1016/j.cles.2022.
Recibido el 14 de enero de 2022; Recibido en forma revisada el 13 de julio de 2022; Aceptado el 11 de septiembre de 2022
Disponible en línea a partir del 13 de septiembre de 2022.
2772-7831/©2022 El autor. Publicado por Elsevier Ltd. Este es un artículo de acceso abierto bajo la licencia CC BY-NC-ND.
( http://creativecommons.org/licenses/by-nc-nd/4.0/ )
Nomenclatura
𝐴 Área de la sección transversal del tubo de aspiración [m^2 ]
𝑐 Velocidad del flujo del fluido [m/s]
𝑐𝑢 1 Velocidad de salida tangencial [m/s]
𝑐𝑢 2 Velocidad tangencial de entrada [m/s]
Diámetro del rodillo 𝐷𝑎 [m]
𝐷𝑁 Diámetro del buje [m]
Fuerza meridiana [N]
𝐹𝑟𝑒𝑠 Fuerza resultante [N]
Fuerza tangencial [N]
𝑔 Constante gravitacional [m/s²]
𝐻 Cabeza [m]
Cabezal de succión [m]
𝐻𝑆𝑚𝑎𝑥 Altura máxima de succión [m]
𝑀 Par [Nm]
𝑚̇ Caudal másico [kg/s]
𝑁 Velocidad de rotación [s−^1 ]
𝑁𝑠 Velocidad de rotación específica [-]
𝑃 Potencia [Vatios]
𝑝 Presión [Pa]
𝑝𝑎𝑡𝑚 Presión atmosférica [Pa]
𝑝𝑣 Presión de vapor del agua [Pa]
𝑠 ′′ Longitud de la cuerda [m]
𝑡 ′′ Partición de la hoja [m]
𝑢 Velocidad tangencial [m/s]
𝑉 Volumen [m^3 ]
𝑉̇ Caudal (también descarga) [m^3 /s]
𝑤 Velocidad relativa [m/s]
Valor de la coordenada x, dirección x [m]
Valor de la coordenada y, dirección y [m]
𝑧 Valor de la coordenada, dirección z [m]
𝑧 ′′ Número de cuchillas [-]
𝛼 Ángulo de ataque [°]
𝛽 Ángulo de velocidad del flujo [°]
Δ Diferencia [-]
𝛿 Número de diámetro [-]
𝜂 Eficiencia [%]
𝜎 “Schnelllläufigkeit”[-]
𝜎𝑐 Coeficiente de cavitación [-]
𝜌 Densidad del agua [kg.m^3 ]
de los virus más mortales en la historia humana conocida) estaban mostrando algunos
movimientos positivos en todo el mundo debido a la reducción de las actividades humanas
(es decir, en particular la reducción de los niveles de emisiones y del polvo en la atmósfera-
esfera). Sin embargo, el mundo entero podría volver pronto a la normalidad.
y por lo tanto, las alteraciones en la naturaleza continuarán como de costumbre.
Dadas estas circunstancias, los fabricantes de energía globales tienen
se han visto obligados a centrarse en fuentes de energía renovables como la solar, la eólica,
hidro, geotérmica, biomasa, undimotriz, mareomotriz, etc. Actualmente, la hidro-
La energía de dropower representa la mayor parte de la energía renovable mundial.
generación donde una capacidad de generación de más de 4.000 TWh tiene
se han registrado en todo el mundo a partir de 2018 (IRENA International Re-
Agencia de Energías renovables, 2019). Por lo tanto, la energía hidroeléctrica contribuye a
hasta el 15% de la generación mundial de electricidad (26.600 TWh ( IEA Inter-
Agencia Nacional de Energía, 2018) y parte de la información relevante
se presenta en las figuras 1 y 2. Además, la hidroeléctrica es una de las más antiguas y
una fuente altamente confiable para aprovechar la energía renovable.
Otras fuentes renovables importantes, las turbinas eólicas funcionan bien solo en el área
facilidades de viento fuerte (también las capacidades de generación podrían estar fluctuando)
a lo largo del día), la capacidad de energía solar depende de la hora y
condiciones meteorológicas del día y también de la ubicación geográfica,
pero el agua, la fuente de la energía hidroeléctrica, fluye de manera bastante constante en
los ríos en la mayor parte del mundo (IHA International Hydropower Or-
organización, 2017). Por lo tanto, la generación de energía hidroeléctrica es bastante común.
en todo el mundo y la región de Asia-Pacífico se encuentra actualmente a la cabeza por
generando más de 1.720 TWh a partir de 2018, mientras que Oriente Medio re-
Gion se encuentra al final de la lista al generar solo alrededor de 20 TWh a través de
energía hidroeléctrica. Por lo general, las turbinas hidroeléctricas pueden generar energía.
eficiencias de hasta el 95% con una capacidad de generación de energía promedio.
de hasta 800 MW, y también pueden operar con alturas de hasta 1800
m dependiendo del tipo/modelo (Zivkovic et al., 2018). En la actualidad, el
La central hidroeléctrica de la presa de las Tres Gargantas en China cuenta con 32 turbinas (que
(Se completó en 2012) es la central hidroeléctrica más grande del planeta.
con una asombrosa capacidad de generación de 22.500 MW (Power Technology,
2013). Además, en 2019, China (siendo pionera en la generación de energía hidroeléctrica-
ción) ha generado 1.302 TWh de energía hidroeléctrica, lo que representa alrededor de
El 30% de la generación mundial de energía hidroeléctrica, mientras que las naciones 2ª y 3ª en
La lista (Canadá y Brasil) han generado solo 398 TWh y 386 TWh,
respectivamente. Como era de esperar, el diseño y la optimización de la
Las palas del rotor son fundamentales para la eficiencia de una turbina. Las palas
controlar el flujo del agua mientras se transforma la energía cinética transportada
por el agua en la energía rotacional del corredor y luego finalmente en
la energía eléctrica. Por lo tanto, la geometría/diseño de las palas debe ser
cuidadosamente optimizado para aprovechar la mayor energía posible. Mientras tanto,
También debe considerarse la susceptibilidad de las palas a la cavitación y
evitado durante el proceso de diseño. Además, el análisis del flujo a-
comportamiento en toda la maquinaria hidráulica utilizada en la generación de energía
También es importante para optimizar la eficiencia de recolección de energía de
los fluidos en movimiento (Kuriqi et al., 2019). Por lo tanto, es esencial y oportuno
continuar la investigación sobre turbinas y otros dispositivos relacionados utilizados
en la generación de energía hidroeléctrica (que es la mayor fuente de energía renovable del mundo)
fuente de generación de tricity) con el propósito de mejorar su potencia
capacidades/eficiencias de generación.
1.1. Generación de energía hidroeléctrica
Se sabe que las antiguas naciones griegas fueron las primeras en utilizar el en-
Energía transportada por el agua en movimiento (energía hidroeléctrica) para aplicaciones prácticas
ya hace unos 2000 años. Se ha informado que los griegos tienen
construyeron ruedas hidráulicas para moler el trigo para preparar harina, para serrar
madera y también para alimentar sus fábricas textiles. El antiguo rey de Sri Lanka-
El templo de Sigiriya también es conocido por ser el jardín acuático más antiguo del mundo y
Han construido una serie de fuentes alimentadas por gravedad utilizando algunos métodos sofisticados.
tecnologías hidráulicas catedráticas hace más de 1600 años y algunas de estas
Las fuentes siguen funcionando hoy en día (Cooray, 2012). El antiguo Sri
Los habitantes de Sri Lanka también son bien conocidos por su uso de tecnologías hidráulicas en
aspectos como la agricultura (Dharmasena, 2010) y la ingeniería de riego.
ing (Gunasekara, 2004). Luego, a mediados del siglo XVIII, la evolución
de la tecnología hidroeléctrica moderna/reciente y las turbinas comenzaron af-
ter publicando un informe en cuatro volúmenes titulado “Architecture Hydraulique”,
que explicaba las máquinas hidráulicas de eje vertical y horizontal,
por un ingeniero hidráulico francés, BF de Bèlidor (Departamento de Energía de EE. UU.,
2022). Luego, después de 180 años, en 1880, se generó la energía hidroeléctrica.
clasificado por primera vez por Grand Rapids Electric Light and Power Com-
empresa en Michigan que utiliza una dinamo conectada a una turbina impulsada por agua.
bina por iluminar 16 lámparas en sus tiendas y teatros. Seguido de
Todos estos avances, la primera central hidroeléctrica del mundo fue construida...
Construido en el río Fox en Appleton, Wisconsin, EE. UU. en 1882 con un
capacidad de generación de 12,5 kW. Luego, en agosto de 1913 (después de 33 años)
desde el inicio de la primera central hidroeléctrica), la turbina Kaplan fue
desarrollado por un ingeniero austriaco, Viktor Kaplan (Woehl, 2013).
Se muestra la disposición de una central hidroeléctrica con sus unidades principales.
en la Figura 3. Estas centrales eléctricas se utilizan para extraer la energía cinética.
del agua que fluye a través de una tubería forzada para hacer girar una turbina que es
acoplado a un generador para producir energía eléctrica. La mayoría de
Las centrales hidroeléctricas se basan en los ríos naturales que utilizan un
presa construida a través de un río para crear un embalse para almacenar el agua.
El embalse se encuentra a una gran altura de la central eléctrica (es decir, la gravedad).
Figura 1. Generación mundial de electricidad renovable por región (2005-2020 (en teravatios-hora, TWh) (Fuente: Agencia Internacional de Energía).
Figura 2. Capacidad hidroeléctrica instalada total a nivel mundial a finales del año 2018, incluyendo el almacenamiento por bombeo (en gigavatios) (Fuente: International Hydropower).
Organización).
energía potencial) y luego se utiliza una tubería de presión para generar una alta
velocidad del chorro de agua (es decir, la energía cinética) que pasará a través de un
turbina. Actualmente, la generación de energía basada en la energía mareomotriz (con el uso
de las mareas a través del océano) también se está volviendo popular. El propósito de
cualquier tipo de turbina sirve para extraer la energía transportada por el agua que fluye,
y se puede seleccionar un tipo/diseño de turbina adecuado en función del número
de factores como se discute en la Sección 1.2. Finalmente, la cinética extraída
La energía del agua se transformará en energía eléctrica y se alimentará a
la red nacional para uso público ( ESHA, 2004 ).
1.2. Diferentes tipos de turbinas y su funcionamiento en la energía hidroeléctrica.
generación
Por lo general, las turbinas utilizadas para la generación de energía hidroeléctrica se pueden clasificar.
se clasifican en dos tipos fundamentales como reacción e impulso. El más
El tipo adecuado se seleccionará principalmente en función del caudal y la altura de elevación.
la central eléctrica, para lograr la mayor eficiencia posible. La moderna
Las turbinas hidroeléctricas se pueden clasificar en tres tipos principales: Francis,
Turbinas Pelton y Kaplan como se ilustra en la Fig. 4. La Fig. 4 indica la
La base para elegir una turbina depende de dos parámetros clave: la altura de caída.
del sitio (H) y un coeficiente adimensional (𝜎) que se relaciona con el
velocidad operativa específica de la turbina. En mecánica de fluidos, la altura (H) es
relacionado con la energía en un fluido incompresible que indica en términos
de una altura en metros o pies, y para este estudio, se puede considerar como
la diferencia de altura entre las aguas de cabecera y de cola. Tal como se presenta
En la figura 4, las turbinas Kaplan y Francis se utilizan habitualmente con baja y
cabezas medias, respectivamente, mientras que las turbinas Pelton se utilizan principalmente con
cabezas altas (Balkhair y Rahman, 2017). El coeficiente adimensional
𝜎 es una característica importante de una turbina que depende del volumen.
caudal métrico del fluido ( 𝑉̇ ), velocidad de rotación de la rueda ( N ),
La constante gravitacional (g) y 𝜎 se pueden calcular a partir de la ecuación (1).
𝜎 =
2 N
√
𝜋𝑉̇
(2 g) 3/^
(1)
Fig. 3. Esquema de una central hidroeléctrica con sus unidades principales (ESHA, 2004).
Fig. 4. Los criterios para elegir turbinas en función de las diferentes capacidades de altura de caída (H) (Menny, 2006).
Figura 5. Diagramas esquemáticos de los rotores de turbina: uno de reacción (izquierda) y otro de impulso (derecha).
La función general de cualquier turbina hidráulica (tanto para reacción como para...
Los tipos de impulsos son bastante simples y simplemente transforman la energía cinética.
energía del agua que fluye en un movimiento rotacional. La rueda de rodadura de
una turbina de reacción (como Francis y Kaplan) tiene múltiples álabes de un
ciertas formas que se ensamblan circunferencialmente (es decir, espaciadas uniformemente)
sobre un eje, y el fluido entra en la turbina en una dirección paralela a su
eje de rotación. Mientras tanto, las turbinas de impulso (por ejemplo, Pelton) están equipadas con
palas en forma de cubo que también se ensamblan circunferencialmente (es decir,
espaciados uniformemente) en un eje. En este tipo de turbinas, el agua que fluye
es forzado como un chorro de alta velocidad en dirección perpendicular al eje de
rotación de la turbina como se ilustra en la Fig. 5. Para ambos tipos, el agua
entra con cierta velocidad C, y luego la energía transportada por el
El agua que fluye se convierte en una fuerza rotacional Fu al golpear las aspas.
que activa el movimiento de rotación de la rueda. El eje de la turbina
está conectado a un generador para transformar la energía rotacional en
energía eléctrica.
La efectividad de una turbina para extraer energía depende de la
componentes como el tubo de aspiración, el eje, las paletas guía, el embrague, los cojinetes,
y así sucesivamente, además de su corredor. De todos estos componentes, el diseño
Las aspas del rotor desempeñan un papel vital en términos de generación de energía.
eficiencia ya que son responsables de extraer la energía transportada por
agua corriente, y también podrían ser susceptibles a la cavitación que es
un problema común en cualquier maquinaria hidráulica (ESHA, 2004).
La figura 6 ilustra la relación entre la relación de carga y la eficiencia.
eficiencia de tres tipos principales de turbinas, e indica que la eficiencia
La eficiencia aumenta con la relación de carga independientemente del tipo de
turbina. La relación de carga define la relación entre la potencia real y la teórica.
caudales a través de una turbina. Con una relación de carga baja, una presión adecuada
Figura 6. Diagrama de eficiencias de las turbinas.
(Dixon, 2005).
Tabla 1
Características comunes de las turbinas (Dixon, 2005).
Pelton turbine Francis turbine Kaplan turbine
Specific speed (rad) 0.05 –0.4 0.4 –2.2 1.8 –5.
Head (m) 100 - 1770 20 - 900 6 - 70
Maximum power (MW) 500 800 300
Optimum efficiency, % 90 95 94
Regulation method Needle valve and deflector plate Stagger angle of guide vanes Stagger angle of rotor blades
Fig. 7. (a) - Esquema de una disposición de una turbina Pelton, (b) –Una sola pala de una turbina Pelton con álabes dobles simétricos.
podría no desarrollarse en las palas del corredor y, por lo tanto, el mo- resultante
El mentón también debería ser bajo (por lo tanto, también baja eficiencia). Además, bajo
En tales condiciones, podrían desarrollarse efectos de turbulencia y remolino.
el corredor y esto también puede crear algunos efectos adversos en el corredor.
capacidad de extraer la energía (Dixon, 2005). Algunos de los comunes
Las características de tres tipos principales de turbinas hidroeléctricas se muestran en
Tabla 1. Como se puede observar, una turbina Kaplan debería poder alcanzar
una eficiencia óptima de alrededor del 94%.
1.2.1. Turbina Pelton
Las turbinas Pelton se clasifican como turbinas de impulso y normalmente se utilizan
para centrales hidroeléctricas que operan bajo altas presiones (es decir, una altura de
hasta 2000 m) y caudales bajos. Este tipo fue inventado en 1884 por un
El ingeniero hidráulico estadounidense L.A. Pelton. Un flujo de agua a alta velocidad.
llega a través de una tubería forzada (en forma de un solo chorro o múltiples chorros de
hasta seis) y luego golpea tangencialmente las palas de la turbina como se ilustra
En la figura 7, las palas de las turbinas Pelton tienen forma de palas dobles simétricas.
cubos con una pared/borde de corte en el medio (también conocidos como divisores)
y se muestran en la Fig. 7 –(b)) y se ensamblan circunferencialmente en
un eje. Cuando un chorro de agua golpea una cuchilla (o un cubo), se divide en dos partes.
fluye y se desvía casi 180°. La fuerza de impulso generada por esto
La acción permite la rotación del rotor/impulsor (es decir, transferencia de energía).
desde el agua que fluye hasta el rotor de la turbina) ( Dixson, 2005 ).
1.2.2. Turbina Francis
Se trata de una turbina de reacción y se utiliza comúnmente en la energía hidroeléctrica.
estaciones que operan bajo una presión (altura) media y un caudal medio
tasas. En 1849, un ingeniero hidráulico estadounidense inventó la turbina Francis.
ingeniero hidráulico James B. Francis. En estas turbinas, el flujo de agua
está regulado por un conjunto de paletas guía que están montadas radialmente en la turbina.
entrada de la góndola como se muestra en la Fig. 8. El propósito principal de estas paletas guía es
dirigir el flujo de agua radialmente con un cierto ángulo de ataque hacia
La rueda del rotor de la turbina y también estas paletas pueden autoajustarse para pequeñas
variaciones de descarga para lograr la mejor eficiencia posible, o incluso
detener completamente la entrada de agua en caso de problema. Idealmente, el
Las palas del rotor de una turbina Francis transforman un flujo radial de agua.
Figura 8. Esquema de la disposición de una turbina Francis y el flujo.
Fig. 9. Esquema de la rueda del rotor y los álabes directores de una turbina Kaplan (Menny, 2006).
en un flujo axial al entrar en el tubo de aspiración y por lo tanto también son
conocidas como turbinas de flujo mixto. Los álabes del rotor tienen una forma especial.
de modo que creen una diferencia de presión cuando un fluido pasa a través de ellas.
(por lo tanto genera una fuerza de sustentación) y también un fluido generará un impulso.
fuerza al salir del corredor. La combinación de estos levantamientos e im-
Las fuerzas pulsantes generan la rotación del rotor. En comparación con Pelton
Las turbinas y los rotores Francis deben estar completamente sumergidos bajo el agua para
funcionalidad eficiente (Menny, 2006).
1.2.3. Turbina Kaplan
La turbina Kaplan fue inventada en 1913 por un ingeniero hidráulico austriaco.
ingeniero Viktor Kaplan. Es un tipo de reacción y es apropiado para el
centrales hidroeléctricas que operan a bajas presiones (es decir, bajas alturas) y
también con descargas considerablemente mayores. Al igual que los corredores de Francis, Kaplan
Los patines también deben estar completamente sumergidos en el agua para un correcto funcionamiento.
La naturaleza del agua, regulada por las paletas guía, incide sobre el rotor.
Las palas se mueven axialmente con un cierto ángulo de ataque como se muestra en la Fig. 9. Cuando el
El caudal es variable, las paletas guía ajustables están normalmente controladas.
mediante un mecanismo de gobierno asociado con la variación del caudal de agua.
Además, estas paletas guía se pueden cerrar completamente para detener el flujo de agua.
si es necesario. El agua entra y sale de la turbina en la dirección axial.
ción al eje. Cuando el agua golpea las palas de la turbina, la fuerza de reacción
genera la rotación del corredor y luego el agua sale a través del
tubo de tiro. Los patines pueden tener aspas fijas o ajustables. La mayoría
La disposición común son los rieles verticales (como se ilustra en la Fig. 9),
o bien los corredores pueden colocarse horizontalmente o en algún lugar en-
entre. Si el tubo de aspiración tiene una sección transversal uniforme, el flujo
La velocidad es uniforme y, por lo tanto, el corredor podría colocarse en una posición adecuada.
posición del tubo de tiro. En caso de que el corredor esté situado dentro
el tubo de tiro, entonces las paletas guía también deben colocarse justo en
delante del corredor para guiar con precisión el flujo de agua. Sin embargo, si
El tubo de aspiración es relativamente largo, el posible riesgo de cavitación puede
también puede aumentar debido al aumento de la cabeza (Dixon, 2005).
1.2.3.1. Álabes directores de una turbina Kaplan. Obviamente, los álabes directores desempeñan un papel importante.
un papel importante en el diseño de turbinas de alta eficiencia. Típicamente, la
Las paletas guía están situadas justo encima del rodete (como se muestra en las figuras 9 y 1).
10) para lograr las mejores condiciones de flujo hidráulico posibles. El flujo
de agua entra en la turbina axialmente con una velocidad C o. La ergonomía
de las paletas guía proporciona un giro al agua que fluye para golpear en
las palas del corredor con un cierto ángulo de ataque 𝛽 1 y una velocidad de flujo-
Ciudad C 1. Este giro creado por las paletas guía permite que el agua golpee las palas.
con una alta fuerza de reacción que promueve la rotación del corredor y
Por lo tanto, un ajuste adecuado de las paletas guía es crucial para la eficiencia de las turbinas.
eficiencia. Por lo general, el ángulo con el que el agua ataca un corredor puede ser determinado.
definido como el ángulo de salida del agua que sale de las paletas guía.
(Arne, 2001).
1.2.3.2. Extracción de energía a través de un corredor Kaplan. Como se explicó
En la sección anterior, el agua entra en la turbina con un caudal absoluto.
velocidad C o y debido a las paletas guía, el agua se retuerce y
golpea las aspas del corredor con una velocidad absoluta C 1 y un ángulo de
ataque 𝛼. La energía extraída debido a la fuerza de reacción permite el
rotación de la rueda con una velocidad de la pala u como se indica en la Fig. 11. Un resultado-
Se generará una fuerza constante F res en cada pala debido a la fuerza axial.
F m y la fuerza tangencial F u. Mientras tanto, w 1 y w 2 son las fuerzas relativas.
velocidades en la entrada y salida de los álabes, como se indica en la figura 11.
Finalmente, el agua sale de las palas del rotor axialmente, con una velocidad
ciudad C 2 en su borde posterior, a través del tubo de tiro ( Dixson, 2005 ).
A medida que el agua pasa por el rodillo, extrae la energía del coche.
impulsada por el agua que fluye y por lo tanto la presión del agua cae significativamente.
sónicamente. La diferencia de presión entre la entrada y la salida de la turbina-
Los flujos pueden definirse como Δ 𝑃. La ecuación (2), que recibe su nombre de Euler, define
la cantidad de potencia generada por un rotor de turbina (P runner) resultante
a partir de la diferencia de velocidad tangencial a través de la entrada y la salida del álabe
flujos.
𝑃𝑟𝑢𝑛𝑛𝑒𝑟 = 𝑚̇ ( 𝑢 1 𝑐𝑢 1 − 𝑢 2 𝑐𝑢 2 ) (2)
Donde 𝑚̇ es el caudal másico del agua que fluye, c u1 y c u2 son
las velocidades tangenciales de entrada y salida, respectivamente.
1.3. Cavitación
En cualquier máquina hidráulica, la presión estática puede disminuirse con-
considerablemente dentro de las áreas de velocidades significativamente altas, como se explicó
por la ecuación de Bernoulli. Como lo describió Menny (2009), el bajo-
La presión de fluido más posible dentro de una unidad de rotor de turbina puede ser el agua.
presión de vapor a una temperatura dada. Como la presión estática de la unidad
cuando alcanza la presión de vapor del líquido, entonces parte del líquido puede ser
convertido en estado gaseoso. Esto puede causar un vol- bastante significativo.
expansión de ese fluido y por lo tanto el fluido no puede ser considerado
ya no como un fluido incompresible. Entonces el vapor condensado burbujea-
Los bles implosionan instantáneamente creando microhaces de agua como representación.
presentado en la Fig. 12. Este fenómeno puede generar tensiones residuales mientras
generando picos de presión significativamente altos. Tales tensiones pueden causar
desgaste de los materiales y también puede dañar los componentes (por ejemplo, el corredor)
palas) (Menny, 2005). La cavitación suele ocurrir en los lugares donde
La presión es bastante baja y la velocidad del fluido que fluye es bastante
alto (por ejemplo, a través de las palas del rodillo). Por lo tanto, máquinas rotativas de alta velocidad
Las turbinas como Francis y Kaplan presentan cierto riesgo de cavitación.
(IHA, 2017). Por lo tanto, debe asegurarse que la presión estática dentro
La unidad es mayor que la de la presión de vapor del líquido en movimiento.
para evitar la posible formación de burbujas de vapor precarias y sus
implosiones alrededor de la rueda de rodadura. Para lograr esto, la succión típica
cabeza H s (es decir, la diferencia de altitud entre el agua del corredor y el agua de cola,
(véase la figura 14) que está asociada con la presión estática de la unidad no debería
ser excesivamente alto ya que no hay ninguna posibilidad práctica de tiempo real
observación del fenómeno de cavitación una vez que una turbomáquina está en funcionamiento
operación.
Figura 10. Diagrama esquemático que muestra la disposición.
componentes de las palas del rotor y las paletas guía.
Figura 11. Esquema que indica las velocidades y fuerzas en un Kaplan
cuchilla de corredor.
Figura 12. Esquema que muestra el comportamiento de cavitación de un
Corredor de Kaplan (Mecaflux, 2013).
1.4. Estudios previos sobre el diseño y la optimización de turbinas Kaplan con y
sin CFD
En 2012, Januja et al. (2013) analizaron la potencia de salida de
una turbina Kaplan utilizando enfoques experimentales y CFD, y una
La comparación de los resultados obtenidos se muestra en la Fig. 13. Aquí, el CFD
La potencia de salida calculada es ligeramente inferior a la del experimento.
tal. Otro trabajo reciente de Janjua et al. (2020) presentó un modelo paramétrico
Estudio para evaluar el efecto del perfil de la pala en la potencia de salida.
de una turbina Kaplan. Han desarrollado cuatro geometrías de pala diferentes.
Intenta variar el perfil de la pala en diferentes ángulos en un modelo CAD.
y luego estos modelos se mejoraron utilizando técnicas computacionales.
Además, estos modelos fueron validados utilizando datos experimentales y la re-
Los resultados confirmaron que la potencia de salida de la turbina podría mejorarse.
en un 5,43% con los cambios propuestos, y esto podría ser equivalente a
obteniendo una ganancia financiera de 18.000 USD al mes por una planta de 4,6 MW.
unidad de turbina.
Dragica et al. (2014) analizaron las inconsistencias entre algunos ex-
mediciones experimentales y simulaciones numéricas relacionadas con un Ka-
turbina planificada con el propósito de evaluar la precisión de los números-
enfoques ical. Con las simulaciones numéricas (o CFD), estudiaron
la simulación en estado estacionario, corrección de curvatura, transporte de esfuerzo cortante,
Modelo Kato-Launder, simulación de grandes remolinos zonales y adaptación a la escala.
simulación. De estos métodos, las simulaciones en estado estacionario realizadas
con varios modelos de turbulencia dieron los peores resultados con considerable
errores de tasa de descarga total. Mientras tanto, transporte de esfuerzo cortante, escala-
Figura 13. Una comparación de resultados experimentales y
Resultados de CFD sobre el caudal frente a la potencia de salida de un
Turbina Kaplan (Januja et al., 2013).
La simulación adaptativa y la simulación de grandes remolinos zonales pudieron proporcionar...
proporcionar mejores resultados con menos del 1% de discrepancia con respecto al experimento
mediciones. Basándose en estas consideraciones, la simulación de estado estacionario
Se eligió el método de ción para el presente estudio ya que es bastante compatible.
debe realizarse con ANSYS, mientras que otros métodos pueden ser altamente...
plex y también pueden requerir supercomputación y también tiempo excesivo
escalas para generar las soluciones.
Mulu et al. (2012) estudiaron un modelo de turbina Kaplan asociado con
una anemometría láser Doppler y múltiples sensores de presión para optimizar
el tubo de aspiración para mejorar la eficiencia de la turbina, mediante el uso de ambos exper-
herramientas mentales y computacionales. Descubrieron que el remolino que dejaba el
El corredor influye en la funcionalidad del tubo de tiro, mientras que el cubo de la pala
La holgura tuvo cierto impacto en el flujo debajo del cono del riel.
Además, los resultados mostraron que la tensión de Reynolds de la tangencial
La velocidad (en la entrada del tubo de aspiración) se vio influenciada por la presión.
y el lado de succión de la pala del corredor.
El trabajo de Wu et al. (2012) utilizó CFD para analizar el comportamiento del flujo.
a través del conducto de flujo de una turbina Kaplan prototipo y luego la
Los resultados se compararon con una turbina modelo. Algunas discrepancias de presión-
Se observaron fluctuaciones seguras en el tubo de tiro, particularmente a bajas frecuencias.
preguntas que se encontraron asociadas con las diferencias en la
Número de Reynolds. Un estudio reciente de Bozic (2021), una evaluación fue
realizadas en las pérdidas del tubo de tiro del codo de una turbina Kaplan mediante el empleo de
un enfoque contemporáneo. El enfoque principal se centró en estudiar el efecto
de los parámetros del flujo en espiral sobre las pérdidas hidráulicas. Finalmente, un nuevo modelo
Se propuso determinar las pérdidas del tubo de aspiración que deberían ser una
enfoque económicamente viable para la optimización del diseño y el rendimiento
fines de evaluación.
Jonsson et al. (2012) afirmaron que es bastante difícil modelar
el flujo dentro de las turbinas Kaplan con herramientas CFD. Presentaron un Ka-
Planificar el modelo de turbina para condiciones de funcionamiento a carga parcial y a alta carga.
ciones de la turbina. Aquí han realizado una serie de mediciones.
utilizando una configuración experimental y también se ha recomendado el uso de CFD.
herramientas en el diseño y optimización de turbinas. Sus resultados mostraron que la
Las velocidades axiales máximas se han producido por debajo del cono del corredor a alta velocidad.
cargas. Mientras tanto, a cargas parciales, se produjo un nivel significativo de remolino.
baja el cono del corredor y esto creó una ruptura de vórtice helicoidal. Más-
Al terminar, descubrieron que la presión en el núcleo del vórtice podría ser tan baja como...
35 kPa en comparación con la presión ambiente (que ronda los 101 kPa).
Por lo tanto, sería bueno realizar mediciones en tiempo real (en particular
la presión) en los puntos críticos de flujo de las máquinas hidráulicas para garantizar
la funcionalidad adecuada y también para evitar problemas como
cavitación.
Bozic y Benisek (2016) han realizado simulaciones numéricas.
con dos modelos de turbulencia específicos para analizar el perfil y la secundaria
pérdidas de energía de un rotor de turbina Kaplan. Además, han propuesto algunas
modificaciones mediante la introducción de un coeficiente variable en lugar de uno constante
coeficiente, al modelo semiempírico existente de Voytashevski que es
utilizado para determinar las pérdidas secundarias del corredor. Los autores afirmaron
que la metodología propuesta debería ser útil en el diseño y operación
Optimización de la geometría del rotor de la turbina para un mejor rendimiento energético.
matrimonio.
Javadi y Nilsson (2017) simularon una turbina Kaplan U9 bajo
dos condiciones de funcionamiento mediante el empleo de métodos no convencionales y convencionales.
modelos de viscosidad turbulenta tional, y también se han utilizado algunos modelos experimentales.
datos para fines de validación. Afirmaron que todos los mod- de turbulencia
Los els fueron buenos para capturar las estructuras en el campo de flujo, como por ejemplo
vórtices del cubo, el vórtice de la punta, las estelas de las palas y el eje
estructura. Además, los resultados numéricos dieron predicciones precisas sobre la
chorro y también los flujos de fuga de la punta. Con base en las observaciones realizadas,
Los autores sugirieron seguir trabajando en el uso y desarrollo de
Ecuaciones de Navier-Stokes no convencionales no estacionarias promediadas por Reynolds (URANS)
modelos y funciones de pared que son capaces de basarse más en la física
evaluaciones.
El trabajo de Grassmann y Ganis (2005) ha estudiado la posibilidad de
utilizando turbinas Kaplan (con el eje de rotación paralelo al flujo del
agua) en condiciones parcialmente estáticas con el propósito de aumentar
su capacidad de potencia mientras los operan bajo una cabeza más pequeña. En el
modo parcialmente estático, la velocidad del flujo a través de la turbina era
aumentó, y esto provocó un aumento en la velocidad de rotación de la turbina.
bine. Como lo confirman los resultados, la capacidad de generación de energía podría
mejorar en un modo parcialmente estático en comparación con el tradicional.
modo.
Nilsson y Davidson (1999) han utilizado CFD para estudiar la turbulencia
flujo dentro de las turbinas Kaplan. El trabajo se centró principalmente en la limpieza de la punta.
pérdidas de corriente que provocan una reducción de la eficiencia de estas turbinas.
han analizado el rendimiento de un modelo de turbina bajo cuatro condiciones diferentes
condiciones de funcionamiento para diferentes ángulos de las paletas guía. Los resultados indican
cató una estructura vorticial cerca de la holgura de la punta del borde de ataque. Además,
Se encontró que la carga de la punta de la hoja aumentaba con la disminución de
la velocidad específica.
Piratelli-Filho et al. (2009) propusieron enfoques de ingeniería inversa.
y modelado de B-Splines racionales no uniformes (NURBS) para modelar grandes
geometrías complejas como los rotores de turbinas hidráulicas. Reconocen
construyó un rotor de turbina hidráulica Kaplan utilizando las medidas
fabricado con un brazo de medición de coordenadas y algunos algoritmos desarrollados
Optó por ajustar los puntos de datos a curvas y superficies. Luego se creó un modelo CAD.
desarrollado utilizando NURBS y también se realizó un análisis de errores para
verificar el modelo CAD. Una comparación realizada entre el reconstruido
El modelo CAD y el corredor real mostraron desviaciones de solo hasta 5
mm en relación con la geometría y dimensión de la pala. Además,
Están planeando extender el método propuesto a otros tipos de turbinas.
también.
Schiffer et al. (2013) estudiaron experimentalmente el sellado del borde de un
Turbina Kaplan STRAFLO de doble regulación. El objetivo principal de este estudio.
El objetivo era detectar la magnitud de la fuga y la potencia de fricción producida.
por el sistema de sellado de una central hidroeléctrica seleccionada. Además, ellos ob-
Se analizó el comportamiento del sistema de sellado con diversos materiales de sellado.
y parámetros operativos. Además, el efecto de la contaminación por arena.
con el agua se observó y se encontró que la contaminación de arena puede
conducen a aumentar la fuerza de fricción en un factor de 2-3. Finalmente,
propuso un novedoso concepto de enjuague para evitar la entrada de abrasivos
partículas de arena fina en la zona de sellado manteniendo la fuga
y una potencia de fricción a un nivel bastante bajo.
El trabajo de Lipej y Poloni (2000) ha propuesto un enfoque multiobjetivo.
misión para un corredor de Kaplan usando un algoritmo genético. Estrés de Reynolds
Las ecuaciones de Navies-Stokes promediadas se resolvieron utilizando un código informático.
desarrollado en CFX-TASCflow. Los autores afirmaron que la optimización
dio buenos resultados pero el tiempo empleado para resolver el problema debería
se reducirá aún más.
Kaniecki et al. (2011) realizaron un análisis CFD de los flujos a través de
Turbinas Kaplan y semi-Kaplan utilizando NUMECA/Fine y software ANSYS.
paquetes de software. Aquí, los autores destacaron la importancia de la
selección apropiada de algunos parámetros como la precisión de la
representación de la geometría real, una cuadrícula fina con un y + apropiado
valor, un modelo de turbulencia apropiado y una discretización de segundo orden
esquema con al menos 104 iteraciones por proceso para lograr precisión
resultados numéricos. Los resultados numéricos obtenidos fueron validados con
una serie de pruebas de laboratorio en una turbina semi-Kaplan TNS y afirmaciones
que coincidían en gran medida con los hallazgos reportados previamente.
Martínez et al. (2019) han presentado un trabajo interesante centrado en
sobre la caracterización hidráulica y biológica de un sistema Kaplan a gran escala
turbina. La idea principal era desarrollar una caracterización hidráulica de referencia.
ción para las turbinas Kaplan existentes que respaldarían su reemplazo
mento al final de la vida útil prevista. Se realizó un estudio de caso.
En la presa de Ice Harbor en Washington para observar el comportamiento hidráulico.
bajo diferentes configuraciones operativas utilizando un dispositivo sensor autónomo.
Los datos recopilados coincidieron con los de turbinas de tipo similar.
y luego los autores afirman que este enfoque debería ser útil en im-
Implementar mejoras de diseño u operativas en las turbinas Kaplan.
Masood et al. (2021) propusieron un método de sobre- basado en procesos gaussianos.
modelo de puerta mediante el empleo de un enfoque de entrenamiento adaptativo para inferir el
velocidades tangenciales relativas en los bordes delantero y trasero de un Ka-
plan turbina. Luego, este modelo se integró con un optimizador para de-
determinar el subespacio más adecuado para un diseño óptimo y definir
la sensibilidad de los parámetros de diseño. Los resultados confirmaron que el pro-
El enfoque propuesto podría mejorar la eficiencia del diseño inicial mediante una
margen significativo del 56,98% al 90,73%, pero con un margen bastante bajo.
también el costo putativo.
Grekula y Bark (2001) realizaron un trabajo experimental para des-
comprender el fenómeno de cavitación en una turbina modelo Kaplan.
El objetivo principal de su trabajo era reconocer los posibles mecanismos.
que promueven el comportamiento de cavitación erosiva, y también utilizaron alta-
filmación rápida y observaciones visuales con luz estroboscópica para transportar
fuera del estudio. Las observaciones confirmaron que el vórtice cavitante
se dobló hacia la superficie de la hoja y también se transformó en nube.
formaciones.
Shamsuddeen et al. (2020) estudiaron los fenómenos de cavitación de un
Turbina Kaplan en el espacio libre de la punta entre la punta del álabe y la turbina.
carcasa de cubierta cionaria. Los autores probaron una cavi-
modelo numérico de la estación empleando un modelo de turbina 3D (que estaba en
una escala real) sobre cinco condiciones de cámara. Además, una aleta anticavidad
Se propuso un sistema para controlar la cavitación en el lado de succión a lo largo de
la punta de la cuchilla del corredor. Luego, una comparación del rendimiento hidráulico.
y otros parámetros (es decir, fracción de volumen de vapor, carga de la pala)
distribución y flujo de fuga de punta) se llevaron a cabo entre palas con
y sin un sistema de aletas anticavidad. Los resultados mostraron que el sistema anticavidad
El sistema Cavity Fin es una forma eficaz de minimizar la cavitación en-
tensión en el borde de ataque de las palas sin alterar la hidráulica
rendimiento de la turbina. Mientras tanto, Kumar y Saini (2010) han
Se realizó una revisión sobre los fenómenos de cavitación de las turbinas hidráulicas. Algunos
Otros trabajos también se han centrado en el comportamiento de cavitación de Kaplan.
turbinas que se centran en áreas como el monitoreo de cavitación (Shi et al.,
2007), el efecto de la cavitación en el rendimiento (Balint, 2004), y
predicción de cavitación (Nennemann y Vu, 2007).
El trabajo de Sedmak et al. (2022) ha analizado la integridad estructural.
de una cubierta de turbina Kaplan con el objetivo de evaluar la formación de grietas.
comportamientos de fatiga y estrés. Además, Zhang et al. (2020) han
También se estudió la formación y propagación de grietas en las palas de un Ka-
planificar la turbina mediante investigaciones tanto experimentales como numéricas. Luego,
propusieron un modelo numérico para estimar el comportamiento modal de
grandes grietas donde el modelo coincidía bien con el experimento.
resultados mentales. Otro trabajo reciente de Zhang y Chen (2022) ha
Se emplearon enfoques computacionales para estudiar el efecto de la interna
interacciones de las palas sobre la masa añadida y la amortiguación añadida de un prototipo
tipo rotor de turbina Kaplan. Además, el trabajo de Muis (2015) ha demostrado...
centrado en el modelado CFD de turbinas hidráulicas integradas con sistemas eléctricos
generadores mientras que Borkowski et al. (2019) han discutido sobre el diseño
y optimización de turbinas hidráulicas axiales para alturas de caída muy bajas.
Además, otros trabajos reportados en la literatura se han centrado en
en otras áreas relacionadas, como las consideraciones básicas para el aprovechamiento
energía hidroeléctrica (Price y Probert, 1997), turbinas de bombeo (Morabito y
Hendrick, 2019), impacto ambiental debido al establecimiento de energía hidroeléctrica
mentos (Rashad e Ismail, 2000), desafíos en el aprovechamiento de la energía hidroeléctrica
( Ardizzon et al., 2014 ), potencial hidroeléctrico en Egipto ( Salah et al.,
2022), potencial hidroeléctrico en Nigeria (Ogbonnaya et al., 2019) y
los efectos de las instalaciones de energía renovable sobre la economía
desarrollo de una nación (Dasanayaka et al., 2022).
Dado el limitado número de trabajos previos disponibles sobre el diseño
y optimización (tanto en aspectos teóricos como de CFD) de la curva de Kaplan-
combinaciones y también debido a la naturaleza altamente compleja de estas tareas, es
Es importante y oportuno realizar más investigaciones en esta área. Por lo tanto, en
En este estudio, se realizaron cálculos teóricos para diseñar un modelo de Kaplan-Meier.
rueda del rotor de la turbina para un caso de estudio seleccionado y luego el mismo diseño
se implementó en una plataforma CFD y luego se analizó para comparar
Comparar los resultados teóricos y de CFD. A continuación, se optimizó el modelo de CFD.
para lograr la mayor eficiencia de extracción de energía posible, principalmente mediante la operación
sincronizando la geometría de las palas y, por lo tanto, para generar la mayor
posible potencia de salida de la turbina. Una discusión exhaustiva sobre
Todos estos estudios se presentan en las siguientes secciones.
2. Formulación del problema del estudio de caso
Para esta investigación, se utilizó una central hidroeléctrica (con una presa que atraviesa un río).
Se consideró con una turbina Kaplan como se ilustra en la Fig. 14. El principal
Los parámetros seleccionados para el estudio de caso se enumeran a continuación:
Altura (H): 6 m
Caudal volumétrico 𝑉̇ : 5 m^3 .s−^1 (constante)
El coeficiente adimensional 𝜎: - 1,45 (de la Fig. 15)
El rotor de la turbina: tiene álabes fijos.
La altura de succión HS y la altura neta HN (diferencia entre la altura-
El agua y el agua de cola) se definen como se indica en la Fig. 14.
Figura 14. Detalles del estudio de caso.
3. Procedimiento de diseño teórico
Los enfoques clave seguidos para el proceso de diseño teórico fueron:
Junto con los cálculos/suposiciones relevantes, se discuten en este documento.
Sección con detalles relacionados.
3.1. Parámetros de flujo y diseño
Basándose en los valores elegidos para el estudio de caso (presentados en
Sección 2), la velocidad de rotación típica 𝑁 del rotor de la turbina puede
se especificará mediante la ecuación (3) en función de la altura (H) y el caudal volumétrico.
del fluido ( 𝑉̇ ), ( Menny, 2006 ):
𝑁 =
𝜎 ( 2 g )
3/
2
√
𝜋𝑉̇
=
1. 45 ( 2 ×9. 81 ×6 )
3/
2
√
𝜋 5
= 6,538 s−1^ = 392,28 rpm (3)
Una vez que se conoce la velocidad de rotación (N), la velocidad específica relacionada
se puede determinar a partir de la ecuación (4):
𝑁𝑠 =
N
√
V̇
𝐻 3∕^
=
6. 538
√
5
6 3∕^
= 228,78 (4)
El gráfico presentado en la Fig. 15 explica la relación (o requerimiento-
medidas para la compatibilidad) entre el diámetro exterior y el del cubo (interior)
ters de la rueda ( 𝐷𝑁 , 𝐷𝑎 ), el coeficiente adimensional ( 𝜎 ) , el diam-
número de éter ( 𝛿 ), la relación de ( 𝐷𝑁 ∕ 𝐷𝑎 ) y el número de aspas del rodillo
( 𝑧 ′′). Dada esta información, el diámetro exterior del rotor de la turbina
La rueda (𝐷𝑎) debe calcularse a partir de la ecuación (5):
𝐷𝑎 =
2𝛿
√
𝜋
×
4
√
𝑉̇^2
2 g
=
2 × 1. 3
√
𝜋
×
4
√
52
2 ×9. 81 ×
= 0,996 m (5)
Fig. 15. Relaciones entre el coeficiente adimensional 𝜎 y las relaciones de diámetro para una turbina Kaplan (Menny, 2006).
Un número de diámetro (𝛿) de 1,3 y una relación de diámetro (𝐷𝑁/𝐷𝑎) de 0.
están asociados al coeficiente adimensional 𝜎 = 1,45 (que es el 𝜎
valor relacionado con este estudio). Por lo tanto, el diámetro del cubo del corredor ( 𝐷𝑁 )
se puede calcular a partir de la ecuación (6):
𝐷𝑁 = 𝐷𝑎 ×0. 4 = 0,996 ×0. 4 = 0. 398 𝑚 (6)
El número de aspas ( 𝑧 ′′) también está relacionado con 𝜎 y debe ser de-
determinado en base a la Fig. 15. Luego, la cabeza de succión de la central eléctrica
( 𝐻𝑆𝑚𝑎𝑥 ) se define mediante la ecuación (7):
𝐻𝑆𝑚𝑎𝑥 =
𝑝𝑎𝑡𝑚
𝜌𝑔
−
𝑝𝑣
𝜌𝑔
− 𝜎𝑐 𝐻 (7)
𝐻𝑆𝑚𝑎𝑥 =
101300
999 × 9,81
−
1705
999 × 9,81
− 1. 3 ×6 = 2. 363 m
Donde 𝑝𝑣 es la presión de vapor del agua, 𝑝𝑎𝑡𝑚 es la presión atmosférica.
presión, 𝜌 es la densidad del agua y 𝜎𝑐 es el coeficiente de cavitación.
ficient. Por lo general, un valor adecuado para 𝜎𝑐 se determina mediante la prueba del modelo.
experimentos llevados a cabo por los fabricantes de turbinas (PACER, 1995).
De la ecuación (7), se obtuvo una altura de succión (𝐻𝑆𝑚𝑎𝑥) de 2,363 m como el
la mayor altura posible para evitar la cavitación y, por lo tanto, la altura de succión.
( 𝐻𝑆 ) se seleccionó como 2 m para este caso de estudio en particular.
La presión atmosférica depende de la altitud y la temperatura.
temperatura de la ubicación de la central eléctrica, y para este trabajo, se puede
Se supone que es 101.300 Pa. Si el rango de temperatura del agua es
Consideradas entre 0 y 25 °C, las presiones de vapor relevantes son
0,611 kPa y 3,168 kPa, respectivamente. En este estudio, la temperatura del agua...
La temperatura se considera de 15 °C teniendo en cuenta la temperatura máxima de
algunos de los ríos europeos (Jakob, 2010), y por lo tanto la presión de vapor-
seguro debe tomarse como 1,705 kPa ( Rod, 2000 ). Según la ecuación (7), el
La altura máxima de succión debería disminuir a medida que disminuye la temperatura del agua.
aumenta. Como se mencionó anteriormente, el coeficiente de cavitación 𝜎𝑐 debería
se obtienen a partir de los experimentos de prueba de modelos del fabricante de la turbina.
La figura 16 de PACER proporciona la relación entre la cavitación co-
velocidad eficiente y específica ( 𝑁𝑆 ) (obtenida de la ecuación (4) ) para Francis y
Turbinas Kaplan. La velocidad específica 𝑁𝑆 ya se conoce a partir de la ecuación (4) como
228.78. Por lo tanto, para este trabajo, se puede tomar un coeficiente de cavitación 𝜎𝑐 como
1.3.
3.2. Diseño de las palas de la turbina
Como este trabajo implica una descarga constante, no ajustable idéntica
Se eligieron cuchillas para el corredor. Por lo tanto, esas cuchillas pueden ser...
fijado permanentemente al cubo de la turbina ya que no habrá necesidad de
ajustes. Para definir teóricamente la geometría/forma del corredor
En las palas, se desarrollaron varios triángulos de velocidad tanto en la parte posterior como en la posterior.
y bordes de ataque y también en el centro de la hoja en 4 diferentes ra-
Ubicaciones de los diales (𝐷𝑁 , 𝐷 1 , 𝐷 2 , 𝐷 3 , 𝐷 4 , 𝐷𝑎 ) como se indica en la Fig. 17 -(a).
En total, se desarrollaron 15 triángulos de velocidad para definir cada pala.
La figura 17-(b) presenta las vistas en sección transversal de tres palas a una velocidad específica.
diámetro crítico (en un plano recto) donde las notaciones 1, 2 e ∞ indican
las velocidades en la entrada, la salida y el centro de la sección, respectivamente.
Además, 𝑤 es la velocidad relativa, 𝑐 es la velocidad del flujo del fluido y
𝑢 representa la velocidad tangencial. Además, la velocidad relativa meridiana.
La velocidad 𝑤𝑚 genera su propio triángulo de velocidad con el valor promedio-
ues de 𝑤 1 y 𝑤 2 y también con el ángulo 𝛽 ∞. Además, la longitud de la cuerda es
especificado por 𝑠 ′′y 𝑡 ′′, que define el espacio entre las palas, y
Estos parámetros dependen del diámetro de la rueda de rodadura.
también (Flaspöhler, 2007). La sección transversal de una pala a diferentes radios
tendrán diferentes formas de cuerda, velocidades y ángulos.
Los cálculos relacionados con el desarrollo de los triángulos de velocidad
en el medio de las palas del corredor en el diámetro exterior 𝐷𝑎 están pre-
Se indica a continuación. Basado en el diámetro exterior del rotor de la turbina.
rueda (𝐷𝑎) y su velocidad de rotación (N), la magnitud de la tangencial
La velocidad de una pala del rodillo (𝑢) se puede determinar mediante la ecuación (8):
𝑢 = 𝜋𝐷𝑁 = 𝜋 ×0. 996×6. 538 = 20. 452 𝑚.𝑠
−
(8)
La velocidad relativa en la dirección meridiana 𝑤𝑚 depende de
el caudal de descarga y el área del flujo de fluido dentro del rodete, y
Además, esto debería ser idéntico para toda la unidad del corredor. Por lo tanto, la entrada
La velocidad 𝑤 0 también debe ser idéntica a 𝑤𝑚.
𝑤𝑚 = 𝑐 0 =
V̇
A
=
V̇
1
4
𝜋
(
𝐷² 𝑎⁻𝐷𝑁²
)=
5
1
4
𝜋
(
0.996
2
-0,398
2)
= 7,643 m −^
(9)
La velocidad tangencial del flujo ( 𝑐𝑢 ∞) depende de la
la velocidad tangencial de las palas y también la cabeza de la central eléctrica, y
Fig. 16. Diagrama de los coeficientes de cavitación 𝝈𝒄: la línea discontinua denominada 1 corresponde a las bombas, y la línea continua, a las turbinas Francis y Kaplan (PACER, 1995).
Fig. 17. (a) – Esquema que indica los diámetros de la sección transversal de las palas del rotor utilizadas para desarrollar triángulos de velocidad, (b) Esquema que presenta las palas
secciones transversales junto con los triángulos de velocidad correspondientes (Menny, 2006).
Tabla 2
Valores generados por cálculos teóricos en diferentes ubicaciones radiales.
de una hoja.
D a D 1 D 2 D 3 D N Unit
D 0.996 0.846 0.697 0.548 0.398 m
U 20.452 17.384 14.316 11.249 8.181 m/s
c u1 3.271 3.849 4.673 5.948 8.178 m/s
c u2 0.566 0.666 0.809 1.029 1.415 m/s
c u ∞ 1.919 2.257 2.741 3.488 4.797 m/s
w u1 -17.181 -13.536 -9.643 -5.301 -0.003 m/s
w u2 -19.886 -16.718 -13.508 -10.220 -6.766 m/s
w ∞ 20.047 16.948 13.871 10.892 8.359 m/s
w m 7.643 7.643 7.643 7.643 7.643 m/s
w u ∞ -18.533 -15.127 -11.576 -7.760 -3.384 m/s
∆ w u 2.705 3.183 3.865 4.919 6.763 m/s
𝛽 ∞ 157.589 153.195 146.565 135.436 113.883 Degree
A 23.172 26.727 31.444 37.890 46.938 Degree
𝛽 1 156.018 150.549 141.601 124.744 90.020 Degree
𝛽 2 158.976 155.432 150.498 143.208 131.517 Degree
𝑠 ′′
𝑡 ′′ 0.750^ 0.888^ 1.025^ 1.163^ 1.300^ -^
𝑡 ′′ 0.782 0.665 0.547 0.430 0.313 m
𝑠 ′′ 0.587 0.590 0.561 0.500 0.407 m
Esto se puede expresar mediante la ecuación (10) asociada con la velocidad tangencial.
de una cuchilla de corredor y términos de cabeza:
𝑐𝑢 ∞=
(
𝐻 − 𝐻𝑠
)
𝑔
yo
=
( 6 − 2 ) ×9. 81
20. 452
= 1,919 m .𝑠 −1^ (10)
La diferencia entre las velocidades tangenciales ( Δ 𝑤𝑢 ) es dependiente
sobre la cabeza de la planta y la velocidad tangencial del corredor
cuchillas. Aquí, se asumió que el corredor está trabajando a la máxima velocidad.
posible eficiencia que puede lograrse con un rotor de turbina Kaplan,
que se ha reportado como 94% (Dixson, 2005).
Δ 𝑤𝑢 = 𝑤𝑢 1 − 𝑤𝑢 2 =
Hola
yo
=
6 × 9,81 × 0,94
20. 452
= 2,705 m .s
−
(11)
Donde 𝜂𝑒 es la eficiencia de extracción de energía del corredor, 𝑤𝑢 1 es la
velocidad relativa tangencial en el borde de ataque y 𝑤𝑢 2 es la tangencial
velocidad relativa en el borde de salida. Luego, la velocidad relativa a lo largo
La dirección tangencial se puede obtener mediante la ecuación (12):
𝑤𝑢 ∞= 𝑐𝑢 ∞− 𝑢 = 1. 919 − 20. 452 = −18. 533 m .𝑠 −1^ (12)
La velocidad relativa en el centro de la pala del rotor 𝑤 ∞ es pre-
Enviado por:
𝑤 ∞=
√
𝑤^2 𝑢^ ∞+ 𝑤^2 𝑚^ =
√
−18.533 2 +7.643 2 = 20.047 m.s − 1 (13)
El ángulo desarrollado en el centro de la pala del rodillo con el hor-
izontal ( 𝛽 ∞) viene dado por la ecuación (14):
𝛽 ∞= 90 ◦−tan −^
(
nosotros ∞
nosotros
)
= 90 ◦−tan −^
(
−18.533
7. 643
)
= 157. 589 ◦(14)
Por lo general, los corredores con un valor superior a 𝜎 = 1,3 se especifican como corredores rápidos y
Por lo tanto, la rueda de apoyo desarrollada en este estudio de caso puede considerarse
como corredor rápido ya que 𝜎 es igual a 1.45. La rueda del corredor seleccionada para
Este caso de estudio tiene relaciones 𝑠 ′′/ 𝑡 ′′ de 1,3 y 0,75 en el interior y exterior.
diámetros, respectivamente. Por lo tanto, el margen de partición de la hoja 𝑡'' es
dada por la ecuación (15):
𝑡
"
=
𝜋𝐷
𝑧 ′′
=
𝜋 ×0.996
4
= 0,782 (15)
De esta forma, se puede obtener la longitud de la cuerda 𝑠 ′′:
𝑠 ′′= 0,75 𝑡 ′′= 0,75 ×0,782 = 0,587 𝑚
Para diseñar las palas del rodillo, se desarrollaron todos los triángulos de velocidad relacionados.
Opté con el mismo enfoque discutido anteriormente y todos los correspondientes
Los valores se enumeran en la Tabla 2. La exactitud de los cálculos teóricos
Los valores presentados en la Tabla 2 se pueden evaluar simplemente calculando el
eficiencias esperadas y resultantes de la rueda de rodadura. Como se consideró
En los cálculos teóricos, se determinó la eficiencia esperada 𝜂𝑒 del corredor.
La rueda es del 94%. Con fines comparativos, la eficiencia de la
El corredor se puede determinar con la potencia de salida real y la proporcionada.
valores del corredor. La energía liberada por una masa de agua en caída libre de
La masa, m, sobre una altura H, viene dada por mgH, y entonces esto puede ser con-
se convierte en 𝜌VgH ya que la masa (m) viene dada por el producto del volumen (V).
y densidad ( 𝜌 ). En consecuencia, esto puede modificarse para determinar la
potencia entregada por el agua que fluye a la rueda motriz según lo indicado por
Ecuación (16):
𝑃𝑤𝑎𝑡𝑒𝑟 = 𝜌𝑔𝐻𝑉̇ = 999 × 9.81 × 6 × 5 = 294005.7W (16)
Luego, a partir de los valores enumerados en la Tabla 2 y la fórmula de Euler pre-
En la ecuación (1), se expresa la potencia teórica real generada por el rotor.
Se puede determinar la rueda:
𝑃𝑟𝑢𝑛𝑛𝑒𝑟 = 𝑚̇
(
𝑢 1 𝑐𝑢 1 − 𝑢 2 𝑐𝑢 2
)
= 𝑚̇ 𝑢 Δ 𝑤𝑢 (17)
𝑚̇ = ρ 𝐴𝑐 0 = 𝛿
1
4
𝜋
(
𝐷^2 𝑎^ − 𝐷^2 𝑁^
)
𝑐 0 (18)
𝑃𝑟𝑢𝑛𝑛𝑒𝑟 = ρ
1
4
𝜋
(
𝐷^2 𝑎^ − 𝐷^2 𝑁^
)
𝑐 0 𝑢 Δ 𝑤𝑢
𝑃𝑟𝑢𝑛𝑛𝑒𝑟 = 999 ×
1
4
𝜋
(
0,99582 −0,39832
)
×7,64 ×14,316 ×3,865
= 276365. 36 W
Ahora bien, la eficiencia teórica se define como:
𝜂𝑟 =
𝑃𝑟𝑢𝑛𝑛𝑒𝑟
𝑃𝑤𝑎𝑡𝑒𝑟
× 100% = 94% (19)
Esto confirma la exactitud de los cálculos teóricos y también
Esto se evaluará nuevamente comparando los resultados teóricos con
Dinámica de fluidos computacional (CFD) mediante el análisis del mismo diseño dentro de una plataforma CFD.
3.3. Traslación de coordenadas
Cabe mencionar que solo los triángulos de velocidad en sí mismos son
no es suficiente para definir la forma geométrica de las palas del riel.
Como propusieron Janjua et al. (2013), una traducción de los valores
presentado en la Tabla 2 a un sistema de coordenadas 3D debería ser necesario para
Desarrollar un modelo 3D preciso para su uso en un análisis CFD. Figura 18
Ilustra el sistema de coordenadas 3D desarrollado para el corredor. Puntos rojos
indican 15 coordenadas que fueron trasladadas para definir la hoja de-
signo. La información presentada en cada fila de la Tabla 2 está relacionada con el
triángulos de velocidad de estas 15 coordenadas. Aquí, las notaciones 1, ∞ y
2 están relacionadas con las coordenadas de la entrada de la pala, la posición media y
salida, respectivamente.
Los cálculos relativos a la traslación de las velocidades, el
longitudes de cuerda y sus ángulos relacionados en coordenadas cartesianas
se presentan a continuación. Para definir la traducción de coord-
nate apunta en la dirección y, la mitad de la longitud de la cuerda 𝑠 ′′(proporcionado en
La tabla 2) debe definirse mediante los ángulos 𝛽 ∞, 𝛽 1 y 𝛽 2 (véase la figura 18).
𝑦 1 = 𝑠𝑖𝑛
(
𝛽 1 − 90
)Dsin^
(
𝑠 ′′
D
×
180°
𝜋
)
2cos
(
𝛽 ∞− 𝛽 1
)
= 𝑠𝑖𝑛 ( 156. 018 − 90 )
0,996 × seno
(
0.587
0.996
×
180°
𝜋
)
2 ×cos ( 157. 589 − 156. 018 )
= 253,833 mm (20)
𝑦 2 = 𝑠𝑖𝑛
(
𝛽 2 − 90
)Dsin^
(
𝑠 ′′
D
×
180°
𝜋
)
2cos
(
𝛽 2 − 𝛽 ∞
)
= 𝑠𝑖𝑛 ( 158. 976 − 90 )
0,996 × seno
(
0.587
0.996
×
180°
𝜋
)
2 ×cos ( 158. 976 − 157. 589 )
= −258. 280 mm (21)
Además, el ángulo 𝛽 1 en la dirección y debe definirse para definir
Las coordenadas apuntan en la dirección z. Por lo tanto, con referencia a
Figura 18. Esquema que muestra el proceso de traslación de coordenadas de la rueda de rodadura: izquierda – vista frontal, derecha – vista superior.
Las tangentes relacionadas, la traslación se puede describir mediante las ecuaciones (22).
y (23):
𝑧 1 =
y 1
𝑡𝑎𝑛
(
𝛽 1 − 90
)=
253.833
𝑡𝑎𝑛 ( 156. 018 − 90 )
= 112,474 mm (22)
𝑧 2 =
y 2
𝑡𝑎𝑛
(
𝛽 2 − 90
)=
−258. 280
𝑡𝑎𝑛 ( 158. 976 − 90 )
= −99,266 mm (23)
La traslación en la dirección 𝑥 se puede definir restando el arco
aumento como se presenta en la ecuación (24):
𝑥 1 =
D
2
− 𝐷𝑠𝑖𝑛
⎛
⎜
⎜
⎜
⎝
arcoseno
(
2 años
D
)
2
⎞
⎟
⎟
⎟
⎠
2
=
0.996
2
− 0,996 × 𝑠𝑖𝑛
⎛
⎜
⎜
⎜
⎝
arcoseno
(
2×253.833
0.996
)
2
⎞
⎟
⎟
⎟
⎠
2
= 428,927 mm (24)
Las coordenadas trasladadas recién calculadas se presentan en la Tabla 3.
Además, los valores de las coordenadas relacionados con 𝑦 y 𝑧 en el medio de la
Las cuchillas son iguales a cero, ya que esos son los valores iniciales para definir el
forma geométrica y por lo tanto se colocaron exactamente en el eje x. Algunos de
los detalles relacionados con la tecnología hidroeléctrica y el diseño de turbinas
se puede encontrar en la literatura (Nawar, 2016).
3.4. Desarrollo del modelo CAD 3D
Con base en los detalles presentados en la Tabla 3 y el diámetro calculado
valores de eter, se puede definir la forma/geometría de las palas del corredor.
con precisión. Por lo tanto, se desarrolló un modelo 3D en Solid Edge 3D CAD.
Tabla 3
Las coordenadas trasladadas en diferentes ubicaciones radiales.
D a D 1 D 2 D 3 D N Unit
x 1 428.927 350.746 287.075 243.297 199.159 mm
y 1 252.833 236.827 197.637 125.686 0.064 mm
z 1 112.474 133.724 156.642 181.218 185.685 mm
x∞ 497.899 423.214 348.529 273.844 199.159 mm
y ∞ 0.000 0.000 0.000 0.000 0.000 mm
z ∞ 0.000 0.000 0.000 0.000 0.000 mm
x 2 425.670 343.460 270.985 210.505 160.360 mm
y 2 -258.280 -247.276 -219.179 -175.153 -118.106 mm
z 2 -99.266 -113.044 -124.014 -130.992 -133.417 mm
software y se muestra en la Fig. 19-a. Los puntos rojos mostrados en el modelo
son los puntos de coordenadas calculados en la entrada, el medio y la salida de
las cuchillas. Después de definir las coordenadas, la forma geométrica de las
Las cuchillas se desarrollaron uniendo estas 15 coordenadas (es decir, coordenadas
en 1, ∞ y 2) con la ayuda de la herramienta modelador de caras en Solid Edge.
No fue posible utilizar una forma de perfil aerodinámico debido a la geometría retorcida.
de las palas. La sección transversal de las cuerdas varía significativamente de
diámetros interior a exterior y, por lo tanto, las palas del rodillo de 4 mm uniformes
Se desarrollaron espesores. En este estudio, no se espera analizar
la estructura mecánica o sección transversal de las palas, y se centra en
únicamente para estudiar el comportamiento del flujo de fluido resultante debido a la geometría
forma de las aspas del riel.
3.5. Desarrollo de los álabes guía
Después de diseñar las palas del rodete, se diseñaron las paletas guía del rodete.
también se desarrolló basándose en el mismo enfoque seguido para diseñar el
Fig. 19. Imágenes de los modelos 3D: (a) rueda de rodadura, (b) rueda de rodadura con las paletas guía.
Tabla 4
Las coordenadas calculadas teóricamente para las paletas guía.
D a D 1 D 2 D 3 D N Unit
X 481.444 399.629 316.306 231.756 147.601 mm
Y 126.945 139.307 146.366 145.877 133.710 mm
Z 296.590 276.653 239.376 187.452 124.958 mm
𝑠 ′′ 0.323 0.310 0.281 0.238 0.183 mm
las palas (discutidas en la Sección 3.3.), y las coordenadas calculadas y
Otros valores relacionados se proporcionan en la Tabla 4 (PACER, 1995). El flujo
de agua entra axialmente con una velocidad 𝑐 0 hacia los álabes guía y luego
golpea las palas a una velocidad 𝑐 1 y en un ángulo 𝛽 1 como se ilustró en
Figura 10. Como se mencionó, la velocidad de entrada del fluido 𝑐 1 y la relacionada
El ángulo de entrada 𝛽 1 a las palas del corredor es el mismo que el de salida del fluido.
Sea la velocidad 𝑐 1 y el ángulo de salida relacionado 𝛽 1 de las paletas guía.
Luego, el diseño final de la rueda de rodadura con aspas y paletas guía.
se muestra en la Fig. 19 -(b). En este diseño, los bordes de todas las palas del corredor
Fueron diseñados para tener una forma redonda, como se muestra en la Fig. 19.
4. Análisis CFD
Después de completar el diseño teórico del corredor, el teor-
El corredor diseñado específicamente se implementó con el disponible comercialmente.
Software ANSYS FLUENT (con las mismas características) para fur-
otras evaluaciones y también para una posible optimización de la teoría
diseño.
4.1. Condiciones del solucionador CFD
Para el análisis CFD, el flujo de fluido dentro de la sección de la turbina debe
ser definido con las condiciones de contorno apropiadas. El modelo 3D de
El corredor que se desarrolló con Solid Edge se importó posteriormente a
el software ANSYS. La figura 20 presenta el modelo 3D en ANSYS con su
malla desarrollada para realizar el análisis CFD. Para el estudio CFD, la
La rueda de apoyo está centrada dentro del tubo de tiro cilíndrico de 2 m de longitud como
ilustrado en la Fig. 10. El cuerpo del fluido contiene dos cuerpos separados.
ies: el fluido interior que encierra la geometría giratoria (es decir, el
corredor) y el fluido exterior que cubre la geometría estática. El final
La malla contiene más de 750.000 celdas/elementos tetraédricos. Tetrahe-
Los elementos de malla dral serían adecuados para un modelado preciso y también
para lograr una alta relación ortogonal, una baja relación de aspecto y también una baja
coeficiente de asimetría. El coeficiente de asimetría es un tipo de coeficiente de comparación entre...
entre las células reales y óptimas (triangulares equiláteras) (Choi et al.,
2013). Después de asegurar la precisión de la malla, se establecen los ajustes adecuados.
(por ejemplo, área de salida, área de entrada, eje de rotación, dirección del flujo, densidad y
temperatura del agua, velocidad y área del movimiento de la malla, solucionador preferido,
etc.) deben seleccionarse. El flujo de agua entra en la turbina con una entrada.
Deje una velocidad de 7,643 ms−^1 ( 𝑐 0 ) y luego salga por la salida de la turbina.
El agua dentro de la sección del rodillo gira en sentido contrario a las agujas del reloj.
el eje Z con una velocidad de rotación de 392,25 rpm. Para este caso de estudio,
Para la simulación CFD se empleó un solucionador con ecuaciones k-epsilon laminares.
análisis.
4.2. Desafíos/Limitaciones asociados al análisis CFD
Después de realizar los primeros conjuntos de pruebas en ANSYS, algunos límites...
Se encontraron iteraciones y estas deberían tener algún tipo de impacto.
en la tarea de optimización del diseño planificada. Una de las preocupaciones era que
ANSYS presenta cierto tipo de limitaciones en la visualización de los resultados asociados.
asociado con objetos sólidos en movimiento (como la rueda de apoyo en este
estudio). Una de las posibles soluciones es que la creación de un cilindro-
der alrededor/cubriendo el objeto sólido en movimiento (la rueda de rodadura) y
luego restando el objeto sólido del volumen del cilindro, entonces
que solo queda el cuerpo de fluido (ANSYS, 2015). Entonces, el volumen de
El cuerpo fluido que rodea al corredor puede describirse como un cuerpo interior.
de fluido que podría rotar durante la resolución/modelado
proceso (como se muestra en la Fig. 20). Dada esta limitación, el flujo de fluido debe ser...
El comportamiento que incorpora turbulencias y líneas de corriente difícilmente puede ser anal-
ysed. Styrylski et al. (2008) y Kaniecki et al. (2011) también han informado
sobre el mismo desafío/limitación y utilizaron ANSYS para diseñar y
Optimizar turbinas hidroeléctricas. Trabajo presentado por la Universidad Técnica.
La ciudad de Graz (Instituto de Maquinaria de Fluidos Hidráulicos, 2012) también ha utilizado
el mismo enfoque (descrito justo arriba en esta sección) para la optimización
sación de una turbina Kaplan, y sus resultados experimentales y de CFD han sido
Presentaba solo ligeras discrepancias. Líneas de flujo dentro de la sección del corredor
Los detalles de su modelo de turbina Kaplan se muestran en la Fig. 21.
Por lo tanto, para este estudio también se siguió el mismo método que Tech-
Se empleó la Universidad Nacional de Graz. Además, la precisión de
Los resultados podrían deteriorarse a medida que disminuye el espacio entre el corredor.
La rueda y el cilindro estirado se están haciendo más grandes. Sin embargo, ajustado
Las holguras entre la rueda del corredor y el cilindro podrían afectar la
calidad de la malla y por lo tanto puede influir en la precisión de la
resultados de CFD. Por lo tanto, se emplearon los ajustes apropiados como
fue sugerido por las directrices de ANSYS (ANSYS, 2015). Además,
Ferziger et al. (2019) han presentado enfoques computacionales para fluidos
Figura 20. Modelo CAD 3D de la rueda del rotor de la turbina y los álabes directores (izquierda), modelo 3D mallado en ANSYS (derecha).
Figura 21. Líneas de corriente de velocidad a través del Ka-
Modelo CFD de turbina planificado informado por Tech-
Universidad Nacional de Graz (Instituto de Hidráulica)
Maquinaria de fluidos, 2012).
dinámica mientras que Abeykoon (2020) ha presentado más detalles sobre CFD
Modelado con ANSYS, y puede consultarse para obtener más detalles.
4.3. Análisis del diseño teórico en CFD
Primero, se implementó el diseño teórico de la rueda de rodadura.
con CFD con las mismas dimensiones exactas y luego analizado. El relacionado
Los detalles se presentan en esta sección.
4.3.1. Comportamiento del flujo a lo largo del corredor
Los patrones de flujo generados por ANSYS Fluent con la inicial
El modelo CFD se ilustra en la Fig. 22. Las dimensiones de este ANSYS
Los modelos son exactamente iguales al modelo teórico presentado anteriormente.
mente en la Sección 3. Las líneas de corriente de diferentes colores demuestran la ve-
Magnitudes de la ubicación del agua que fluye (como se indica en el mapa de colores)
a la izquierda) y es evidente que el agua contiene en el flujo giratorio-
La sección ner muestra las mayores magnitudes de velocidad. Como lo indica el
Mapa codificado por colores a la izquierda, la velocidad ha alcanzado un máximo de
22,66 ms−^1. Además, es evidente que existen limitaciones en el software ANSYS.
(descrito en la Sección 4.2) han causado algunas complicaciones en la visualización-
las líneas de corriente generadas a través del cuerpo de fluido interior alrededor del
corredor. A medida que el agua entra en la parte giratoria del cuerpo de fluido, ANSYS
visualiza las líneas de corriente con movimiento rotacional en una posición estática con
no hay rotación. Por lo tanto, el movimiento de rotación real del fluido no puede
estar representado en una imagen. Para mayor claridad, la línea discontinua morada
representa una posible naturaleza de la línea de corriente a través del cilindro de fluido interior.
si pudiera visualizarse con su movimiento de rotación a 392 rpm.
Justo después de salir de la sección del corredor, las líneas de corriente deberían llegar a la salida.
con una delgada rotación en sentido contrario a las agujas del reloj (que puede cuantificarse mediante tan-
velocidad gravitacional 𝑐𝑢 ). Esto indica que el corredor no puede extraer
la máxima energía posible (que está asociada con la tangencial)
velocidad también) transportada por el agua que fluye.
4.3.2. Velocidad tangencial
La velocidad tangencial 𝑢 define la velocidad del agua que fluye en
la dirección de rotación de las palas del rotor, donde 𝑐𝑢 1 y 𝑐𝑢 2 son las
velocidades del agua que fluye en la entrada y salida de las palas, re-
respectivamente. Con el propósito de medir estas velocidades, se utilizaron tres sistemas separados.
Los planos se crearon dentro de la plataforma CFD como se ilustra en la Fig. 23.
(en la entrada del corredor, en el medio y también en la salida). La medida-
Los planos de seguridad en las ubicaciones de entrada/salida se crearon de forma circular como
lo más cerca posible de los bordes de las cuchillas debido a las limitaciones de la
geometrías que se pueden seleccionar para planos de medición. Con ANSYS,
Estos planos solo pueden insertarse como planos de forma uniforme y, por lo tanto,
no se extenderían a lo largo de todos los bordes curvos de las hojas y, por lo tanto,
Esto podría afectar ligeramente la precisión de los resultados. Luego, el informe
Se utilizó la herramienta de ANSYS (que emplea integrales de superficie) para registrar el promedio.
resultados ponderados de velocidades tangenciales en las tres mediciones
Los planos y los valores correspondientes se proporcionan en la Tabla 5.
Luego, la diferencia entre la velocidad tangencial de entrada y salida-
Los lazos se pueden obtener de la ecuación (25).
Δ 𝑤𝑢 = Δ 𝑐𝑢 = 𝑐𝑢 1 − 𝑐𝑢 2 = 2. 161 − 0. 988 = 1. 173 𝑚 ∕ 𝑠 (25)
Obviamente, la potencia de salida de una rueda de rodadura depende de la
diferencia de velocidad tangencial y esto se discutirá en la Sección 4.3.
La figura 24 muestra un mapa de colores de la magnitud de la velocidad tangencial.
distribución a lo largo del corredor. Como es evidente, la velocidad tangencial más alta
se puede observar sobre el diámetro exterior de las palas con una magnitud
de 20,45 ms−^1 y este valor es idéntico al calculado teóricamente
valor presentado en la Tabla 2.
4.3.3. Distribución de la presión a lo largo del corredor
A medida que el agua fluye sobre el rodillo, la presión del agua debería
pueden variar a lo largo de la superficie de las palas. La figura 25 proporciona una ilustración.
de la distribución de presión a través del rotor de la turbina que gira a una velocidad
velocidad de 392 rpm.
Como se puede apreciar en la Fig. 25, la magnitud de la presión es mayor en
las superficies superiores de las palas que las superficies inferiores.
La presión más alta (color rojo) se ha producido hacia el exterior.
bordes de las cuchillas (en las superficies superiores) mientras que la parte inferior (color azul)
está alrededor de los bordes de ataque exteriores en la parte inferior. Como se explicó
Tabla 5
Las velocidades tangenciales medidas en las diferentes ubicaciones radiales de
las cuchillas.
D a D 1 D 2 D 3 D N Average Unit
c u1 2.161 3.060 3.924 5.111 6.863 4.144 m/s
c u2 0.988 1.583 1.967 2.571 2.945 2.048 m/s
w m 7.694 7.694 7.694 7.694 7.694 4.694 m/s
∆ w u 1.173 1.477 1.957 2.540 3.918 2.096 m/s
Figura 22. Líneas de corriente de velocidad (unidades: m/s)
a través del corredor implementado en ANSYS con
las mismas dimensiones teóricas.
Figura 23. Planos de medición creados en ANSYS para medir las velocidades tangenciales del agua a lo largo del corredor.
Según PACER (1995), los bordes en la entrada con una presión baja están en alta
riesgo de exposición a la cavitación debido a las posibles presiones negativas
(que es de alrededor de -63,8 kPa para este trabajo).
Como sugirió RDT (2014), el nivel máximo de presión oc-
curvas cuando la rueda del corredor está en condiciones estáticas (es decir, a 0 rpm).
La figura 26 representa la distribución de presión a través de las superficies superiores de la
El motor gira a 0 rpm y los resultados coinciden con las afirmaciones realizadas.
por RDT (2014). Como se muestra en la Fig. 26, en condiciones estáticas, el máximo
La presión ha subido a 372 kPa (desde 159 kPa) y también la presión
La distribución en las superficies de las palas es diferente a la del rodillo móvil.
(como se muestra en la Fig. 25). Una mayor porción de las superficies del corredor
Las cuchillas están a alta presión sin rotación (color rojo) mientras que una pequeña
Figura 24. Distribución de la velocidad tangencial (unidades
–m/s) a través del corredor en ANSYS.
Figura 25. Distribución de presión (unidades - Pa) a través del rodete (velocidad de rotación -392 rpm): superficies superiores (izquierda) y superficies inferiores (derecha).
Figura 26. Distribución de presión (unidades: Pa)
a través de la rueda del corredor a 0 rpm en ANSYS.
Figura 27. Planos de medición creados para observar la caída de presión a través del corredor (en ANSYS).
Tabla 6
Detalles que indican la caída de presión a lo largo del corredor.
Plane 1 Plane 2 Difference Unit
Pressure 115839.27 93601.19 22238.08 Pa
una porción de las áreas en los bordes de las palas está a la presión más baja.
condiciones (color azul/verde). Mientras tanto, un área bastante pequeña de tamaño mediano
También se puede observar una región de presión entre alta y baja presión.
regiones (zonas amarillas/naranjas en la Fig. 26). Para observar claramente la presencia-
caída segura a través de la rueda del corredor, otros dos planos de medición adicionales
También se crearon en ANSYS justo encima y debajo del corredor, como se muestra.
en la figura 27.
A partir de los contornos de color, se puede determinar el comportamiento de la caída de presión.
analizado. Aquí también se utilizó la herramienta de informes de ANSYS (con integrales de superficie).
utilizado para registrar las magnitudes promedio ponderadas de las diferencias de presión.
encia a través de los dos planos de medición, y los valores relacionados son pre-
presentado en la Tabla 6.
Una vez conocida la diferencia de presión, se puede calcular la fuerza axial del corredor.
puede determinarse a partir de la ecuación (26) basándose en el trabajo previo informado
por Szymczyk (2008).
𝐹𝑎𝑥𝑖𝑎𝑙 = 𝐴
(
𝑝 1 − 𝑝 2
)
=
1
4
𝜋
(
𝐷𝑎^2 − 𝐷𝑁^2
)(
𝑝 1 − 𝑝 2
)
(26)
𝐹𝑎𝑥𝑖𝑎𝑙 =
1
4
𝜋
(
0, 9958
2
-0,3983
2)
( 22238. 08 ) = 14548. 53 𝑁
4.3.4. Capacidad de generación de energía y eficiencia del rotor
Por lo general, la potencia de salida define la posible generación de energía.
pasividad de una rueda de rodadura basada en la energía extraída del flujo
agua. A partir de la ecuación (18), la potencia de salida se puede calcular en función de la
diferencia de las velocidades tangenciales.
𝑃𝑟𝑢𝑛𝑛𝑒𝑟 = 𝜌
1
4
𝜋
(
𝐷^2 𝑎^ − 𝐷^2 𝑁^
)
𝑐 0 𝑢 Δ 𝑤𝑢
𝑃𝑟𝑢𝑛𝑛𝑒𝑟 = 999 ×
1
4
𝜋
(
0,99582 −0,39832
)
×7,64 ×14,316 ×2,096
= 149883. 2 W
Según la ecuación (16), la potencia proporcionada por el agua fue calculada.
calculado como 294005,7 W. Por lo tanto, la eficiencia de la rueda de apoyo es
Tabla 7
Cambios en los parámetros clave a medida que se incrementó el número de palas.
De 3 a 7.
3 Blades 4 Blades 5 Blades 6 Blades 7 Blades Unit
c u1 4.122 4.14362 4.283 4.203 4.167 m/s
cu2 2.813 2.04766 1.712 1.563 1.569 m/s
∆ w u 1.309 2.09596 2.571 2.64 2.598 m/s
P runner 93607.3 149883.2 183853.6 188787.8 185784.4 W
𝜂 r 31.84 50.98 62.53 64.21 63.19 %
analizado en CFD (con las mismas dimensiones teóricas) puede ser
calculado mediante la ecuación (19).
𝜂𝑟 =
𝑃𝑟𝑢𝑛𝑛𝑒𝑟
𝑃𝑤𝑎𝑡𝑒𝑟
× 100% =
149883. 2
294005. 7
× 100% = 50,98%
Por lo tanto, está claro que el modelo CFD del corredor indica solo
una eficiencia de extracción de energía del 50,98% mientras que el diseño teórico
arrojó una eficiencia del 94% para el mismo diseño. Por lo tanto, el CFD
El modelo indica condiciones un 43,02% menos eficientes que las teóricas.
diseño. De hecho, los resultados de CFD deberían ser más realistas que los teóricos.
Los cálculos están asociados a una serie de supuestos simplificadores.
4.4. Optimización del diseño de las palas del rotor mediante CFD
Como se presentó en la sección anterior, el modelo CFD creado con
Las mismas dimensiones exactas que el diseño teórico dieron como resultado una eficiencia
del 50,98%, lo cual es una eficiencia bastante baja. Por lo tanto, una optimización del diseño
El ejercicio debería ser invaluable para mejorar la eficiencia de extracción de energía.
mejorar la eficiencia de la rueda de apoyo modificando el diseño/forma de las aspas.
4.4.1. Selección del número de aspas de rodadura
Inicialmente, se intentó mejorar la eficiencia del sistema.
corredor diseñado teóricamente variando el número de aspas. El teo-
Los cálculos reticulares (discutidos en la Sección 3.2) se realizaron con cuatro
palas. Aquí, se utilizó ANSYS para analizar las variaciones de la tangencial
velocidades en la entrada 𝑐𝑢 1 y la salida 𝑐𝑢 2 de la rueda del corredor como el num-
El número de aspas se incrementó de 3 a 7. Luego, la potencia de salida del corredor
y la eficiencia se puede determinar en función de la velocidad tangencial.
diferencia siguiendo el mismo método presentado en la Sección 4.3.4. Como
estaba analizando el efecto del número de aspas, la velocidad tangencial
de las palas 𝑢 y el caudal másico del agua 𝑚̇ se mantuvieron iguales,
Figura 28. Modelo CAD 3D de una rueda de rodadura con 7 aspas.
y los valores registrados para cada configuración de diseño con los diferentes
El número de aspas se indica en la Tabla 7. A partir de los detalles proporcionados en la Tabla 7,
La eficiencia máxima del 64,21% se registró con 6 aspas. Nunca-
Sin embargo, como lo informó Menny (2006), la eficiencia más alta posible
Normalmente, esto debería lograrse con 4 aspas. La figura 28 muestra un modelo 3D.
del corredor con 7 aspas. Con 7 aspas, los espacios entre las aspas son
bastante ajustado y por lo tanto esto podría causar algunos problemas al fijar las cuchillas
en el eje del corredor.
4.4.2. Velocidad de entrada
Los efectos de la velocidad de entrada de agua 𝑐 0 (al tubo de aspiración) sobre el
También se analizaron las diferencias de velocidad tangencial. Por lo general, la velocidad de entrada...
La localización del agua cambia con la variación del caudal másico. Para
En este trabajo, el tubo de tiro tiene un diámetro constante y por lo tanto la entrada
Se debe aumentar la velocidad para incrementar el caudal másico a través del
sección de turbina. Como se presentó en la Sección 3.2, el cálculo teórico-
La velocidad de entrada relacionada 𝑐 0 es 7,643 m/s. En ANSYS Fluent, la velocidad de entrada
del flujo de agua puede ser alterado y luego sus efectos sobre la tangente-
Se puede estudiar la diferencia de velocidad tangencial. La figura 29 ilustra la tangencial.
velocidades en la entrada del álabe 𝑐𝑢 1 , salida 𝑐𝑢 2 y la diferencia entre
velocidades tangenciales de entrada y salida Δ 𝑤𝑢 , con las variaciones de la entrada
velocidad 𝑐 0. Como es evidente, la velocidad de entrada tangencial disminuye únicamente
marginalmente con el aumento de la velocidad de entrada, mientras que la velocidad de salida-
La idad disminuye considerablemente. En consecuencia, la velocidad tangencial
La diferencia Δ 𝑤𝑢 también debería aumentar con el incremento de la entrada.
velocidad.
La figura 30 representa el aumento resultante de la potencia de salida con
el aumento de la velocidad de entrada 𝑐 0 de 6,5 a 9,5 m/s. La potencia de salida-
Los valores de entrada se calcularon siguiendo el mismo principio presentado.
en la Sección 4.3.4. Luego, la Fig. 31 presenta la mejora de eficiencia relacionada.
mentos del corredor con los cambios en la velocidad de entrada 𝑐 0. Como es
Es evidente que la rueda de apoyo ha alcanzado la máxima eficiencia de alrededor de
51,5%, a una velocidad de entrada entre 7,64 y 8 ms−^1.
indica que la eficiencia de extracción de energía de la rueda de rodadura puede
no se puede mejorar a un buen nivel solo cambiando la velocidad de entrada del agua
al tubo de tiro.
4.4.3. Ángulos de las palas
Obviamente, la geometría del corredor, como el diseño de la pala.
También debe optimizarse para lograr el mejor rendimiento posible.
( Janjua et al., 2013 ). Por lo tanto, el diseño de las palas también es con-
considerado mediante el análisis de la entrada y salida diseñadas teóricamente
gles (𝛽 1 y 𝛽 2) en la capacidad de generación de energía. Como se afirmó por
Styrylski et al. (2008), se desarrolla un alto nivel de presión en la parte superior.
superficie de las palas del corredor (en su dirección de rotación) en comparación con
las superficies inferiores. La diferencia de presión entre la parte superior e inferior.
Las superficies deben afectar el movimiento de rotación del corredor y por lo tanto su
también la capacidad de generación de energía. Además, las fluctuaciones de presión pueden influir.
por lo tanto, la eficiencia general del corredor. La figura 32 representa el típico
Distribución de la presión a lo largo del rodete, tal como se simuló con ANSYS.
Las zonas con mayor presión están representadas por el color rojo.
mientras que el color azul está relacionado con las áreas con la presión más baja.
Las posiciones marcadas del 1 al 5 en la Fig. 32 indican algunas áreas problemáticas en
términos del funcionamiento eficiente del corredor. La posición 1 representa
un área naranja en la parte inferior de la superficie de una cuchilla (una alta presión)
región) mientras que la posición 2 indica un área de baja presión (con amarillo-
color bajo) en la superficie superior de una hoja. Como se mencionó, el deseado
El funcionamiento normal consiste en tener una alta presión distribuida homogéneamente.
sobre las superficies superiores de las palas del rodillo mientras que una distribución homogénea
ejerció una presión menor (en comparación con las superficies superiores) en la parte inferior.
superficies de las palas. Para lograr esto, el ángulo de entrada interior 𝛽 1 debe
debe seleccionarse cuidadosamente. Además, la posición 3 indica un área de
Figura 29. Velocidades tangenciales en la pala en-
Sea 𝒄 (^) 𝒖 1 , la salida 𝒄 (^) 𝒖 2 y la
diferencia de velocidad tangencial Δ 𝒘 (^) 𝒖 a diferentes velocidades de entrada Co.

Figura 30. Potencia producida por el rotor a diferentes velocidades de entrada Co.
Figura 31. Eficiencia de la rueda del rodillo a diferentes velocidades de entrada Co.
Figura 32. Distribución de presión (unidades: Pa)
a través del corredor en ANSYS (las dimensiones son
exactamente igual que el diseño teórico).
Tabla 8
Modificaciones en los parámetros clave relacionados con el rendimiento del rodillo mediante la optimización de la forma de las palas.
Mod.1 Mod.2 Mod.3 Mod.4 Mod.5 Mod.6 Mod.7 Mod.8 Mod.9 Unit
c u1 4.215 4.006 3.979 3.981 4.104 4.191 4.351 4.241 4.286 m/s
cu2 2.018 0.975 0.533 0.768 0.545 0.539 0.527 0.577 0.581 m/s
∆ w u 2.197 3.031 3.446 3.213 3.559 3.652 3.824 3.664 3.705 m/s
P runner 160250.8 216748.4 246425.3 229763.3 254506.0 261156.5 273456.3 262014.6 264946.5 W
𝜂 r 54.51 73.72 83.82 78.15 86.56 88.83 93.01 89.12 90.12 %
baja presión alrededor del borde interior de entrada de una pala, mientras que el exterior
un fragmento del borde de entrada de la misma pala indicó una diferencia significativa
alta presión (marcada por la posición 4). Por lo tanto, el ángulo de entrada desde
Los bordes de entrada interior y exterior deben ajustarse cuidadosamente para lograr un
distribución de presión deseada a través del corredor. Mientras tanto, posi-
La figura 5 muestra un área de presión negativa que, por lo tanto, se encuentra a una presión alta.
riesgo de cavitación.
Para este estudio, la optimización de la forma geométrica de las palas
se realizó en ANSYS bajo 9 pasos de modificación y el resultado-
cambios en los parámetros clave relacionados con el rendimiento del corredor
En la Tabla 8 se presentan todas las modificaciones realizadas al CAD 3D original.
modelo (diseñado con las mismas dimensiones que el diseño teórico)
se realizaron en Solid Edge y luego se reevaluaron con ANSYS. En todos los casos
de estas subfiguras en la Fig. 33, la hoja transparente indica el orig-
hoja final mientras que la hoja sólida es la versión recientemente modificada. Aquí,
Las figuras 33-(a) a 33-(i) están relacionadas con los pasos de modificación 1-9, respectivamente.
tivamente. Tras todas las modificaciones, cada nuevo modelo fue recién
se mezcló y luego se determinaron las variables clave de rendimiento como se
presentado en la Sección 4.3.4.
Modificación 1: Como primera modificación, el ángulo de entrada de la pala interior
𝛽 1 aumentó. Debido a esto, la presión a través del lado inferior
de las palas del rodillo se redujo como se muestra en la Fig. 34. Aunque,
La distribución de la presión ha mejorado ligeramente en comparación con la
diseño original (ver Fig. 32), podría mejorarse aún más. Como
presentado en la Tabla 8, con la modificación 1, fue posible
aumentar la eficiencia del corredor del 50,98% al 54,51%.
Modificación 2: Como en la modificación 2, el ángulo de salida de la pala 𝛽 2 fue
aumentó aún más (como se muestra en la Fig. 33 -(b)) para reducir la tangente-
velocidad de salida tangencial 𝑐𝑢 2. Los cálculos teóricos dieron una velocidad tangencial
velocidad de salida de 0,897 m/s (en promedio), sin embargo, según la
Los resultados de CFD presentados en la Sección 4.3.2 fueron de 2,048 m/s.
cuanto mayor sea la diferencia entre las velocidades tangenciales de entrada y salida.
Cuanto mayor sea el número de ties (Δ 𝑤𝑢), mayor será la potencia de salida que se puede generar.
y por lo tanto la eficiencia. Con esta modificación, la tangencial
La velocidad de salida se redujo a 0,975 m/s y la eficiencia fue
mejoró del 54,51% al 73,72%.
Modificación 3: La modificación 3 fue aumentar el exterior exterior-
Supongamos que el ángulo 𝛽 2 es mayor y, por lo tanto, disminuye la salida tangencial.
velocidad (ver Fig. 33 -(c)), y esto mejoró la eficiencia del corredor.
eficiencia al 83,82%
Modificación 4: El ángulo de salida interior se incrementó con la modificación.
ficación 4 como se muestra en la Fig. 33 -(d) para reducir aún más la tangencial
velocidad de salida. Sin embargo, esta modificación provocó una disminución de la
eficiencia al 78,15% y por lo tanto no se implementó. El valor
de la velocidad de salida tangencial 𝑐𝑢 2 (antes de la modificación 3) es
bastante bajo y cercano al valor determinado teóricamente. Por lo tanto,
Como siguiente paso, se consideraría modificar el ángulo de entrada 𝛽 1
ya que esto puede influir en la velocidad de entrada tangencial 𝑐𝑢 1. La teoría-
El valor calculado reticalmente para 𝑐𝑢 1 fue de 5,184 m/s y esto ha dado un valor
de 3,979 m/s después de la tercera modificación, como se indica en la Tabla 8.
Modificación 5: Luego se introdujo la quinta modificación a partir de modi-
ficación 3 para disminuir el ángulo de entrada exterior 𝛽 1 con el propósito de
aumentando la velocidad de entrada tangencial 𝑐𝑢 1 (véase la figura 33 -(e)). Con
Figura 33. Esquemas que muestran las modificaciones 1 a 9.
Figura 34. Distribución de la presión a través del corredor después de la modificación 1.
Esto, la velocidad de entrada tangencial se incrementó a 4,104 ms−^1
y por lo tanto la eficiencia al 86,56%.
Modificación 6: La modificación 6 también tenía como objetivo reducir aún más el
ángulo de entrada exterior 𝛽 1 (como se presenta en la Fig. 33 -(f)) y por lo tanto a
aumentar aún más la velocidad de entrada tangencial 𝑐𝑢 1. Esto dio como resultado una tan-
velocidad de entrada general de 4,191 ms−^1 y por lo tanto la eficiencia de
El corredor subió al 88,83%.
Modificación 7: La modificación 7 consistió en disminuir la entrada exterior.
El ángulo 𝛽 1 y el ángulo de entrada interior también aumentaron ligeramente (ver
Figura 33 -(g)) para aumentar aún más la velocidad de entrada tangencial 𝑐𝑢 1. Como
Como resultado de esto, la velocidad de entrada tangencial se convirtió en 4,351 ms−^1.
y por lo tanto, la eficiencia aumentó al 93,01%.
Modificación 8: La octava modificación se implementó para in- ligeramente
aumentar el ángulo de entrada de la pala 𝛽 1 para aumentar la entrada tangencial
velocidad 𝑐𝑢 1 como se muestra en la Fig. 33 -(h). Sin embargo, con esto, la tan-
La velocidad gravitacional disminuyó a 4,241 ms−^1 y por lo tanto la eficiencia
se redujo al 89,12%. Por lo tanto, esta modificación tampoco fue
consideró.
Modificación 9: La modificación 9 se realizó aumentando ligeramente-
ing el ángulo de entrada 𝛽 1 como se representa en la Fig. 33 -(i) para in-
aumentar la velocidad de entrada tangencial 𝑐𝑢 1 y por lo tanto aumentar la
diferencia de velocidad tangencial Δ 𝑤𝑢. Sin embargo, con esta modificación-
Además, la velocidad de entrada tangencial disminuyó a 4,286 ms−^1.
causando una eficacia reducida del 90,12%. Por lo tanto, este medicamento
Tampoco se tuvo en cuenta y el diseño se dio con el 7.º mod.
La ficación se tomó como el diseño óptimo. Por lo tanto, desde el principio
Desde el diseño teórico hasta el diseño final optimizado por CFD, la potencia
La potencia producida por el corredor aumentó de 149.883,2 W a
273.456,2 W mientras que su eficiencia mejoró del 50,98% al
93,01%.
Luego, después de lograr el diseño/perfil óptimo de la pala con el
Con ángulos de entrada y salida modificados, este diseño optimizado del corredor
La rueda se probó de nuevo en CFD variando el número de aspas a
observar la mayor potencia de salida posible. Los resultados obtenidos son
mostrado en la Fig. 35. Finalmente, después de todas las modificaciones, el óptimo
El diseño fue el diseño que salió con la séptima modificación con 4 Runner
Figura 35. Potencia de salida de la turbina con diferente número de palas tras la optimización de los ángulos de las mismas.
palas. Este rotor optimizado mediante CFD proporcionó una potencia de salida de 273.456,2 W.
con una eficiencia de extracción de energía del 93,01%. Logrando lo mejor
La eficiencia posible con 4 aspas ahora está de acuerdo con la anterior.
Menny (2006) también informó hallazgos similares, aunque fue con
6 palas antes de la optimización del diseño tal como se presenta en la Sección 4.4.1.
5. Resultados y discusión
5.1. Diseño teórico
Para este estudio, se asumió que la turbina está instalada en un sistema hidráulico.
central hidroeléctrica (que cuenta con una presa construida a través de un río) que opera
con una altura de 6 m y un caudal de agua uniforme de 5 m³ .s−¹. Por lo tanto,
Las cuchillas están fijadas permanentemente al soporte ya que no es necesario
regular durante la operación. Debido a la altura relativamente baja, un Kaplan
Se eligió la turbina como el tipo más adecuado (Miller et al., 1987).
A partir de los cálculos teóricos presentados en la Sección 3.1, se obtiene una rotación.
Se eligieron una velocidad 𝑁 de 392,3 rpm y una velocidad específica 𝑁𝑠 de 228,78 para
determinar las dimensiones del rotor de la turbina. La determinación teórica-
La señal del corredor se realizó con 4 cuchillas y el sin dimensiones
coeficiente, “Schnelläufigkeit ”, 𝜎 de 1,45. Además, un diámetro número 𝛿 de
1.3 fue considerado, y por lo tanto el corredor (𝐷𝑎) y su cubo (𝐷𝑁) diame-
Los ters se seleccionaron como 0,996 m y 0,398 m, respectivamente. El máximo
La posible altura de succión 𝐻𝑆𝑚𝑎𝑥 se calculó en 2,363 m con cavitación.
coeficiente 𝜎𝑐 de 1,3. Sin embargo, la altura de succión real 𝐻𝑆 de la planta
Se seleccionó para que estuviera 2 m por encima del nivel del agua aguas abajo para evitar cualquier posible riesgo.
de cavitación. Finalmente, la eficiencia teórica del corredor fue
Se encontró que era del 94%.
5.2. Evaluación del rendimiento del corredor optimizado mediante CFD.
El corredor diseñado teóricamente original (que fue implementado)
en ANSYS con las mismas dimensiones exactas) dio solo el 50,98% de eficiencia.
eficiencia después de implementar con CFD. Por lo tanto, el diseño teórico fue
optimizado con CFD principalmente ajustando los ángulos de entrada y salida de
Tabla 9
Las magnitudes de los ángulos de las palas de la ejecución teórica y optimizada mediante CFD-
ners en diferentes ubicaciones radiales.
D a D 1 D 2 D 3 D N Unit
𝛽 1 theoretical 156.02 150.55 141.60 124.74 90.02 Degree
𝛽 2 theoretical 158.98 155.43 150.50 143.21 131.52 Degree
𝛽 1 optimised 150.60 144.00 136.80 128.50 114.50 Degree
𝛽 2 optimised 165.90 160.50 154.00 147.30 136.20 Degree
∆ 𝛽 1 -5.42 -6.55 -4.80 3.76 24.48 Degree
∆ 𝛽 2 6.92 5.07 3.50 4.09 4.68 Degree
las palas (con una serie de pasos) para alcanzar una mayor velocidad tangencial-
diferencia de idad Δ 𝑤𝑢 , ya que la eficiencia del corredor aumenta con Δ 𝑤𝑢.
Además, se estudiaron los efectos del número de palas en la eficiencia de la turbina.
explorado variando el número de aspas de 3 a 7. Aquí, una discusión
de los resultados obtenidos con el método teórico, CFD teórico (el mismo)
El diseño teórico en CFD) y los diseños optimizados mediante CFD se presentan en
las siguientes secciones.
5.2.1. Diseño de las palas
Los ángulos de entrada y salida de las palas (de ahí la forma de
Las palas del corredor) se modificaron en 9 pasos como se explicó en
Sección 4.4.3. En cada uno de estos pasos, se intentó modificar la in-
ángulos de las aspas de entrada y/o salida para ajustar la diferencia de velocidad tangencial
para alcanzar la mejor potencia posible y la eficiencia resultante.
comparación de las palas del diseño teórico y el CFD final-
Los corredores optimizados se presentan en la Fig. 36, donde el diseño teórico
está indicado por las líneas transparentes. Como es evidente, las salidas de las cuchillas
son bastante más planos ahora y por lo tanto la magnitud de los ángulos de salida 𝛽 2
ha aumentado desde su valor teórico. Mientras tanto, el tamaño de
Los ángulos de entrada de las palas 𝛽 1 también se han vuelto más grandes desde el lado interior.
mientras que el lado exterior se hacía más pequeño. Las magnitudes de entrada y salida
ángulos de las palas en diferentes ubicaciones radiales tanto para teóricos como para
Los diseños optimizados mediante CFD se presentan en la Tabla 9. Las magnitudes Δ 𝛽 1
Figura 36. Modelo 3D que compara los corredores calculados teóricamente y los optimizados mediante CFD en ANSYS.
Fig. 37. Las magnitudes de la diferencia de velocidad tangencial en diferentes ubicaciones radiales del modelo teórico, CFD-teórico (con las mismas dimensiones exactas que el modelo teórico).
diseño teórico) y corredores optimizados mediante CFD.
y Δ 𝛽 2 indican la diferencia entre los ángulos de entrada y salida de
los diseños teóricos y optimizados mediante CFD, respectivamente. Como es evidente,
la mayor discrepancia entre la des- teórica y la optimizada por CFD-
La señal se encuentra en la entrada de la pala interior y esto indica una diferencia de 24,48°.
5.2.2. Velocidad tangencial
A partir de la ecuación de Euler (es decir, la ecuación (1)) y los cálculos presentados
En la Sección 4.3.4, queda claro que la potencia de salida (y por lo tanto el resultado-
La eficiencia de rotación del corredor depende de la velocidad tangencial.
y esto también queda claro en la Fig. 37. La velocidad tangencial de entrada/salida
vínculos logrados mediante diseños teóricos, teóricos de CFD y optimizados mediante CFD.
siguen una tendencia bastante similar, sin embargo, el mag- calculado teóricamente
Las magnitudes son mayores que los valores dados por CFD. Las magnitudes de
la diferencia de velocidad tangencial Δ 𝒘 (^) 𝒖 de la teórica (Theor.), CFD-

Los corredores teóricos (CFD) y optimizados mediante CFD (Optim.) son de 3,865 m/s,
2,096 m/s y 3,824 m/s, respectivamente.
5.2.3. La potencia de salida y la eficiencia resultante
Se identificó la mayor diferencia de velocidad tangencial posible Δ 𝑤𝑢.
se filtró después de modificar los ángulos de entrada y salida de las palas. Luego, el
Se puede determinar la potencia producida por el corredor optimizado mediante CFD.
de la ecuación (18):
𝑃𝑟𝑢𝑛𝑛𝑒𝑟 = 𝜌
1
4
𝜋
(
𝐷^2 𝑎^ − 𝐷^2 𝑁^
)
𝑐 0 𝑢 Δ 𝑤𝑢
𝑃𝑟𝑢𝑛𝑛𝑒𝑟 = 999 ×0. 25 𝜋
(
0,99582 −0,39832
)
×7.643 ×14.316 ×3.824
= 273 456, 3 W
Como se calculó anteriormente, en función de las condiciones del estudio de caso (un
con una altura de 6 m y un caudal uniforme de 5 m³ .s⁻¹ ), el flujo de agua puede
Proporcionar una potencia de salida equivalente a 294005,7 W. Por lo tanto, la eficiencia
del corredor final optimizado por CFD podría calcularse a partir de la ecuación (19), como
Se presentó anteriormente:
𝜂𝑟 =
𝑃𝑟𝑢𝑛𝑛𝑒𝑟
𝑃𝑤𝑎𝑡𝑒𝑟
× 100% =
273456. 3
294005. 7
× 100% = 93,01%
Como se presentó en la Sección 3.2, una potencia de salida de 276365,36 W
fue dado por el corredor diseñado teóricamente mientras que el mismo diseño
En CFD (CFD-teórico) solo se proporcionó una potencia de salida de 149883,2.
W. Luego, el corredor optimizado mediante CFD final pudo generar un resultado.
entrada de 273456,3 W. Por lo tanto, la optimización CFD ha provocado que...
aumentar la eficiencia del corredor 𝜂𝑟 en un 42,03% (es decir, del 50,98% al
93,01%). Además, las potencias de salida y las eficiencias relacionadas de la
Conductores teóricos y optimizados mediante CFD a diferentes velocidades de entrada.
se presentan en las figuras 38-(a) y 38-(b), respectivamente. Como es evidente, la
La potencia de salida desarrollada por el corredor mejora con el aumento de
velocidad de entrada del flujo de agua a medida que aumenta la cantidad de energía
llevado por. Aunque la capacidad de generación de energía mejora con
la velocidad de entrada, la eficiencia de extracción de energía del corredor logra una
máximo del 93,01% a una velocidad de entrada de 7,64 ms−^1 y luego después-
hacia la eficiencia muestra una reducción gradual. La teóricamente de-
El corredor firmado en CFD (CFD-teórico) dio su máxima eficiencia de
50,98%, a una velocidad de entrada entre 7,64 y 8 ms−^1. Mientras tanto, el
El corredor diseñado teóricamente dio una eficiencia del 94%. Podría haber
Existen algunas posibles causas de que existan tales diferencias entre CFD y
resultados generados teóricamente. Como se informó en algunos informes anteriores
búsquedas (ESHA, 2004), los cálculos/diseños teóricos suelen ser
capaz de proporcionar solo una solución aproximada para la mayor parte del diseño.
ejercicios. Esto se debe principalmente al hecho de que la mayoría de los teóricos-
Las ecuaciones químicas están asociadas a una serie de supuestos simplificadores.
eso podría conducir a soluciones menos precisas. Por lo tanto, hoy en día es bastante
Es común evaluar y modificar diseños teóricos con CFD para el diseño.
optimización. Sin embargo, los diseños optimizados mediante CFD también pueden ser...
asociado con algunas limitaciones y la precisión de los resultados depende
en factores como el solucionador utilizado, la selección del límite
condiciones, calidad/precisión de la malla, etc. (Dragic y otros, 2014), y
también con las limitaciones asociadas al software también (Lukas et al.,
2010), y algunos de ellos se analizaron en la Sección 4.2. Además,
otros componentes relacionados, como el eje del corredor, el tubo de tiro y
Las paletas guía también deben analizarse simultáneamente para lograr una comprensión completa.
turbina optimizada mientras que las condiciones de contorno también son críticas en la
precisión de las evaluaciones CFD ( Vu et al., 2013 ). Además, el tangen-
Las velocidades iniciales medidas con CFD también podrían ser ligeramente inexactas.
las limitaciones experimentadas en la creación de los planos de medición, como se
tratado en la Sección 4.3.2.
5.2.4. Comportamiento del flujo
La figura 39 representa los comportamientos/patrones de flujo a través del CFD-
corredores teóricos y optimizados mediante CFD. Claramente, hay diferencias notables.
diferencias en el comportamiento del flujo entre los modelos optimizados mediante CFD y los modelos teóricos
corredores. Sin embargo, las diferencias reales del comportamiento del flujo a través de
El corredor giratorio no pudo visualizarse correctamente debido a la limitación.
ciones de ANSYS (es decir, la representación gráfica de una geometría en movimiento) y
Esto se describió anteriormente en las Secciones 4.2 y 4.3. La ejecución optimizada de CFD-
El ner libera agua al tubo de tiro (en su salida) en una línea bastante recta.
de manera mientras que el flujo de salida del corredor teórico CFD indica
comportamiento de flujo turbulento/de remolino relativamente alto que el del CFD-
corredor optimizado. Por lo tanto, esto es una indicación de que el agua que sale
a partir del diseño teórico CFD todavía tiene cierto nivel de potencial por delante
generando la energía (Menny, 2005). De lo contrario, se puede explicar
que el diseño teórico no es efectivo para extraer la energía de
el flujo de agua como en el corredor optimizado mediante CFD.
Figura 38. La potencia de salida (arriba) y la eficiencia resultante (abajo) de los corredores teóricos y optimizados mediante CFD a diferentes velocidades de entrada del flujo.
agua.
Figura 39. Líneas de corriente de velocidad a través del corredor: Izquierda: corredor optimizado mediante CFD; Derecha: corredor teórico mediante CFD.
5.2.5. Distribución de la presión
La figura 40 muestra la distribución de presión resultante a lo largo del corredor.
para corredores teóricos y optimizados mediante CFD. Como se indica en
Los mapas de color de la izquierda, la optimización de CFD ha provocado un aumento
la presión máxima a través del corredor en 24 kPa (es decir, de 160 kPa
a 184 kPa) mientras que la presión mínima también ha aumentado en 61,74
kPa (es decir, de -63,8 kPa a 2,06 kPa), de negativo a positivo
presión. Además, es evidente que la presión sobre la superficie inferior
del corredor optimizado por CFD se ha reducido ligeramente en comparación con el CFD-
corredor teórico. Con la optimización, la diferencia de presión a través
El corredor ha aumentado y esto es favorable para aumentar el corredor.
capacidad de generación de energía y, por lo tanto, la eficiencia resultante también.
( Styrylski et al., 2008 ). En el corredor teórico de CFD (arriba), algunos local-
Las propiedades de las superficies inferiores de las palas (posición 1) indican una mayor
nivel de presión que el de las superficies superiores (posición 2). Sin embargo,
en el corredor optimizado por CFD, la presión a través del área indicada por
La posición 1 se ha reducido y, en general, las superficies inferiores muestran un nivel más bajo.
capas de presión que las superficies superiores de las palas (lo cual es favorable)
en la mejora de la eficiencia de extracción de energía). Con la modificación
8 (discutido en la Sección 4.4.3), se intentó reducir aún más
la presión alrededor de la posición 1 aumentando aún más la entrada de las palas
ángulo. Sin embargo, esta modificación solo produjo un ligero aumento en la tangente.
diferencia de velocidad angular, pero no hubo mejora en la carrera.
eficiencia de ner. Además, las áreas que mantienen la baja presión tienen
También se desplazó con la optimización CFD, que está marcada como posición 3.
en ambos corredores. Dichas áreas con baja presión pueden estar en riesgo de cavitación.
cita (si la magnitud de la presión es menor que la presión de vapor-
seguro del fluido) que se sabe que es uno de los problemas comunes, por ejemplo
experimentado por maquinarias hidráulicas con movimiento rotatorio. Por lo tanto,
La distribución de la presión a través de las palas del rotor se evaluó además.
ated para examinar las áreas críticas de baja presión para comprobar si
están por debajo de la presión de vapor. Si la presión en algunas posiciones
de la rueda de rodadura está alcanzando por debajo de la presión de vapor del agua.
ter, el agua en tales lugares se puede convertir en vapor y esto
causaría cavitación, lo que provocaría daños en las palas. Para este caso en particular
trabajo, la presión de vapor y la temperatura máxima del agua
se determinaron como 1,705 kPa y 15 °C, respectivamente ( Rod, 2000 ). Como
Como se puede leer en la Fig. 40, el corredor optimizado por CFD indica el bajo-
La presión estimada es de 2,060 kPa, y esto está muy por encima de la presión de vapor.
de agua a 15 °C. Por lo tanto, se puede afirmar que el CFD optimizado
El corredor no corre riesgo de sufrir cavitación. Para este estudio, los puntos
de baja presión (indicada por el color azul) a lo largo del corredor son bastante
los mismos puntos que fueron observados por Mecaflux (2013) en su re-
búsqueda. Como afirmó PACER (1995), los rotores de las turbinas Kaplan
Figura 40. Distribución de presión (unidades –Pa) a través de la rueda del rotor: teórica mediante CFD (arriba), optimizada mediante CFD (abajo).
Figura 41. Distribución de presión (unidades: Pa)
a través del corredor optimizado mediante CFD a 0 rpm.
Tabla 10
Los parámetros medidos en la parte superior (Up. Surf) y en la parte inferior
superficies (Lo. Surf) del corredor optimizado mediante CFD.
Blade
At 392.25 rpm At 0 rpm Unit
Up. Surf. Lo. Surf Up. Surf. Lo. Surf
Pressure 58632.84 4910.03 259614.54 -12238.70 Pa
Area 0.152 0.152 0.152 0.152 m
Force 8912.19 746.32 39461.41 -1860.28 N
Pressure difference 53722.81 271853.24 Pa
Resultant force 8165.87 41321.69 N
son normalmente susceptibles a la cavitación debido a su rotación relativamente alta.
velocidades tional. Por lo tanto, es importante evitar las posibles causas que
puede conducir a crear posibles oportunidades en que se produzcan situaciones de cavitación
la etapa de diseño en sí. La posible aparición de la cavitación no es normal.
depende principalmente de la velocidad y la presión del agua que fluye
a través de las palas del corredor. Si bien las altas velocidades promueven la cavitación, es
También es un requisito para lograr altas eficiencias. Por lo tanto, sería
Es adecuado ajustar la presión estática modificando el cabezal de succión.
En consecuencia.
Según RDT (2014), la presión máxima a través de la carrera-
Las cuchillas ner se producen cuando el corredor está en condiciones estáticas (es decir, a 0
rpm). La figura 41 muestra la distribución de presión a través del corredor cuando
está bajo condiciones estáticas (mientras que las demás condiciones de flujo permanecen iguales)
y está claro que la presión máxima a través del corredor en condiciones estáticas
Las condiciones son dos veces más altas que las de las condiciones rotacionales (ver
Figuras 40 y 41).
Con ANSYS Fluent, la magnitud de la presión a través de la parte superior
y las superficies inferiores del corredor podrían determinarse con la ayuda
de la herramienta de medición de integral de superficie. Algunos parámetros medidos en
Las velocidades de rotación de 392,25 rpm y 0 rpm se enumeran en la Tabla 10.
Se puede observar que la diferencia de presión medida y la resultante
Las fuerzas son bastante mayores en condiciones estacionarias que cuando la rueda está en
rotación. La fuerza resultante máxima 𝐹𝑚𝑎𝑥 se registra como 41321,69 N
a 0 rpm. Habrá una diferencia de presión a través del conducto debido a la
diferencias de presión entre las superficies superior e inferior. La superficie
También se determinaron las áreas de las superficies superior e inferior de las palas con
La herramienta de medición integral y luego se determinó la fuerza resultante.
utilizando la ecuación (27).
𝐹 𝑜𝑟𝑐𝑒 =Presión × 𝐴𝑟𝑒𝑎 (27)
Por ejemplo, la presión en la superficie superior a 392,25 rpm:
𝐹 𝑜𝑟𝑐𝑒 = 58632. 84 ×0. 152 = 8912. 19 𝑁
5.2.6. Par motor del corredor
Después de determinar la fuerza ejercida en la dirección tangencial, la
El par máximo del corredor 𝑀𝑚𝑎𝑥 se puede calcular (por incor-
girando el radio en el centro de la hoja, 𝑟 ) como se presentó
por Szymczyk (2008), utilizando la ecuación. (28) :
𝑀𝑟𝑢𝑛𝑛𝑒𝑟 = 𝐹𝑢 𝑟 = 𝑚̇ 𝑟
(
𝑐𝑢 2 − 𝑐𝑢 1
)
(28)
Como se presentó en la ecuación (18), 𝑚̇ = 𝜌𝐴𝑐 0 = 𝜌
1
4
𝜋 ( 𝐷^2 𝑎^ − 𝐷^2 𝑁^ ) 𝑐 0 , por lo tanto:
𝑀𝑟𝑢𝑛𝑛𝑒𝑟 = 𝜌
1
4
𝜋
(
𝐷^2 𝑎^ − 𝐷^2 𝑁^
)
𝑐 0 𝑟 Δ 𝑤𝑢
𝑀𝑟𝑢𝑛𝑛𝑒𝑟 = 999 ×
1
4
𝜋
(
0, 9958
2
-0,3983
2)
×7,643 ×0,353 ×3,824
= 6742,85 Nm
Se determinó el radio en el centro de las palas del rotor (𝑟).
con la ayuda de las herramientas de Solid Edge.
5.2.7. La energía eléctrica
La energía extraída por la rueda del rodillo del agua en movimiento puede
luego se transforma en energía eléctrica mediante un generador. La posibilidad
La capacidad de generación de energía eléctrica depende de la situación real.
eficiencia del generador 𝜂𝑒𝑙 , y se considera que es del 95% en función de
las características del generador presentadas por PACER (1995). Por lo tanto, el
Los valores de potencia eléctrica (Pel) se pueden calcular a partir de las ecuaciones (29) y (30).
𝑃𝑒𝑙 = 𝑃𝑟𝑢𝑛𝑛𝑒𝑟 𝜂𝑒𝑙 (29)
𝑃𝑒𝑙 = 273456. 3 ×0. 95 = 259, 783, 49W
Entonces, se puede determinar la capacidad anual de energía eléctrica.
(con un total de 8760 horas al año):
𝑃𝑒𝑙 = 𝑃𝑒𝑙 × 𝑛𝑢𝑚𝑏𝑒𝑟 𝑜𝑓 ℎ𝑜𝑢𝑟𝑠 (30)
𝑃𝑒𝑙 = 259783. 49 × 8760 = 2, 275, 703. 46 𝑘𝑊 ℎ
6. Conclusión
Se presenta un estudio exhaustivo sobre el diseño y la optimización.
de una rueda de rodadura de una turbina Kaplan. Inicialmente, se diseñó un rodete.
teóricamente basado en un estudio de caso dado y dio un generador de poder-
eficiencia de ación del 94%. Luego, el corredor diseñado teóricamente fue
implementado en una plataforma CFD (ANSYS) con las mismas dimensiones exactas.
siones. Sin embargo, el mismo diseño teórico implementado con CFD
(con las mismas dimensiones exactas) dio una eficiencia de alrededor de
50,98%. Por lo tanto, está claro que los cálculos teóricos son menos precisos.
precisión que debería deberse a las suposiciones simplificadoras relacionadas.
Sin embargo, los cálculos teóricos siempre son invaluables como punto de partida.
paso de diseño. Luego, el corredor diseñado teóricamente que fue implementado
El método estudiado en CFD se modificó siguiendo una serie de opciones posibles.
como por ejemplo, cambiando los ángulos de entrada/salida de las palas y también variando
el número de palas. Con las modificaciones realizadas en CFD, fue
es posible mejorar la eficiencia de extracción de energía del corredor sig-
significativamente del 50,98% al 93,01%. Además, los resultados de CFD lo confirmaron
que los ángulos de entrada y salida de las palas del rotor pueden influir en el
diferencia de velocidad tangencial del agua que fluye y por lo tanto puede in-
también influyó en la eficiencia de generación de energía de la turbina. Fue capaz de
lograr una mejora sustancial en la eficiencia de extracción de energía
de la turbina ajustando los ángulos de entrada/salida de las palas, donde
En este estudio se logró una mejora de hasta el 42,03%. Después de la operación...
Sincronización de los ángulos de entrada y salida, el efecto del número de álabes
También se observó al cambiar el número de aspas de 3 a 7, y
Se ha comprobado que 4 aspas proporcionan la mejor eficiencia y esto está de acuerdo.
con los trabajos informados anteriormente también. En general, este trabajo amplía
El estado del arte en el diseño y la optimización de una turbina Kaplan.
rueda de corredor al proporcionar una visión amplia de todos los aspectos relacionados.
Obviamente, este tipo de información específica/amplia rara vez se encuentra en la literatura actual.
eratura. Además, el análisis y los hallazgos de este trabajo deben ser utilizados-
completo en el diseño y optimización de otros tipos de turbinas hidráulicas
también.
Declaración de conflicto de intereses
Los autores declaran no tener ningún conflicto de intereses financiero conocido.
intereses o relaciones personales que podrían haber parecido influir
el trabajo que se presenta en este artículo.
Expresiones de gratitud
El autor desea agradecer el apoyo brindado.
por el Sr. Tobi Hantsch en la realización de este proyecto.
Referencias
Abeykoon, C. , 2020. Intercambiadores de calor compactos: diseño y optimización con CFD. Int. J.
Heat Mass Transf. 146, 118766.
ANSYS, 2015. Canonsburg, Pensilvania, EE. UU. [En línea] disponible en < .
Ardizzon, G. , Cavazzini, G. , Pavesi, G. , 2014. Una nueva generación de pequeñas
centrales hidroeléctricas y de bombeo: avances y desafíos futuros. Renew. Sustain. Energy Rev. 31,
746–761.
Arne, K. , 2001. Energía hidroeléctrica en Noruega, Equipos mecánicos. Universidad Noruega de
Ciencia y Tecnología, Trondheim en Noruega.
Balkhair, KS , Rahman, KU , 2017. Generación de energía hidroeléctrica sostenible y económica a pequeña escala y de baja altura
: una solución potencial alternativa prometedora para la generación de energía
a escala local y regional. Appl. Energy 188, 378–391.
Balint, D. , 2004. High performance computing of self-induced unsteadiness for cavitating
flows in Hydraulic Turbo Machinery.
Borkowski, D. , Wegiel, M. , Oc ł on, P. , Wegiel, T. , 2019. CFD model and experimental ver- ification
of water turbine integrated with electrical generator. Energy 185, 875–883.
Bozic, I. , 2021. A novel energy losses dependence on integral swirl flow parameters in an
elbow-draw tube of a Kaplan turbine. Renew. Energy 175, 550–558.
Bozic, I. , Benisek, M. , 2016. An improved formula for determination of secondary energy
losses in the runner of Kaplan turbine. Renew. Energy 94, 537–546.
Choi, H. , Zullah, M. , Roh, H. , Ha, P. , Oh, S. , Lee, Y. , 2013. Validación CFD de la
mejora del rendimiento de una turbina Francis de 500 kW. Renew. Energy 54, 111–123.
Cooray, N. , 2012. Los jardines reales de Sigiriya: análisis de la
composición arquitectónica del paisaje. CreateSpace Independent Publishing Platform.
Dasanayaka, CH , Perera, YS , Abeykoon, C. , 2022. Investigación de los efectos de
la utilización de energía renovable hacia el crecimiento económico de Sri Lanka: un
enfoque de modelado de ecuaciones estructurales. Clean. Eng. Technol. 6, 100377.
Dharmasena, PB, 2010. Evolución de las sociedades hidráulicas en el antiguo
reino de Anuradhapura de Sri Lanka. En: Martini, I., Chesworth, W. (Eds.), Paisajes y sociedades.
Springer, Dordrecht doi: 10.1007/978-90-481-9413-1_21.
Dixon, SL , 2005. Mecánica de fluidos y termodinámica de turbomáquinas, 5.ª ed.
Elsevier Butterworth–Heinemann.
Dragica, J. , Š kerlavaj, A. , Andrej, L. , 2014. Mejora de la predicción de eficiencia para una
turbina Ka- plan con modelos avanzados de turbulencia, Turboin š titut. J. Mech. Eng. Slove-
nia.

ESHA, 2004. (European Small Hydropower Association –ESHA), Guide on How to Develop
a Small Hydropower Plant. TNSHP, Brussels, Belgium.
Ferziger, J.H. , Peric, M. , Street, J.L. , 2019. Computational methods for fluid dynamics,
4th Ed. Springer, Stanford, USA ISBN-10: 3319996916.
Flaspöhler, T. , 2007. Design of the runner of a Kaplan turbine for small hydroelectric
power plants. Tampere University of Applied Sciences, Tampere, Finland.
Grassmann, H. , Ganis, M.L. , 2005. On partially static Kaplan turbines. Renew. Energy 30,
179–186.
Grekula, M. , Bark, G. , 2001. Experimental study of cavitation in a Kaplan model turbine.
Fourth International Symposium on Cavitation, June 20-23. California Institute of
Technology, Pasadena, CA USA.
Gunasekara, S. , 2004. Pa ṭṭ ipola Badulla - an exceptional design of ancient sinhala hy-
draulic engineering. J. R. Asiat. Soc. S. L., New Series 50, 33–42.
IEA (International Energy Agency), 2018. Global energy & CO 2 status report, the latest
trends in energy and emissions in 2018. IEA [Online] Available from:.
IHA (International Hydropower Organization), 2017. Key trends in hydropower. IHA [On-
line] Available at:.
Institute for Hydraulic Fluid Machinery, 2012. Entwicklung einer Kaplan-Rohrtur-
binen-Hydraulik. Technical University Graz, GrazAustria in[Online] available from
<.
IRENA (International Renewable Energy Agency), 2019. Renewable energy now accounts
for a third of global power capacity. IRENA [online] available from:.
Jakob, A. , 2010. Temperaturen in Schweizer Fliessgewässern. GWA, BernSwitzerland in.
Janjua, A.B. , Khalil, M.S. , Saeed, M. , 2013. Blade Profile Optimisation of Kaplan Turbine
Using CFD Analysis. Mehran Univ. Res. J. Eng. Technol. 32 (4), 559–574 Pakistan„
ISSN 0254-7821.
Janjua, A.B. , Khalil, M.S. , Saeed, M. , Butt, F.S. , Badar, A.W. , 2020. Static and dynamic
computational analysis of Kaplan turbine runner by varying blade profile. Energy
Sustain. Dev. 58, 90–99.
Javadi, A. , Nilsson, H. , 2017. Detailed numerical investigation of a Kaplan turbine with
rotor-stator interaction using turbulence-resolving simulations. Int. J. Heat Fluid Flow
63, 1–13.
Jonsson, P.P. , Mulu, B.G. , Cervantes, M.J. , 2012. Experimental investigation of a Kaplan
draft tube –Part II: Off-design conditions. Appl. Energy 94, 71–83.
Kaniecki, M. , Krzemianowski, Z. , Banaszek, M. , 2011. Computational fluid dynamics sim-
ulations of small capacity Kaplan turbines. Transactions of the Institute of fluid-flow
machinery 123, 71–84.
Kumar, P. , Saini, R.P. , 2010. Study of cavitation in hydro turbines-a review. Renew. Sus-
tain. Energy Rev. 14, 374–383.
Kuriqi, A.N. , Pinheiro, A.N. , Sordo-Wardb, A. , Garrote, L. , 2019. Flow regime aspects in
determining environmental flows and maximizing energy production at run-of-river
hydropower plants. Appl. Energy 256, 113980.
Lipej, A. , Poloni, C. , 2000. Design of Kaplan runner using multi-objective genetic algorithm
optimization. J. Hydraul. Res. 38 (1), 73–79.
Martinez, J.J. , Deng, Z.D. , Titzler, P.S. , Duncan, J.P. , Lu, J. , Mueller, R.P. , Tian, C. ,
Trumbo, B.A. , Ahmann, M.L. , Renholds, J.F. , 2019. Hydraulic and biological char-
acterization of a large Kaplan turbine. Renew. Energy 131, 240–249 [37].
Masood, Z. , Khan, S. , Qian, L. , 2021. Machine learning-based surrogate model for acceler-
ating simulation-driven optimisation of hydropower Kaplan turbine. Renew. Energy
173, 827–848.
Mecaflux, 2013. Cavitation propeller and hydrofoils or foils. Mecaflux Heliciel, Naves-
France in[Online] available from <.
Menny, K. , 2006. Strömungsmaschinen –Hydraulische und thermische Kraft- und Arbeits-
maschinen, Verlag, Ronnenberg, Germany.
Miller, G. , Corren, D. , Armstrong, P. , Franceschi, J. , 1987. A study of an axial-flow turbine
for kinetic hydropower generation. Energy 12, 155–162.
Morabito, A. , Hendrick, P. , 2019. Pump as turbine applied to micro-energy storage and
smart water grids: a case study. Appl. Energy 241, 567–579.
Muis, A. , Sutikno, P. , Soewono, A. , Hartono, F. , 2015. Design optimization of axial hy-
draulic turbine for very low head application. In: 2nd International Conference on
Sustainable Energy Engineering and Application, Energy Procedia, 68, pp. 263–273.
Mulu, B.G. , Jonsson, P.P. , Cervantes, M.J. , 2012. Experimental investigation of a Kaplan
draft tube –Part I: best efficiency point. Appl. Energy 93, 695–706.
Nawar, M.A.E.A.E. , 2016. Hydro power plant technology. Report by Helwan University,
Egypt Available at:.
Nennemann, B., Vu, T.C., 2007. Kaplan turbine blade and discharge ring cavitation
prediction using unsteady CFD. In: Proceedings of the 2nd IAHR international
meeting of the workgroup on cavitation and dynamic problems in hydraulic ma-
chinery and systems, Timisoara, Romania. IAHR, Timisoara, Romania Available
at:. http://mh.mec.upt.ro/iahr2007/pdf/09_Nennemann.pdf. October 24 - 26, 2007,
[Last Viewed: 13/07/2022].
Nilsson, H., Davidson, L., 1999. A numerical investigation of tip clearance flow in Ka-
plan water turbines. Proceedings of Hydropower into the next century —III. ISBN 0
9522642 9 3, Available at http://mh.mec.upt.ro/iahr2007/pdf/09_Nennemann.pdf.
[Last Viewed: 13/07/2022].
Ogbonnaya, C., Abeykoon, C, Damo, U., Turan, A., 2019. The current and emerging re-
newable energy technologies for power generation in Nigeria: a review. Therm. Sci.
Eng. Progress 13. doi: 10.1016/j.tsep.2019.100390.
PACER, 1995. Kleinwasserkraftwerke, Wasserturbinen, Switzerland. [Online] avail-
able from < https://swissmallhydro.ch/wp-content/uploads/2019/07/247_1d-
Wasserturbinen.pdf >[Last Viewed: 13/07/2022].
Piratelli-Filho, A. , Araújo, J.A. , Júnior, A.C.P.B. , 2009. Reverse engineering of hydraulic
turbine runners using coordinate measuring arms and NURBS modelling. Rev. Tecnol.,
Fortaleza 30 (1), 114–122.
Price, T. , Probert, D. , 1997. Harnessing hydropower: a practical guide. Appl. Energy 57
(2/3), 175–251.
Rashad, SM , Ismail, MA , 2000. Evaluación del impacto ambiental de la energía hidroeléctrica en
Egipto. Appl. Energy 65, 285–302.
RDT , 2014. Kraft- und Arbeitsmaschinen Skript. Rudolf Diesel Technikum Augsburg en
Alemania.
Rod, N. , 2000. Guelph. Presión de vapor saturado. Densidad del agua Hyper Physics,
Canadá en [En línea] disponible en < .
Salah, S. , Eltaweel, M. , Abeykoon, C. , 2022. Hacia un futuro energético sostenible para Egipto
: una revisión sistemática de fuentes de energía renovables, tecnologías y recomendaciones
. Cleaner Engineering Technology.
Sedmaka, A., Arsi ćb, M., Milovanovi ćc, N., Opa či ćc, M., Đor đevi ćc, B., 2022.
Análisis de integridad estructural de una cubierta de turbina Kaplan. Estructura de procedimiento. Integral 37, 263–

Schiffer, J., Benigni, H., Jaberg, H., Wessiak, M., Mayrhuber, J., 2013.
Investigación experimental del sello de labio de borde de una turbina Kaplan STRAFLO de doble regulación
en condiciones extremas. Hydro - Conferencia y Exposición Internacional - Innsbruck , Austria .
Disponible en: http://www.hfm.tugraz.at/fileadmin/user_upload/pdf/publikationen/2013/Institut-HFM_TU-Graz_HYDRO_2013_investigation-rim-lip-seal-double-regulated-STRAFLO-Kaplan-turbine.pdf [Última visualización: 13/07/2022]. Shamsuddeen, MM, Park, J., Choi, Y., Kim, J., 2020. Análisis de cavitación multifásica transitoria sobre el efecto de una aleta anticavitación instalada en un rotor de turbina Kaplan. Renewable Energy 162, 861–876. Shi, H., Li, Z., Li, Y., 2007. Un sistema de monitoreo de cavitación en línea para grandes turbinas Kaplan . IEEE Power Engineering Society General Meeting 1–16.







Styrylski, M. , Tomalik, J. , Grahl, M.M. , 2008. Computer Aided Engineering as a Useful
Tool in Hydraulic Turbine Design, Krzeszowice. The 9th International Scientific Con-
ference Computer Aided Engineering, 58-580 Szklarska Poreba, Poland.
Szymczyk, J.A. , 2008. Vorlesungsskript zur Strömungsmechanik, Berechnungsschema Ka-
plan Turbinen, FH Stralsund, Stralsund in Germany.
US Dept. of Energy, 2022. History of Hydropower, Washington [Online] available from: <.
Vu, C.T., Gauthier, M., Nennemann, B., Wallimann, H., Deschênes, C., 2013. CFD analysis
of a blub turbine and validation with measurements from the BlubT project. IAHR
2014, Canada and Switzerland Available at: doi: 10.1088/1755-1315/22/2/022008.
Woehl, M. , 2013. The Kaplan turbine –a hydropower innovation celebrates its 100th
birthday. Voith GmbH Heidenheim, Germany in [Online] Available at:.
Wu, Y. , Liu, S. , Dou, H. , Wu, S. , Chen, T. , 2012. Numerical prediction and similarity study
of pressure fluctuation in a prototype Kaplan turbine and the model turbine. Comput.
Fluids 56, 128–142.
Zhang, M. , Valentina, D. , Valeroa, C. , Presasa, A. , Egusquizaa, M. , Egusquizaa, E. , 2020.
Experimental and numerical investigation on the influence of a large crack on the
modal behaviour of a Kaplan turbine blade. Eng. Fail. Anal. 109.
Zhang, M. , Chen, Q. , 2022. Influence of internal blade-interactions on the added mass
and added damping of a prototype Kaplan turbine runner. Alexandr. Eng. J. 61,
2376–2385.
Zivkovic, S. , Cerce, L , Kostic, J. , MAJSTOROVIC, V. , Kramar, D. , 2018. Reverse engineer-
ing of turbine blades Kaplan’s type for small hydroelectric power station. Procedia
CIRP 75, 379–384.
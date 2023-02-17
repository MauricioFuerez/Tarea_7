# Informe Tarea 7


Nombre: Mauricio Fuerez

NRC:10069

El informe realizado a continuación está evaluado y especificado para la compresión de los capítulos  13 y 14 del libro: Principios de circuitos eléctricos - Floyd

# 1.OBJETIVOS

1.1 Objetivo general:

*  Analizar y entender el capitulo 13 y 14 del libro "Principios de circuitos electricos - Floyd" para lo cual se debera leer y resolver los ejercicios pares que se encuentran al terminar el capitulo.

1.2 Objetivos especificos:

* Realizar un resumen del conenido de cada capitulo visto.

* Estudiar los capacitores e inductores.

* Reforzar el trabajo y uso de las ondas seno en CA

* Realizar los ejercicios pares de cada capitulo y explicar como fueron resueltos
 
# 2.MARCO TEÓRICO

*  CAPITULO 13 : INDUCTORES

EL INDUCTOR BASICO:

Un inductor es un componente eléctrico pasivo formado por un alambre enrollado alrededor de un núcleo y el cual exhibe la propiedad de inductancia. Cuando a un tramo de alambre se le da la forma de una bobina, se convierte en un inductor. Los términos bobina e inductor se utilizan indistintamente. La corriente que fluye a través de la bobina produce un campo electromagnético, como se ilustra. Las líneas de fuerza magnéticas que están presentes alrededor de cada espira (vuelta) en el devanado de la bobina se suman efectivamente a las líneas de fuerza localizadas alrededor de espiras adjuntas y forman un fuerte campo electromagnético adentro y en torno de la bobina. La dirección neta del campo electromagnético total crea un polo norte y un polo sur.

Para comprender la formación del campo electromagnético total en una bobina, consideremos la interacción de los campos electromagnéticos alrededor de dos espiras adyacentes. Cada una de las líneas de fuerza magnéticas en torno de espiras adyacentes se deflexiona hasta formar una trayectoria externa única cuando las espiras se acercan entre sí. Este efecto ocurre porque las líneas de fuerza magnéticas actúan en direcciones opuestas entre espiras adyacentes y, por consiguiente, se anulan cuando las espiras están próximas una a la otra.

![inductor basico](https://user-images.githubusercontent.com/117534483/219696556-7d45986d-8389-4fd2-b7a4-bd9c7c0a5653.jpg)

Inductancia:

Cuando fluye corriente a través de un inductor, se establece un campo electromagnético. Cuando cambia la corriente, el campo electromagnético también cambia. Un incremento de la corriente amplía el campo electromagnético, y una disminución de la corriente lo reduce. Por consiguiente, una corriente cambiante produce un campo electromagnético cambiante alrededor del inductor. A su vez, el campo electromagnético cambiante provoca un voltaje inducido a través de la bobina en una dirección que se opone al cambio de corriente. Esta propiedad se llama autoinductancia, pero en general se conoce simplemente como inductancia, simbolizada mediante L.

La inductancia es una medida de la capacidad que tiene una bobina para establecer un voltaje inducido a consecuencia de un cambio en su corriente, y que dicho voltaje inducido actúe en dirección opuesta al cambio de corriente.

TIPOS DE INDUCTORES: Los inductores son elaborados en una diversidad de formas y tamaños. Básicamente, caen dentro de dos categorías generales: fijos y variables. Tanto los inductores fijos como los variables se clasifican de acuerdo con el tipo de material de su núcleo. Tres tipos comunes son el núcleo de aire, el núcleo de hierro, y el núcleo de ferrita. Cada uno tiene un símbolo único. Los inductores ajustables (variables) disponen, en general, de un ajuste tipo tornillo que mueve un núcleo deslizante hacia dentro y hacia fuera y, por tanto, cambia la inductancia. Existe una amplia variedad de inductores. Los inductores fijos pequeños se encapsulan con frecuencia en un material aislante que protege el fino alambre de la bobina. Los inductores encapsulados tienen una apariencia similar a un resistor.

![INDUCTOR 2](https://user-images.githubusercontent.com/117534483/219696652-47919c5e-2f8d-4ab3-9107-7477ef5eee46.jpg)

INDUCTORES EN SERIE Y EN PARALELO: Cuando se conectan inductores en serie, la inductancia total aumenta. Cuando se conectan en paralelo, la inductancia total disminuye.

Inductancia total en serie: Cuando se conectan inductores en serie, la inductancia total, LT, es la suma de las inductancias individuales. La fórmula para LT se expresa en la siguiente ecuación para el caso general de n inductores en serie:

LT=L1+L2+L3+...+Ln

Inductancia total en paralelo: Cuando se conectan inductores en paralelo, como en la figura 13-16, la inductancia total es menor que la inductancia más pequeña. La fórmula general establece que el recíproco de la inductancia total es igual a la suma de los recíprocos de las inductancias individuales.

LT=1/((1/L1)+(1/L2)+(1/L3)+...+(1/Ln))

INDUCTORES EN CIRCUITOS DE CD: El campo electromagnético de un inductor guarda energía cuando se conecta a una fuente de voltaje de cd. La acumulación de corriente a través del inductor ocurre de una forma predecible, la cual depende de la constante de tiempo determinada por la inductancia y la resistencia presentes en un circuito.

La constante de tiempo RL Como la acción básica del inductor es desarrollar un voltaje que se oponga a un cambio de su corriente, se deduce que la corriente no puede cambiar de modo instantáneo en un inductor. Es necesario que transcurra cierto tiempo para que la corriente cambie de un valor a otro. La constante de tiempo RL determina la rapidez a la cual cambia la corriente. La constante de tiempo RL es un intervalo fijo igual a la razón de la inductancia a la resistencia.

Su formula es: t=L/R

Corriente en un inductor Corriente creciente En un circuito RL en serie, la corriente se incrementará hasta aproximadamente un 63% de su valor total en un intervalo de constante de tiempo una vez que se aplica el voltaje. Esta acumulación de corriente es análoga a la acumulación de voltaje en un capacitor durante la carga en un circuito RC; ambas siguen una curva exponencial y alcanzan porcentajes aproximados de la corriente final.

El cambio de corriente durante cinco intervalos de constante de tiempo. Cuando la corriente alcanza su valor final en 5t, deja de cambiar. En ese momento, el inductor actúa como un cortocircuito (excepto por la resistencia de devanado) con una corriente constante. El valor final de la corriente es:

If = Vs / R = 10V / 1.0 kohm = 10 mA

INDUCTORES DE CIRCUITOS DE CA: Un inductor deja pasar corriente alterna con una cantidad de oposición llamada reactancia inductiva que depende de la frecuencia de la corriente alterna. El concepto de derivada se introdujo en el capítulo 12, y la expresión para voltaje inducido en un inductor ya se formuló en la ecuación anterior. Utilizaremos dichos elementos otra vez en esta sección.

En circuitos inductivos, una corriente sinusoidal siempre induce voltaje sinusoidal. Por consiguiente, es posible graficar el voltaje con respecto a la corriente si se conocen los puntos en la curva de corriente donde el voltaje es de cero y donde es máximo. Advierta que el voltaje se adelanta en 90° con respecto a la corriente. Esto siempre es cierto en un circuito puramente inductivo.

Potencia en un inductor Tal como previamente fue analizado, un inductor guarda energía en su campo magnético cuando a través de él fluye corriente. Un inductor ideal (suponiendo que no hay resistencia de devanado) no disipa energía, sólo la guarda. Cuando se aplica un voltaje de ca a un inductor ideal, el inductor almacena energía durante una parte del ciclo; en seguida la energía guardada regresa a la fuente durante otra parte del ciclo. En un inductor ideal no se pierde energía neta a causa de la conversión en calor. La siguiente imagen muestra la curva de potencia que resulta de un ciclo de corriente o de voltaje en el inductor.

![3 potencia de un inductor](https://user-images.githubusercontent.com/117534483/219696748-111c47c2-542f-40b8-9b73-4837c79458f5.jpg)

*  CAPITULO 14 : TRANSFORMADORES 

INDUCTANCIA MUTUA: 

Cuando se colocan dos bobinas muy cercanas entre sí, el campo electromagnético variante producido por la corriente que fluye por una bobina provocará un voltaje inducido en la segunda bobina a causa de la inductancia mutua presente entre las dos bobinas.

Coeficiente de acoplamiento El coeficiente de acoplamiento, k, entre dos bobinas es la relación de las líneas de fuerza magnéticas (flujo) producidas por la bobina 1, y que enlazan la bobina 2 (f1-2), con el flujo total producido por la bobina 1 (f1).

k = f1-2/f1

EL TRANSFORMADOR BÁSICO: Un transformador básico es un dispositivo eléctrico construido a partir de dos bobinas de alambre (devanados) acopladas magnéticamente entre sí, de modo que existe inductancia mutua para la transferencia de potencia de un devanado al otro.

En la primera imagen se muestra el diagrama esquemático de un transformador. Como puede observarse, una bobina se llama devanado primario y la otra devanado secundario. La fuente de voltaje se aplica al devanado primario y la carga se conecta al devanado secundario, como indica la segunda imagen. El devanado primario es el devanado de entrada y el secundario es el devanado de salida. Es común referirse al lado del transformador que tiene la fuente de voltaje como primario y al lado que tiene el voltaje inducido como secundario.

![4 imagenes inductancias](https://user-images.githubusercontent.com/117534483/219696871-dac8c37a-a7e3-4bb7-a168-cfef71416c71.jpg)

TRANSFORMADORES ELEVADORES Y REDUCTORES: Un transformador elevador tiene más vueltas en su devanado secundario que en el primario y se utiliza para incrementar voltaje de ca. Un transformador reductor tiene más vueltas en su devanado primario que en el secundario y se utiliza para reducir voltaje de ca.

EL TRANSFORMADOR ELEVADOR Un transformador donde el voltaje secundario es más grande que el voltaje primario se llama transformador elevador. La cantidad en que se eleva el voltaje depende de la relación de vueltas. La relación del voltaje secundario (Vsec) al voltaje primario (Vpri) es igual a la relación del número de vueltas presente en el devanado secundario (Nsec) al número de vueltas que haya en el devanado primario (Npri).

Vsec / Vpri = Nsec / Npri

Recordemos que Nsec/Npri define la relación de vueltas, n. Por consiguiente, a partir de esta relación:

Vsec = n * Vpri

CARGA DEL DEBANADO SECUNDARIO: Cuando se conecta una carga resistiva al devanado secundario de un transformador, la relación de la corriente de carga (secundario) y la corriente en el circuito primario se determina por relación de vueltas.

Cuando se conecta un resistor de carga al devanado secundario, fluye corriente a través del circuito secundario resultante a causa del voltaje inducido en la bobina secundaria. Es posible demostrar que la relación de la corriente primaria, Ipri, a la corriente secundaria, Isec, es igual a la relación de vueltas, tal como expresa la siguiente ecuación:

Ipri / Isec = n

Una manipulación de los términos de la ecuación anterior resulta en la ecuación siguiente, la cual muestra que Isec es igual a Ipri multiplicada por el recíproco de la relación de vueltas.

Isec = (1/n) * Ipri

Cuando se conecta una carga al devanado secundario de un transformador, la potencia transferida a la carga nunca puede ser mayor que la potencia en el devanado primario. Para un transformador ideal, la potencia suministrada al primario es igual a la potencia suministrada por el secundario a la carga. Cuando se consideran las pérdidas, algo de potencia se disipa en el transformador en lugar de en la carga; por consiguiente, en la carga la potencia siempre es menor que en el primario. La potencia depende del voltaje y de la corriente, y no puede haber incremento de potencia en un transformador. Por consiguiente, si el voltaje se eleva, la corriente se reduce, y viceversa. En un transformador ideal, la potencia en el secundario es igual a la potencia en el primario independientemente de la relación de vueltas, tal como indican las siguientes ecuaciones. La potencia suministrada al primario es:

Ppri = Vpri * Ipri = Psec

y la potencia suministrada a la carga es:

Psec = Vsec * Isec

CARGA REFLEJADA: Desde el punto de vista del primario, una carga conectada a través del devanado secundario de un transformador parece tener una resistencia que no es necesariamente igual a la resistencia real de la carga. La carga real se “refleja” en el lado primario conforme lo determina la relación de vueltas. Esta carga reflejada es lo que la fuente primaria ve efectivamente, y determina la cantidad de corriente en el primario.

El concepto de carga reflejada se ilustra en la imagen. La carga (RL) en el secundario de un transformador se refleja en el primario a causa de la acción del transformador. La carga aparece ante la fuente en el primario como si fuera una resistencia (Rpri) con un valor determinado por la relación de vueltas y el valor real de resistencia de la carga. La resistencia Rpri se llama resistencia reflejada.

![5 imagen](https://user-images.githubusercontent.com/117534483/219697026-c7a54a3d-11bb-4fd4-8903-ef9c7e9d8302.jpg)

IGUALACION DE IMPEDANCIA: Una aplicación de los transformadores se encuentra en la igualación de una resistencia de carga frente a una resistencia de fuente para lograr una transferencia de potencia máxima. Esta técnica se llama igualación de impedancia. Recuerde que el teorema de transferencia de potencia máxima se estudió en el capítulo 8. En sistemas de audio, a menudo se utilizan transformadores igualadores de impedancia para conseguir la cantidad máxima de potencia disponible del amplificador al altavoz.

CARACTERISTICAS DE UN TRANSFORMADOR NO IDEAL (TRANSFORMADOR REAL): La operación de un transformador fue analizada desde un punto de vista ideal. Es decir, la resistencia de devanado, la capacitancia de devanado, y las características no ideales del núcleo se omitieron y el transformador fue tratado como si su eficiencia fuera del 100%. Para estudiar los conceptos básicos y en muchas aplicaciones, el modelo ideal es válido. Sin embargo, el transformador práctico tiene varias características no ideales.

Pérdidas en el núcleo Siempre hay algo de conversión de energía en el material del núcleo de un transformador práctico. Esta conversión aparece como calentamiento de los núcleos de ferrita y hierro, pero no ocurre en núcleos de aire. Una parte de esta conversión de energía tiene lugar a causa de la inversión continua del campo magnético provocada por la dirección cambiante de la corriente en el primario; este componente de la conversión de energía se conoce como pérdida por histéresis. El resto de la conversión de energía en calor se debe a corrientes parásitas producidas cuando se induce voltaje en el material del núcleo mediante el flujo magnético cambiante, de acuerdo con la ley de Faraday. Las corrientes parásitas se presentan en patrones circulares en la resistencia del núcleo, por lo que se produce calor. Esta conversión en calor se reduce en gran medida con el uso de una construcción laminada de los núcleos de hierro. Las delgadas capas de material electromagnético están aisladas entre sí para reducir al mínimo la acumulación de corrientes parásitas, al confinarlas en una pequeña área, y para mantener las pérdidas en el núcleo a un mínimo.

TRANSFORMADORES CON TOMAS Y DEVANADOS MULTIPLES: El transformador básico tiene distintas variaciones importantes. Éstas incluyen transformadores con tomas, transformadores con múltiples devanados, y autotransformadores. Los voltajes entre uno u otro extremo del devanado secundario y la toma central son, en cualquier instante, iguales en magnitud pero opuestos en polaridad. Aquí, por ejemplo, en algún instante en el voltaje sinusoidal, la polaridad a través de todo el devanado secundario es como se muestra (extremo superior +, inferior -). En la toma central, el voltaje es menos positivo que en el extremo superior, pero más positivo que en el extremo inferior del secundario. Por consiguiente, medido con respecto a la toma central, el extremo superior del secundario es positivo y el inferior es negativo. Esta configuración de toma central se utiliza en muchos rectificadores de fuente de potencia donde el voltaje de ca se transforma en cd. Algunos transformadores tienen tomas en el devanado secundario en puntos diferentes del centro eléctrico. Asimismo, en ocasiones se utilizan tomas únicas y múltiples en el primario y el secundario para ciertas aplicaciones, tales como transformadores igualadores de impedancia que normalmente tienen un primario con toma central.

# 3.EXPLICACIÓN Y RESOLUCIÓN DE EJERCICIOS O PROBLEMAS

# CAPITULO 13 : -Ejercicios pares

![13-1](https://user-images.githubusercontent.com/117534483/219700922-e748e1c6-ec13-4bcf-baa3-9d5be2e09199.jpg)

![13-2](https://user-images.githubusercontent.com/117534483/219700924-a12d9213-d811-43d4-83a5-0e89a6cea993.jpg)

![13-3](https://user-images.githubusercontent.com/117534483/219700925-90fa65f0-b631-4c22-bc3d-efdfb9cce9b8.jpg)

![13-4](https://user-images.githubusercontent.com/117534483/219700930-986a1960-767d-456e-82f1-a217a8c6086c.jpg)

![13-5](https://user-images.githubusercontent.com/117534483/219700932-4ed57d0b-8cee-48bf-afe1-38defa2f072b.jpg)

![13-6](https://user-images.githubusercontent.com/117534483/219700933-a4e0497e-deef-455b-a1dc-87bf871eb67a.jpg)

![13-7](https://user-images.githubusercontent.com/117534483/219700934-a526f107-5ee6-428a-9c69-56f2c20a12b2.jpg)

![13-8](https://user-images.githubusercontent.com/117534483/219700935-a94c2e29-cb88-4d3e-a36e-e19e51777f69.jpg)

![13-9](https://user-images.githubusercontent.com/117534483/219700939-f51a155e-06bc-42a3-bb8d-fdeb1e053762.jpg)

# CAPITULO 14 : -Ejercicios pares

![14-1](https://user-images.githubusercontent.com/117534483/219701018-19fe9272-6552-4d1b-8afd-da76a375840c.jpg)

![14-2](https://user-images.githubusercontent.com/117534483/219701022-18dc7d7d-c9cf-4348-bab0-952a09a8901d.jpg)

![14-3](https://user-images.githubusercontent.com/117534483/219701025-2668088b-ea6a-4258-9ba0-71fef283a599.jpg)

![14-4](https://user-images.githubusercontent.com/117534483/219701029-59bd28ae-ae60-4df4-9481-d8b42aeb38e8.jpg)

![14-5](https://user-images.githubusercontent.com/117534483/219701031-db1925bc-ec1a-46d5-a497-6e1801e81ef9.jpg)

![14-6](https://user-images.githubusercontent.com/117534483/219701033-5217ba5f-7c43-4185-ba0e-cfa8e03e4565.jpg)

![14-7](https://user-images.githubusercontent.com/117534483/219701036-fa1f83d4-83a8-475b-a716-95e89db8f168.png)

# 4.VIDEO

- https://youtu.be/GO1QjpPV9tA

# 5.CONCLUSIONES

◆ La inductancia es una medida de la capacidad de una bobina para establecer voltaje inducido como resultado de un cambio en su corriente.

◆ Un inductor se opone al cambio de su propia corriente.

◆ La ley de Faraday establece que el movimiento relativo entre un campo magnético y una bobina induce cierto voltaje en la bobina.

◆ La cantidad de voltaje inducido es directamente proporcional a la inductancia y a la rapidez de cambio en la corriente.

◆ La ley de Lenz establece que la polaridad del voltaje inducido es tal que la corriente inducida resultante fluye en una dirección que se opone al cambio del campo magnético que la produjo.

◆ Un inductor guarda energía en su campo magnético.

◆ Un henry es la cantidad de inductancia cuando la corriente, que cambia a razón de un ampere por segundo, induce un volt en el inductor.

◆ La inductancia es directamente proporcional al cuadrado de la cantidad de vueltas, a la permeabilidad, y al área de sección transversal del núcleo. Es inversamente proporcional a la longitud del núcleo.

◆ La permeabilidad de un material de núcleo indica la capacidad del material para establecer un campo magnético.

◆ La constante de tiempo de un circuito RL dispuesto en serie es la inductancia dividida entre la resistencia.

◆ En un circuito RL, el voltaje y la corriente crecientes o menguantes en un inductor provocan un cambio del 63% durante cada intervalo de constante de tiempo

◆ Un transformador normal consta de dos o más bobinas acopladas magnéticamente en un núcleo común.

◆ Existe inductancia mutua entre dos bobinas acopladas magnéticamente.

◆ Cuando cambia la corriente en una bobina, se induce voltaje en la otra bobina.

◆ El primario es el devanado conectado a la fuente, y el secundario es el devanado conectado a la carga.

◆ El número de vueltas en el primario y el número de vueltas en el secundario determinan la relación de vueltas.

◆ Las polaridades relativas de los voltajes primario y secundario son determinadas por la dirección de los devanados alrededor del núcleo.

◆ La relación de vueltas de un transformador elevador es mayor que 1.

◆ La relación de vueltas de un transformador reductor es menor que 1.

◆ Un transformador no puede incrementar la potencia.

◆ En un transformador ideal, la potencia de la fuente (potencia entrada) es igual a la potencia suministrada a la carga (potencia de salida).

◆ Si el voltaje se eleva, la corriente se reduce y viceversa

# 6.BIBLIOGRAFÍA

*  Floyd (8va Ed)(2007). Principios de circuitos electricos. Pearson Education.

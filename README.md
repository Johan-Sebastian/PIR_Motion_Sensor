# PIR_Motion_Sensor

# Johan Sebastian Vazquez Gutierrez

<a target="_top"><img src= "https://i.imgur.com/uWteCty.gif" width="120" height="120" alt="Logo GitHub" border="0" /></a>

Los sensores PIR le permiten detectar movimiento, casi siempre se usan para detectar si un humano se ha movido dentro o fuera del alcance de los sensores. Son pequeños, económicos, de bajo consumo, fáciles de usar y no se desgastan. Por esa razón, se encuentran comúnmente en electrodomésticos y aparatos que se usan en los hogares o negocios. A menudo se denominan PIR, "infrarrojos pasivos",
Sensores "piroeléctricos" o de "movimiento IR".

<a target="_top"><img src= "https://content.instructables.com/ORIG/FXY/EQAU/FYIZHAJN/FXYEQAUFYIZHAJN.jpg?auto=webp&frame=1&crop=3:2&width=807&fit=bounds&md=6e7ab9813972c99e99532482e1e81e80" width="280" height="220" alt="Logo GitHub" border="0" /></a>

Estas estadísticas son para el sensor PIR en la tienda de Adafruit, que es muy parecido al de Parallax. Casi todos los PIR tendrán especificaciones ligeramente diferentes, aunque todos funcionan prácticamente igual.


|  Estadísticas básicas                        |
|----------------------------------------------|
| Size: Rectangular                            | 
| Output: Digital pulse high (3V) when triggered (motion detected) digital low when idle (no motion detected). Pulse lengths are determined by resistors and capacitors on the PCB and differ from sensor to sensor.             |
| Sensitivity range: up to 20 feet (6 meters) 110 degrees x 70 degrees detection range | 
| Power supply: 3.3V - 5V input voltage                     |
| BIS0001 Datasheet (the decoder chip used)                  | 
| RE200B datasheet (most likely the PIR sensing element used)             |
| NL11NH datasheet (equivalent lens used)             |
| Parallax Datasheet on their version of the sensor              |

<a target="_top"><img src= "https://content.instructables.com/ORIG/FXW/S6GH/FYNTA23Z/FXWS6GHFYNTA23Z.jpg?auto=webp&frame=1&fit=bounds&md=88e0a0b06d303bad31dc6b6e697f0507" width="280" height="220" alt="Logo GitHub" border="0" /></a>

El sensor PIR en sí tiene dos ranuras, cada ranura está hecha de un material especial que es sensible a los IR. La lente utilizada aquí realmente no está haciendo mucho, por lo que vemos que las dos ranuras pueden 'ver' más allá de cierta distancia (básicamente, la sensibilidad del sensor). Cuando el sensor está inactivo, ambas ranuras detectan la misma cantidad de IR,
la cantidad ambiental radiada desde la habitación, las paredes o el exterior. Cuando pasa un cuerpo caliente como un humano o un animal, primero intercepta la mitad del sensor PIR, lo que provoca un cambio diferencial positivo entre las dos mitades. Cuando el cuerpo tibio sale del área de detección, ocurre lo contrario,
por lo que el sensor genera un cambio diferencial negativo. Estos pulsos de cambio son lo que se detecta.1

| El propio sensor PIR             |
|----------------------------------------------|
| El sensor IR en sí está alojado en una lata de metal sellada herméticamente para mejorar la inmunidad al ruido/temperatura/humedad. Hay una ventana hecha de material transmisor de IR (típicamente silicona recubierta ya que es muy fácil de conseguir) que protege el elemento sensor. Detrás de la ventana están los dos sensores balanceados.             |


Referencia:
https://www.instructables.com/PIR-Motion-Sensor-Tutorial/

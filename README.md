# Mareas

Las mareas son olas con período muy largo que se mueven a través de los océanos como respuesta a las fuerzas gravitacionales, centrífugas e inerciales que actúan sobre cada porción del océano. Además del campo gravitacional de la Tierra que lo mantiene adherido a ella, el océano siente el efecto gravitacional a distancia de los cuerpos celestes, particularmente de la Luna (por su cercanía) y del Sol (por su gran masa). Se suman a éstos las fuerzas inerciales debidas a los movimientos de rotación de los sistemas Tierra-Luna y Tierra-Sol, que giran, cada uno, en torno a un centro de masa común.

Así, cada porción de fluido del océano está sujeta a fuerzas que nunca están en equilibrio. La fuerza resultante, la suma vectorial de todas ellas, es la que genera la marea: la "fuerza generadora (o generatriz) de la marea".

### Teoría estacionaria

Podemos imaginar que si la tierra no rotara sobre su propio eje se presentarían dos abultamientos en el nivel del mar, uno en el eje que une al tierra y la luna (o el sol) y el otro en el lado contrario. Como la tierra gira sobre su propio eje estos abultamientos se van moviendo conforme la tierra rota pero la velocidad con que viaja una ola de marea, que está determinada por la raíz cuadrada del producto de **g * H**, donde **g** es la gravedad y **H** la profundidad, que provoca que en algunos sitios la marea tenga mayor amplitud y en otros menor.

La marea se puede descomponer en una suma de contribuciones, por ejemplo una debida al tiempo en que tarda un meridiano en que el sol lo cruce (24 hrs), o que la lune lo cruce (23.93 hrs)

Las mareas se originan en los océanos y progresan hacia las costas donde se manifiestan como el ascenso y descenso de la superficie del mar.

Cuando la parte más alta de la ola (cresta) alcanza un lugar en específico, ocurre **marea alta** (o _pleamar_); **la marea baja** (o _bajamar_) corresponde a la parte más baja de la ola (valle). La diferencia de altura entre la _pleamar_ y _bajamar_ se denomina **rango de marea**. 

El rango de marea es una característica de cada lugar y está determinado por la forma de la línea de costa, la batimetría regional. Así por ejemplo, el mayor rango de marea en México se observa en el extremo norte del Golfo de California debido a que al avanzar la marea en el Golfo de California va encontrando aguas más someras y un ancho menor del Golfo; y el menor rango de marea se presenta en Cozumel, donde se registra la marea del orden de centímetros.

![alt text](http://www.mareografico.unam.mx/portal/img/mapaRangoMarea1.png)

## "Mareas vivas" y "mareas muertas"?

Cada dos semanas, aproximadamente, el Sol, la Tierra y la Luna están alineados, lo que implica que los puntos 'subsolar' y 'antisolar' se alinean con los puntos lunares correspondientes (lunar y antilunar). Cuando ello ocurre, se dice que la marea está en fase porque los abultamientos lunar y solar coinciden y las amplitudes se superponen. Esta es la '**marea viva**'. Una semana después del alineamiento, el Sol y la Luna se encuentran en direcciones perpendiculares con respecto a la Tierra, los abultamientos están completamente fuera de fase y las amplitudes correspondientes se contraponen. La amplitud de la marea es mínima en esta situación y por ello se le denomina '**marea muerta**'.

![alt text](http://www.mareografico.unam.mx/portal/img/mareasvivas.png "Mareas vivas")     ![alt text](http://www.mareografico.unam.mx/portal/img/mareasmuertas.png "Mareas Muertas")


### Tipos de marea

Cuando se habla de tipos de marea se refiere uno a si por lo general se observan en un lugar dos máximos y dos mínimos por día o solamente uno. Esto depende de si predominan las componentes diurna o las semidiurnas en la marea. 

Para determinar el tipo de marea, se acostumbra determinarlo con el cociente:

TM=(O1+K1)/(M2+S2)

Si el cociente es:

 
* &lt; 1.5         : la marea es mixta, predominantemente diurna
* de 1.5 a 3.0  : mixta
* &gt;  3.0       : semidiurna 

En el Golfo de México predomina la marea diurna, en el Caribe la semidiurna y el Pacífico la mixta predominantemente semidiurna. Sin embargo, hay zonas que se salen del patrón como por ejemplo, Campeche en el Golfo de México, y Santa Rosalía en el Golfo de California.

![alt text](http://www.mareografico.unam.mx/portal/img/mapaTipoMarea1.png)

![alt text](https://upload.wikimedia.org/wikipedia/commons/thumb/9/93/Tides_Fourier_Transform.png/1024px-Tides_Fourier_Transform.png)

Ejemplo de un espectro de Fourier en donde se observa que la frecuencia M2 es la que tiene mayor energía (en algún sitio determinado). Le siguen otras componentes como la N2, O1, K1, S2. Nótese que las frecuencias está cerca de 1c/día, 2c/día, 3 c/dia y 4 c/día, es decir 24, 12 8 y 6 hrs. No todas las frecuencias están en estos grupos, pero están las más importantes. 


**Existen decenas de componentes de marea pero las principales son:**

* #### Semidiurnas

 ** **M2** :  Lunar semidiurna 12.42 hrs
* **S2** :  Solar semidiurna 12 hrs 
* **N2** :  Lunar elíptica semidiurna 12.65

#### Diurnas

* **K1** :  Soli-lunar diurna 23.93
* **O1** :  Lunar 25.82
* **P1** :  Solar 24.07

(ver tabla completa en : https://en.wikipedia.org/wiki/Theory_of_tides)

![alt text](http://132.248.8.68/jzavala/TemSelModNum/Acapulco_30dias_marea.png)

En la gráfica se observan dos períodos de mareas vivas y dos de mareas muertas para los últimos 30 días en Acapulco.


## **Referencias**

http://www.mareografico.unam.mx/

https://oceanservice.noaa.gov/education/kits/tides/tides01_intro.html

https://en.wikipedia.org/wiki/Theory_of_tides


# Cálculo del nivel del mar

La variación del nivel del mar en un lugar en específico se calcula con una suma de _varias componentes_, y se puede representar por la expresión:
```mathjax
$ \sum = A_0 + A_1sin(\omega t)+A_2cos(\omega t) $```


Iniciamos ajuntando la componente de marea **M2** con:
```mathjax
$ M_2(Ac) = A_0 + A_1sin(\omega t)+A_2cos(\omega t) $```

Resolviendo sistemas de ecuaciones

Ax=b

incognitas

Inline: $ M_2(Ac) = A_0 + A_1sin(\omega t)+A_2cos(\omega t) $

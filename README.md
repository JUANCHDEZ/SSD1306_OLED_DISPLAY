# SSD1306 OLED display

Básicamente lo que hace el SSD1306 es comunicar con el microcontrolador para obtener los datos y enviarlos a la pantalla OLED para que dibuje esos datos. La comunicación entre el SSD1306 y el microcontrolador, ya sea un Arduino o un ESP8266, se realiza mediante SPI o I2C. 

### ¿Cómo funciona una pantalla OLED?
OLED funciona como un LED pero usa moléculas orgánicas en lugar de otros semiconductores para producir luz. La electricidad fluye del cátodo al ánodo a través de las capas emisiva y conductora produciendo luz de color. Los materiales OLED primarios son amarillo y azul. Luego se usan filtros de color para hacer el resto del color.

 
### Ventajas de los OLED
La tecnología de pantalla OLED tiene una calidad de imagen extremadamente alta y amplios ángulos de visión. Es por eso que se usa en productos de gama alta como los teléfonos Apple más nuevos y premium. Debido a que cada píxel en una pantalla OLED se puede controlar individualmente, las pantallas OLED tienen una resolución más alta. Además, los OLED no tienen retroiluminación, por lo que su consumo de energía también es menor que el LCD. También son pantallas que ahorran energía porque, en lugar de tener una luz de fondo encendida todo el tiempo, solo se emite energía cuando se enciende un píxel. También debido a la falta de retroiluminación, hay pantallas OLED flexibles. Las luces de fondo limitan a los diseñadores a solo pantallas planas. OLED emite luz propia, por lo que sus dispositivos pueden ser enrollables o plegables.

![](https://www.scienceabc.com/innovation/what-is-oled-and-how-does-it-work.html.jpg)

### Marco teorico

El sensor SSD1306 OLED display es un tipo de pantalla OLED (Organic Light Emitting Diode) que se utiliza en una amplia variedad de aplicaciones, desde dispositivos portátiles hasta electrónica de consumo y aplicaciones industriales. Para comprender mejor el funcionamiento de este sensor, es necesario tener en cuenta algunos conceptos importantes relacionados con la tecnología OLED.

Un OLED es una tecnología de visualización que utiliza materiales orgánicos para generar luz en respuesta a una corriente eléctrica. A diferencia de las pantallas LCD (Liquid Crystal Display), los OLED no requieren una luz de fondo separada, lo que los hace más delgados y eficientes en cuanto al consumo de energía. En lugar de una matriz de píxeles retroiluminados, una pantalla OLED consta de una serie de capas de materiales orgánicos que generan luz cuando se aplica una corriente eléctrica.


![imagen](https://programarfacil.com/wp-content/uploads/2020/02/pineado-pantalla-oled-arduino-esp8266-02.jpg)


El sensor SSD1306 OLED display en particular es un tipo de controlador de pantalla OLED que se utiliza para controlar y gestionar una pantalla OLED de tipo monocromática de 128x64 píxeles. Este controlador se comunica a través de una interfaz de comunicación serial (SPI) y se puede programar para mostrar texto, gráficos y otros tipos de información.

En términos de su arquitectura interna, el SSD1306 OLED display está construido con una matriz de transistores orgánicos que controlan el flujo de corriente a través de los materiales orgánicos de la pantalla. Estos transistores se organizan en una matriz bidimensional, lo que permite controlar individualmente cada píxel de la pantalla. El controlador SSD1306 se encarga de enviar los datos de imagen a la pantalla y de controlar el brillo y el contraste.

![imagen](https://www.sujetamelachispa.es/wp-content/uploads/2021/01/oled2Recortada-3-768x519.jpg)

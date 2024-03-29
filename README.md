# ProjectAIoT_2024
# Seguridad en casa
## Integrantes
|   Nombres Integrantes    | Número Control |
|--------------------------|----------------|
| Laura Berenice Tapia Cid | 1222100476     |
| Carlos Manuel Palma Muñoz| 1222100814     |
| Maribel Ramirez Torres   | 1222100479     |

## Carta de liberacion del proyecto
- Dirijida al docente
- Debe de expresar las funcionalidades que tiene el proyecto
- Nombres de los integrantes que participaron en el proyecto
- Es una imagen jpg o png.
- Firmada por el empresario o docente a la UTNG, agradeciendo la contribucion de la UTNG.
- Hoja menbretada(logo de la empresa, direccion y contacto)

## Lista del Hardware utilizado
| Id | Componente | Descripción | Imagen | Cantidad | Costo total |
|----|------------|-------------|--------|----------|-------------|
| 1  |Rasberry PI |es una computadora de bajo costo y con un tamaño compacto, del porte de una tarjeta de crédito, puede ser conectada a un monitor de computador o un TV, y usarse con un mouse y teclado estándar. Es capaz de hacer la mayoría de las tareas típicas de un computador de escritorio, desde navegar en internet, reproducir videos en alta resolución, manipular documentos de ofimática, hasta reproducir juegos.|![image](https://github.com/Lau1907/ProjectAIoT_2024/assets/130590443/9cb8b5c4-d195-40ff-a6e3-18ccfd50aae8)|1|$1589|
| 2  |Sensor de Temperatura|son componentes eléctricos y electrónicos que, en calidad de sensores, permiten medir la temperatura mediante una señal eléctrica determinada.|![image](https://github.com/Lau1907/ProjectAIoT_2024/assets/130590443/a0a7771d-e3ed-49b1-bb8f-e763573016b9)|1|$50|
| 3  |Sensor de gas natural|Los detectores de gas utilizan un sensor para cuantificar la agrupación de gases específicos en el clima. |![image](https://github.com/Lau1907/ProjectAIoT_2024/assets/130590443/20b9ac5a-bcc9-48d3-9d55-2968bd190e43)|1|$50|
| 4  |Sensor de Movimiento|es un dispositivo electrónico que pone en funcionamiento un sistema (encendido o apagado) cuando detecta movimiento en el área o ambiente en el que está instalado.|![image](https://github.com/Lau1907/ProjectAIoT_2024/assets/130590443/eca5771a-8e4d-48f0-aa4f-33bd1fd0ef8a)|1|$77|
| 5  |Sensor de luz ambiental|se utiliza para detectar el haz de luz reflejado desde el objeto.|![image](https://github.com/Lau1907/ProjectAIoT_2024/assets/130590443/b31987e5-2f83-465c-b26b-ede135d84775)|1|$48|
| 6  |ESP 32|El módulo ESP32 es una solución de Wi-Fi/Bluetooth todo en uno, integrada y certificada que proporciona no solo la radio inalámbrica, sino también un procesador integrado con interfaces para conectarse con varios periféricos.|![image](https://github.com/Lau1907/ProjectAIoT_2024/assets/130590443/9035be2e-1764-4c1e-96ce-f53d9c3490cb)|1|$160|
| 7  |Cables|es un cable con un conector en cada punta, que se usa normalmente para interconectar entre sí los componentes en una placa de pruebas.|![image](https://github.com/Lau1907/ProjectAIoT_2024/assets/130590443/2eeadecd-d56e-4405-9483-6aa8a06bdf01)|60|$60|

## Lista del Software utilizado
| Id | Software | Version | Tipo |
|----|----------|---------|------|
|  1 |Node-RED||      |
|  2 |MQTT|         |      |
|  3 |MicroPython|         |      |

## Visión del proyecto
¿Como generar la visión del proyecto?

Como es usual en agilidad la comunicación se ve enormemente potenciada cuando acompañamos nuestro cometido con elementos visuales. Arriba a la izquierda el resultado de un ejercicio de uno de los cursos, en que el grupo expuso una solución en la que a través de big data se pueden controlar los procesos de incapacidad laboral temporal.
Para generar este mensaje se debe de dar respuesta a estos tres conceptos:

    Quién es el público: ¿Quién va a utilizar tu producto?
    Qué problema tiene: ¿Qué problema o necesidad latente se va a satisfacer?
    Qué solución se ofrece: ¿Cómo se va a satisfacer?

Alex Brown propone el siguiente patrón como una forma de escribir o crear una visión: 

    PARA <cliente objetivo>
    QUIEN <declaración de necesidad>
    EL <nombre de producto> QUE ES UN/A <categoría del producto>
    QUE <beneficio clave, razón de peso para comprar o usar>
    A DIFERENCIA DE <competidor/alternativa>
    NUESTRO PRODUCTO <declaración diferencial>

Ejemplo de una visión:
PARA sociedades propietarias de drones
    QUIEN tienen necesidad de asegurar sus drones y cubrir su responsabilidad civil
    EL producto prodrone QUE ES UN seguro gestionable de forma on-line
    QUE es un producto específico para los profesionales de drones
    A DIFERENCIA DE nuestra competencia que solo dispone de un producto de contratación presencial
    NUESTRO PRODUCTO es totalmente personalizable de forma on-line en cuanto a coberturas y duración se refiere

Como consejo derivado de mi experiencia para la utilización de este patrón de forma positiva, si hay elementos en negativo en la parte de A DIFERENCIA DE, propongo escribirlos en positivo en NUESTRO PRODUCTO, convierte nuestro mensaje en más positivo y por tanto en más poderoso.

"Un enunciado de visión exitoso
es lo suficientemente convincente
para ser ampliamente compartido,
conciso y fácil de recordar"
Referencia:

    Menzinsky, A. (2017). ¿Cómo se realiza la visión del producto?. Scrum.menzinsky.com. Retrieved 19 January 2017, from ¿Cómo se realiza la visión del producto?

## Conexiones
- Imagenes de Wokwi, Fritzing, o de otro software que me permita mostrar las conexiones del circuito.
- Rasberry PI
- ESP 32

## Funcionalidades 
| Id | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
| 1  |El usuario podra identificar mediente el sensor de movimiento cualquier objeto que entre por la puerta o ventana|Alta|            |               |             |
| 2  |El usuario podra detectar fugas de gases peligrosos como el monoxido de carbono o el gas natural|Alta|            |               |             |
| 3  |El usuario podra verificar la humedad y temperatura del hogar|Alta|            |               |             |
| 4  |El usuario tendra la facilidad de encender las luces al momento de que se detecte algun movimiento|Alta||||
| 5  |El usuario podra encender y apagar las luces de acuerdo a la luz ambiental que exista|Alta|
| 6  |El usuario aparte de que pueda detectar movimiento tambien podra capturar imagenes o videos de la camara de seguridad|Alta|

## Prototipo en dibujo
- Coloca la imagen de tu proyecto al iniciar el desarrollo.
- Captura de las pantallas del proyecto
- Video demostrativo de las funcionalidades del proyecto
- Codigo fuente (PROHIBIDO PONER COMPRIMIDOS)















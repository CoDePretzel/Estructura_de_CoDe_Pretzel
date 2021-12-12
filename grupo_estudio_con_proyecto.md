# Grupos de Estudio con Libro

## Descripción

Se toma un proyecto que solucione una problemática como referencia.
Ese proyecto se desgloza en distintos componentes que puedan usar elementos de la infraestructura de software.

Por ejemplo
> Osciloscpio con un STM32
> Se desgloza en los siguientes módulos:
> - Leer voltajes con ADC que cumplan con el req del proyecto (puede necesitar acondicionamiento previo para que sea visible por el rango del ADC)
> - Comunicar información a la PC por UART
> - Un graficador en la PC (puede ser python con matplotlib), para mostrar los datos

Cada uno de esos módulos sería un grupo de estudio.

Y cada módulo usará elementos del flujo de desarrollo que se está construyendo.
Por ejemplo
> - Github colaborativo
> - Configuración de Platformio para usar el micro
> - Estándar de código BARR C2018

El proyecto se desgloza para que dure de entre 1 a 3 semanas en desarrollarse.
Las sesiones grupales son 1 vez por semana.
Pero será necesario que cada miembro trabaje durante la semana un espacio de por lo menos 3 horas en total, porque las sesiones en grupo pueden usarse para depuración o para explicación de las implementaciones

Cada que se inicia un grupo de estudio, se define y se comunica, si se hará trabajo entre semana o no, este trabajo típicamente será por separado, cada miembro.

## Proyecto final

Principalmente se va a ver reflejado en código y en prototipo.

Se define como el entregable que permita tener el módulo del proyecto que se haya desglozado.
Siguiendo el ejemplo anterior:
> - Un lector de ADC de 0-5v con resolución de 10 bits, implementado con ATMega2560, usando directamente C y AVR, con PlatformIO y el repositorio de ese código con documentación de ese módulo en el github de la comunidad
> - La documentación asociada en Notion, de cómo es el trabajo en equipo en CoDe Pretzel, es decir, una branch por funcionalidad, luego un Pull Request y un code review asociado por todos los miembros del equipo, así como el uso del estándar Barr-C 2018

## Duración

Sesiones de 1 a 2 horas por semana en equipo
3 horas mínimo de trabajo en solitario en la semana

## Cantidad de Sesiones

1 a 3 por módulo de proyecto, una sesión por semana.

## Comentarios
La idea de la sesión es aclarar dudas durante el desarrollo colaborativo del módulo.
Es decir:
- Cómo se implementó un HAL o un algoritmo
- Dónde buscar recursos para investigar más a fondo un tema (por ejemplo un protocolo I2C)
- Comentar brevemente los bugs que se han tenido, pero no para resolverlos en esa sesión, si no para derivarlos a trabajo durante la semana
- Hacer notas que van a agregarse a la documentación de logros o descubrimientos durante el desarrollo

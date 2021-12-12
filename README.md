![CoDe Pretzel Logo](/icons/logo_xsm.png)
# Estructura de actvidades en la comunidad de sistemas embebidos CoDe Pretzel
### Vigentes desde Septiembre 2021

## Actividades en CoDe Pretzel
A menos que se especifique lo contrario en el evento en particular que se esté publicitando, las actividades tienen las siguientes características.

Se realizan en la sección de `eventos virtuales` en el canal `Sala de reuniones` de nuestro servidor de [Discord](https://discord.gg/uCZVfvHW5w)

Son los **Sábados** a las **12:30 PM** hora Tijuana México (PST/PDT)

>Las ocasiones donde no haya evento programado, este horario se podrá usar para juntas de coordinación y planeación de la comunidad o para juntas de sincronización en grupos de estudio con proyecto.

Las actividades disponibles en la comunidad hasta el momento son:
* [La hora de inglés](la_hora_de_ing.md)
* Pláticas en vivo
	* [Ponente](platicas_con_ponente.md)
	* [Tipo tutorial](platicas_tipo_tutorial.md)
	* [Conversatorio](platicas_tipo_conversatorio.md)
* Grupos de estudio
	* [Con Proyecto](grupo_estudio_con_proyecto.md)
	* [Con Libro](grupo_estudio_con_libro.md)


**Nota:**
> Los readme arriba mencionados de las actividades, requieren un trabajo y actualización continuas, si no son claras, tienen información incorrecta o necesitan modificaciones, pueden pedir un pull request o mandar mensaje a los admins en Discord


## Nuestras redes

Nuestras plataformas principales son [Discord](https://discord.gg/uCZVfvHW5w) y [Reddit](https://www.reddit.com/r/codepretzel/)(aunque aquí apenas empezamos).

Todos los proyectos estarán en nuestro [Github](https://github.com/CoDePretzel)

También tenemos:
* [Twitter](https://twitter.com/PretzelCode)
* [Instagram](https://www.instagram.com/codepretzel/)
* [Página de facebook](https://www.facebook.com/CoDePretzel/)
* [Grupo de facebook](https://www.facebook.com/groups/425161431009869)
* [Youtube](https://www.youtube.com/channel/UC0TMAn1gR83mykrSQmnoAAQ/featured)
* Página de [Linkedin](https://www.linkedin.com/company/CoDePretzel)
* Alianza con [Código Facilito](https://codigofacilito.com/comunidades)
* Directorio en [Comunidades Atlas](https://comunidades.lat/code-pretzel/)

Estamos trabajando en tener cuentas en:
* Notion (Nuestra base de conocimiento estará ahí)

Así como tener una página web donde se pueda tener una referencia de qué es code pretzel y un poco de nuestra historia.

## Objetivo de CoDe Pretzel
Proporcionar un lugar donde crear sistemas embebidos, aprender, compartir entre todos, principiantes y avanzados y en el camino, mostrar el talento latinoamericano.


##  El sueño de CoDe Pretzel (CoDe Pretzel Framework)
Soñamos construir una infraestructura de herramientas, técnicas y configuraciones que nos permita desarrollar software embebido de calidad, con facilidad de replicación, modularidad y con un proceso de desarrollo establecido.

Es decir
1. Una Estructura para hacer to propio código reusable, (No empezar de cero cada vez)
2. Una Forma de organizar tu proyecto (dónde va qué cosa)
3. Un proceso de desarrollo (cómo configurar tus comiplaciones, pruebas y deploy) 
4. Una Propuesta periféricos y técnicas usados en industria (mejoras tu CV y no reinventas la rueda)
5. Cierta Independencia de fabricante (Puedas cambiar de fabricante sin tantísima modificación)

Los siguientes elementos definen un poco mejor los elementos que atañen a cada punto entre paréntesis.
ej. (1,2) se refiere a los puntos 1. Estructura de código reusable, 2. Forma de organizar tu proyecto

### Desarrollo de software colaborativo (2, 3)
- Colaboración en github (pull requests y branches para cada funcionalidad)
- Code reviews para aprobar los pull requests
- Merge conflicts

### Aseguramiento de la calidad (1, 2, 3)
- Análisis estático
- Enforzamiento del estándar BarrC-2018
- Pruebas unitarias

### Desarrollo modular (1)
- Desarrollo impulsado por pruebas (para embedded)

### Automatización del proceso de desarrollo (3)
- Automatización de pruebas y compilación en jenkins
- Deploy conectado a Jenkins con Artifactory

### Técnicas usadas en industria (4)
- Desarrollo de bootloaders (UART o SPI)
- Uso de filtros digitales (algún otro que no sea promedio)
- Uso de Formato Q (Q15 por ejemplo) (Número fraccionario representado en un número entero)
- Abstracción de hardware multicapas (APIs y HALs)
- Machine Learning en Embedded (Edge devices, probablemente con TinyML/TFLight)
- Configuración y uso de Watchdog timers
- Implementación de máquinas de estados
- Manejo de información por interrupciones sin variables globales (y posteriormente interrupciones anidadas)
- Uso de JTAG para acceso a opciones avanzadas de depuración
- Implementación básica de modos de bajo consumo (sleep mode)

### periféricos usados en industria (4)
- ADC
- PWM
- I2C
- SPI
- QEI


Sin embargo, estamos conscientes de que es una cantidad de trabajo enorme, sobre todo si pensamos que solo podremos desarrollar proyectos hasta tener esta infraestructura lista.
Por lo que hemos pensado en ir implementando diferentes elementos de la misma a través de pequeños proyectos que a su vez también nos permitan practicar y aprender.

Estos proyectos serán llevados en grupos de estudio por projecto.

### Beneficios del framework de CoDe Pretzel
1. Nos da contenido para grupos de estudio
2. Es modular e incremental
3. Proporciona un mapa de aprendizaje
4. Brinda una infraestructura que nos permite hacer software embebido de calidad
5. Nos da un estándar para liberar proyectos y darles continuidad, incluso en cierto momento, para liberarlos como open source
6. Los miembros que construyan e utilicen la infraestructura tendrán mejores prácticas y habilidades para una entrevista de trabajo
7. Prepara a cualquier desarrollador de software embebido para especializarse en alguna de las áreas (DSP, DIP, control de motores, automotriz, etc)
8. Brinda repitibilidad de proceso, podemos sacar proyectos más rápido, más estables y con un aseguramiento de calidad automatizado

## Equipo de administración

* [Leonides](https://www.linkedin.com/in/hermann-leonides-zu%C3%B1iga-cruz-83a4801a1/)
* [Karosuo](https://www.linkedin.com/in/rafaelkarosuo/)
* [Cruz](https://www.linkedin.com/in/claudio-guadalupe-cruz-mendoza-35717a211/)
* [Emmanuel](https://www.linkedin.com/in/emmnee/)

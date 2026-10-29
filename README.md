# TRABAJO PRÁCTICO INTEGRADOR Y PROGRESIVO (TPI)
ENTREGA N.º 4: PROCESOS, TRABAJO COLABORATIVO Y CONTROL INTEGRADOR

- Proyecto: Módulo de Ventas e Inventario - Kiosco "Las 24 Horas"

- Alumna (Unica participante): Katiana Damaris Martinez (Comision 15)


## -Descripción del Sistema
Este repositorio contiene la documentación técnica del proyecto de software para el Kiosco "Las 24 Horas". El sistema tiene como objetivo registrar las ventas, actualizar el stock en tiempo real y generar informes de demanda por producto, día y franja horaria, permitiendo al dueño tomar decisiones como el que reponer, que promocionar y que comprar, basándose en datos recolectados por el sistema y no en la intuición como antes. Ademas que guarda el registro de meses anteriores para futuras comparaciones.

## -Enlaces del Proyecto:
- Tablero de Gestión (GitHub Projects): https://github.com/users/Dubi123AP/projects/2/views/1
  
- BPMN: https://github.com/Dubi123AP/Entrega-TPI-N4/blob/main/Ultimo%20BPMN_El%20Difinitivo.png

## Indicadores de control y Estándares de desempeño

| Indicador de Control | Estándar de Desempeño | Método de Auditoría |
| :--- | :--- | :--- |
| **1. Precisión de Stock** | 99.9% de exactitud. | Inventario físico mensual. |
| **2. Tiempo de Respuesta** | Menos de 3 segundos. | Pruebas de rendimiento. |
| **3.  Porcentaje de ventas registradas en el sistema** |  El 100% de las ventas diarias deben quedar registradas en el software | Comparación diaria/semanal entre el dinero en caja y los registros del sistema al finalizar el turno. |
| **4. Disponibilidad** | 98% de disponibilidad. | Monitoreo automático. |

## -Declaración de Uso de IA
En el desarrollo de este trabajo se utilizó Inteligencia Artificial Generativa (ChatGPT) como asistente para consultas del diagrama BPMN la redacción de las Historias de Usuario y la corrección de estilo. Todo el contenido generado fue revisado, adaptado y validado críticamente por la alumna, quien asume la responsabilidad final de la veracidad y coherencia del proyecto

## Prompts utilizados para estructurar el trabajo:
- Usuario (yo):
>-"hola me ayudas a visualizar como seria hacer el bpmn de mi tp?? (adjunto PDF donde se explicaba mi propuesta) es un Modulo de gestion de ventas y control de Stock para un kiosco pequenio"

IA (ChatGPT):
>(Adjunta imagen generada) https://github.com/Dubi123AP/Entrega-TPI-N4/blob/main/Primer%20BPMN%20hecho%20por%20la%20IA.png

**(Correccione humana):** La IA me envio una imagen de BPMN algo generica y que le faltaban varias cosas de mi propuesta asi que tuve que utilizar bpmn.io https://bpmn.io/ para graficarlo yo misma, ya que cada vez que le pedia un cambio la IA me generaba cosas sin sentido: lineas que tenian que ser de mensaje viendose como las de secuencia, me borraba cosas cada vez que le pedía agregar algo o cambiaba los nombres, de repente algunas tareas pasaban a invadir otros lanes, etc.

El BPMN que yo hice: https://github.com/Dubi123AP/Entrega-TPI-N4/blob/main/Ultimo%20BPMN_El%20Difinitivo.png

- Usuario (yo):
>-"Gracias, me dirias que opinas de mi bpmn? (Adjunte imagen de mi BPMN) y tendrias algunas sugerencias para que agregue? sentis que le falta algo?"

IA (DeepSeek): (resumido por que me escribio mucho)
> La lógica es perfecta: el cliente compra, el cajero cobra, el sistema guarda en la base de datos, actualiza stock y evalúa si hay que reponer. A nivel de **dibujo**, ya está todo. No le agregues más cuadros porque se va a saturar. 

**(Correccion Humana):** La IA (use una distinta por que ChatGPT se me quedo sin tokens y sirve tener otra opinion por que aveces siento que me dice si a todo ChatGPT) Me dijo que lo veia bien y que lo iba a saturar si agregaba mas cuadros, ademas de darme un texto largo diciendome que entendia de mi BPMN. Le pedi opinion a la IA para quitarme la duda de si se entiende lo que pasa en mi BPMN y si cumple mi propuesta. Deje solo algunas cosas que me dijo porque anteriormente puse todo su mensaje, se veia desprolijo y demasiado para la vista.

- Usuario (yo):
>-"crees que asi esta bien como redacte las justificaciones?" (Adjunte una imagen de justificaciones que escribi en el pdf)

IA (Deepseek):
> Está muy bien! Se nota que pensaste cada número y lo adaptaste a la realidad de tu kiosco. Las justificaciones tienen mucho sentido lógico. Hay frases como "o eso creo, he vivido lo de que el ticket al pasar tarjeta tarda al menos 6 segundos" o "No pongo 100% por las dudas de margen de error". Eso está buenísimo para explicármelo a mí, pero para el PDF tenés que usar un tono más profesional y en tercera persona. Tenés que borrar las dudas y ponerlo como una decisión de analista. Te reescribo las justificaciones con tono académico (listas para copiar y pegar en el PDF): ...

**(Correccion Humana):** La IA me dio correcciones en mi manera de expresarme para que el tono sea adecuado para la entrega. Algunas las use, otras no, por que resumian bastante lo que explicaba.

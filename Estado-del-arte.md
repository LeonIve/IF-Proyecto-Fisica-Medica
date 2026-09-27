# IF-Proyecto-Física-Médica
# Introducción
El acceso equitativo y oportuno a métodos de diagnóstico médico representa uno de los mayores retos de la salud pública en el Perú y a nivel global. Actualmente, la evaluación de patologías vasculares como la Trombosis Venosa Profunda (TVP), la isquemia muscular o la 
caracterización de masas tisulares depende fuertemente de tecnologías de imagenología convencional como la tomografía axial computarizada (TAC), la resonancia magnética (RM) y la ecografía Doppler. Si bien estos métodos ofrecen alta resolución espacial, su implementación masiva enfrenta graves limitaciones estructurales.
# Estructura

### 1. Problemática :pushpin:
###### Saturación e Inoperatividad de Equipos Médicos: 
En el sistema de salud público (MINSA y EsSalud), los reportes de organismos de control señalan un porcentaje significativo de tomógrafos y ecógrafos inoperativos debido a la falta de mantenimiento preventivo y al sobreuso por alta demanda. Esto genera listas de espera para exámenes especializados de entre 1 a 3 meses, un tiempo crítico donde patologías vasculares pueden evolucionar hacia complicaciones mortales. 

###### Déficit y Centralización de Personal Especializado:
La operación e interpretación en tiempo real de ecografías Doppler y tomografías requiere médicos radiólogos y especialistas. En el Perú, existe una severa brecha de especialistas, concentrados principalmente en Lima y grandes capitales de región, dejando desprovistos a los centros de atención primaria.

###### Inaccesibilidad Económica y Barreras Geográficas:
En el sector privado, el costo de una tomografía o resonancia oscila entre S/. 500 y S/. 2,500 soles, un monto prohibitivo para familias de bajos recursos económicos. Asimismo, estos equipos requieren instalaciones complejas (blindaje contra radiación, acondicionamiento ambiental estricto y suministro eléctrico continuo de alta potencia), imposibilitando su despliegue en postas de salud rurales o periféricas.

###### Desprotección en Zonas Rurales y Centros de Atención Primaria: 
Muchas postas médicas rurales (niveles I-1 e I-2) operan con equipamiento mínimo o casi nulo. Un paciente con sospecha de coágulo en una zona alejada no cuenta con herramientas de descarte local y debe ser trasladado por carreteras accidentadas durante horas, aumentando exponencialmente el riesgo de desprendimiento del coágulo y embolia pulmonar. 

###### Peligrosidad de Patologías Asintomáticas:
Aproximadamente el 50% de los pacientes con Trombosis Venosa Profunda no manifiestan síntomas clínicos evidentes en etapas tempranas. Cuando los síntomas agudos aparecen, la condición suele estar en fase avanzada.

### 2. Aplicación :pushpin:
Se propone el desarrollo y mejoramiento de un sistema de caracterización y diagnóstico óptico no invasivo, portátil y de ultra bajo costo que medirá las concentraciones de oxihemoglobina \Delta[HbO_2] y desoxihemoglobina \Delta[Hb] mediante luz y sensores IR. Utilizando las propiedades de transporte de radiación electromagnética no ionizante en medios turbios (tejidos biológicos) y la Ley de Beer-Lambert para traducir densidades ópticas en datos de \Delta[HbO_2] y \Delta[Hb]. El dispositivo permite realizar descartes rápidos en triaje o atención primaria en un par de minutos, sin requerir personal altamente especializado ni infraestructura compleja. 

### 3. Antecedentes :pushpin:
- Li T., Sun Y., Chen X., Zhao Y., Ren R.
AUTHOR FULL NAMES: Li, Ting (55728945000); Sun, Yunlong (56086564500); Chen, Xiao (56510551700); Zhao, Yue (56086594600); Ren, Rongrong (58420599500)
55728945000; 56086564500; 56510551700; 56086594600; 58420599500
Noninvasive diagnosis and therapeutic effect evaluation of deep vein thrombosis in clinics by near-infrared spectroscopy
(2015) Journal of Biomedical Optics, 20 (1), art. no. 010502, Cited 31 times.
DOI: 10.1117/1.JBO.20.1.010502
https://www.scopus.com/pages/publications/84922572855?origin=resultslist

- Arora S., Lam D.J.K., Kennedy C., Meier G.H., Gusberg R.J., Negus D.
AUTHOR FULL NAMES: Arora, Subodh (57196588088); Lam, David J.K. (7201749693); Kennedy, Collette (57196725505); Meier, George H. (7103175047); Gusberg, Richard J. (7003957245); Negus, David (7006372987)
57196588088; 7201749693; 57196725505; 7103175047; 7003957245; 7006372987
Light reflection rheography: A simple noninvasive screening test for deep vein thrombosis
(1993) Journal of Vascular Surgery, 18 (5), pp. 767 - 772, Cited 19 times.
DOI: 10.1016/0741-5214(93)90330-O
https://www.scopus.com/pages/publications/0027430092?origin=resultslist

### 4. Objetivo :pushpin:
- Detección de tumores y prevención de muerte por trombosis venosa profunda (TVP) mediante el desarrollo y mejoramiento de un dispositivo NIRS (Near-Infrared spectroscopy).
- Reducción de coste de pruebas y análisis de TVP.
- Accesibilidad inmediata y reducción en el tiempo de análisis de TVP.

## :electric_plug: Parte Electrónica del Dispositivo

### 5. Diseño del Sistema Electrónico :pushpin:

El sistema electrónico es el corazón del dispositivo NIRS. Se encarga de generar la señal de luz infrarroja, controlar la emisión, detectar la luz que atraviesa el tejido, convertirla a señal eléctrica, amplificarla y digitalizarla para su procesamiento. Todo diseñado para ser portátil, de bajo costo y bajo consumo.

---

### :jigsaw: Componentes a Utilizar

| Foto | Componente | Función | Recomendación |
|:---:|---|---|---|
| <img src="images.jfif" width="120"> | Microcontrolador | Cerebro del sistema: controla emisión, lee sensores, procesa datos | Arduino Nano / ESP32 — económico, fácil de programar, suficiente para NIRS |
| <img src="imanes.jfif" width="120"> | LED Infrarrojo (IR) | Emite luz hacia el tejido biológico | LED 850 nm y 940 nm (dos longitudes de onda para medir HbO₂ y Hb) |
| <img src="imanes.jfif" width="120"> | Fotodiodo / Fototransistor | Recibe la luz que regresa del tejido y la convierte en señal eléctrica | Fotodiodo BPW21 o similar — sensible en rango visible e IR |
| <img src="images (4).jfif" width="120"> | Circuito de Amplificación | La señal del fotodiodo es muy débil → se necesita amplificar | Op-Amp LM358 o TL081 — amplificador operacional de bajo costo |
| <img src="images(5).jfif" width="120"> | Filtros | Eliminar ruido de la red eléctrica (50/60 Hz) y luces ambientales | Condensadores de 100nF + resistores → filtro pasa-bajos simple |
| <img src="images(6).jfif" width="120"> | Fuente de Alimentación | Energía portátil para todo el circuito | Batería de 3.7V Li-ion + módulo cargador TP4056 + regulador 5V |
| <img src="images(7).jfif" width="120"> | Resistencias y Condensadores | Polarización, protección y estabilización del circuito | Varios valores: 220Ω, 1kΩ, 10kΩ, 100nF, 10µF |
| <img src="images(8).jfif" width="120"> | Pantalla / Indicador | Mostrar resultados en tiempo real | Pantalla OLED 128×64 (I2C) — pequeña, económica y clara |
---

### :gear: Funcionamiento del Circuito

1. Emisión: El microcontrolador envía una señal para encender los LEDs IR a frecuencia definida → la luz penetra en el tejido biológico.
2. Detección: El fotodiodo capta la luz que regresa → genera una corriente muy pequeña proporcional a la intensidad recibida.
3. Amplificación: El amplificador operacional convierte esa señal débil en voltaje medible → ajustamos la ganancia según necesidad.
4. Filtrado: Se eliminan interferencias de luces externas y ruido eléctrico.
5. Conversión A/D: El microcontrolador lee el voltaje → convierte a valor numérico.
6. Cálculo: Aplica la Ley de Beer-Lambert → calcula cambios en concentraciones de oxihemoglobina y desoxihemoglobina.
7. Salida: Muestra resultados en pantalla y/o envía datos por USB.

---

### :moneybag: Estimación de Costos

| Componente | Aprox. Precio (S/) |
|---|---:|
| Arduino Nano | 15 – 20 |
| 2 LEDs IR (850nm + 940nm) | 4 – 6 |
| Fotodiodo BPW21 | 5 – 8 |
| Amplificador LM358 | 2 – 3 |
| Pantalla OLED 128×64 | 10 – 15 |
| Batería + módulo carga | 15 – 20 |
| Resistencias, condensadores, cables | 5 – 10 |
| **TOTAL** | **~S/. 56 – 82** |

Costo ultra bajo comparado con equipos comerciales que cuestan miles de dólares.

---

### :white_check_mark: Recomendaciones de Diseño y Montaje

- Diseño compacto: Colocar emisor y detector muy juntos (~1–2 cm) para que la luz viaje por el tejido y regrese.
- Protección: Usar cubierta opaca alrededor del sensor → evitar que la luz ambiente interfiera.
- Estabilidad: Alimentar los circuitos de amplificación con condensadores cercanos a las patas del chip → reducir ruido.
- Calibración: Probar primero con materiales de propiedades ópticas conocidas antes de pruebas en personas.
- Código: Encender y apagar los LEDs alternadamente → permite diferenciar la señal de luz del dispositivo vs. luz externa.

---
## :chart_with_upwards_trend: Cronograma del Proyecto — Diagrama de Gantt

| Semana | Actividad | Entregable | Peso | Estado |
|:---:|---|---|:---:|:---:|
| **3** | Definición del problema, objetivos y alcance del proyecto | Propuesta | 15% | :hourglass_flowing_sand: En proceso |
| **4** | Investigación de antecedentes y elaboración del Estado del Arte | Documento Estado del Arte | — | :clock5: Pendiente |
| **5** | Planificación detallada: lista de componentes, presupuesto y cronograma | Plan de Proyecto | 20% | :clock5: Pendiente |
| **6** | Diseño del sistema electrónico: esquemas y selección final de componentes | Diseño Esquemático | — | :clock5: Pendiente |
| **7** | Montaje en protoboard y conexión de circuitos | Avance de Montaje | — | :clock5: Pendiente |
| **8** | Programación del microcontrolador y pruebas básicas de emisión/recepción | Código + Pruebas Preliminares | — | :clock5: Pendiente |
| **9 – 10** | Calibración del sensor, ajuste de amplificación y filtrado | Informe de Calibración | — | :clock5: Pendiente |
| **11 – 12** | Pruebas con muestras/phantoms y toma de datos experimentales | Resultados Experimentales | — | :clock5: Pendiente |
| **13 – 14** | Análisis de resultados, comparación con referencias y redacción de conclusiones | Borrador de Informe Final | — | :clock5: Pendiente |
| **15** | Revisión por pares, correcciones y ajustes finales | Informe Final Revisado | — | :clock5: Pendiente |
| **16** | Entrega oficial del Reporte Técnico Final | Reporte Técnico Final | 20% | :date: Entrega |

---

### :bar_chart: Resumen de Etapas

| Etapa | Semanas | Duración |
|---|:---:|:---:|
| 1. Propuesta y Definición | 3 | 1 semana |
| 2. Planificación y Estado del Arte | 4 – 5 | 2 semanas |
| 3. Diseño y Montaje Electrónico | 6 – 8 | 3 semanas |
| 4. Programación y Calibración | 9 – 10 | 2 semanas |
| 5. Pruebas y Toma de Datos | 11 – 12 | 2 semanas |
| 6. Análisis, Redacción y Revisión | 13 – 15 | 3 semanas |
| 7. Entrega Final | 16 | 1 semana |

### :checkered_flag: Avance General: 15%


## 👥 Equipo del Proyecto

| Foto | Nombre y Código | Rol |
|:---:|:---|:---|
| <img src="foto.png" width="90" style="border-radius:50%"> | **Jairo Jefferson Ortega Vega**<br>`Código: 20220089E` | ⚙️ **Responsable del diseño, implementación y pruebas del sistema electrónico**<br>— Diseño de circuitos, selección de componentes, montaje, conexionado, calibración y verificación del funcionamiento eléctrico y electrónico del equipo |
| <img src="enlace_foto_2" width="90" style="border-radius:50%"> | **Nombre 2**<br>`Código: XXXX` | Aquí tu rol |
| <img src="enlace_foto_3" width="90" style="border-radius:50%"> | **Nombre 3**<br>`Código: XXXX` | Aquí tu rol |
| <img src="enlace_foto_4" width="90" style="border-radius:50%"> | **Nombre 4**<br>`Código: XXXX` | Aquí tu rol |
| <img src="enlace_foto_5" width="90" style="border-radius:50%"> | **Nombre 5**<br>`Código: XXXX` | Aquí tu rol |

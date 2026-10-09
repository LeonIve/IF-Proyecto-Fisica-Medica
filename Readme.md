# Caracterización Óptica de Medios Turbios para Diagnóstico Médico No Invasivo de la Trombosis Venosa Profunda (TVP) y Masas Tisulares

# :book: Introducción
El acceso equitativo y oportuno a métodos de diagnóstico médico representa uno de los mayores retos de la salud pública en el Perú y a nivel global :earth_americas:. Actualmente, la evaluación de patologías vasculares como la Trombosis Venosa Profunda (TVP), la isquemia muscular o la caracterización de masas tisulares depende fuertemente de tecnologías de imagenología convencional como la tomografía axial computarizada (TAC), la resonancia magnética (RM) y la ecografía Doppler. Si bien estos métodos ofrecen alta resolución espacial, su implementación masiva enfrenta graves limitaciones estructurales.

# :clipboard: Estructura

### 1. Problemática :pushpin:

###### :hospital: Saturación e Inoperatividad de Equipos de Imagenología Médica Públicos:
En el sistema de salud público (MINSA y EsSalud), los reportes de organismos de control señalan un porcentaje significativo de tomógrafos, resonadores magnéticos y ecógrafos Doppler inoperativos debido a la falta de mantenimiento preventivo y al sobreuso por alta demanda. Esto genera listas de espera para exámenes especializados de entre 1 a 3 meses, un tiempo crítico donde patologías vasculares pueden evolucionar hacia complicaciones mortales, mientras que un tumor no detectado puede progresar aceleradamente de una etapa localizada a fases metastásicas.

###### :man_health_worker: Déficit y Centralización de Personal Especializado en lectura de Imágenes Diagnósticas:
La operación e interpretación de ecografías Doppler y tomografías requieren médicos radiólogos y especialistas en tiempo real. En el Perú, existe una severa brecha de especialistas, concentrados principalmente en Lima y grandes capitales de región. Esta centralización deja a miles de peruanos en centros de salud de atención primaria sin personal capacitado para interpretar imágenes complejas, provocando diagnósticos erróneos o retrasos prolongados en la derivación de pacientes.

###### :moneybag: Inaccesibilidad Económica por el Alto Costo de exámenes de Imagenología Especializada:
En el sector privado, el costo de una tomografía o resonancia oscila entre S/. 500 y S/. 2,500 soles, un monto prohibitivo para familias de bajos recursos económicos, obligándolos a postergar sus exámenes diagnósticos y arriesgar su vida por motivos financieros. Asimismo, estos equipos requieren instalaciones complejas (blindaje contra radiación, acondicionamiento ambiental estricto y suministro eléctrico continuo de alta potencia), imposibilitando su despliegue en postas de salud rurales o periféricas.

###### :moneybag: Imposibilidad de Diferenciación Temprana entre Tumores Benignos, Malignos y Coágulos en Triaje Primario:
Los métodos de palpación manual o evaluación física básica en triaje son incapaces de caracterizar la naturaleza de una masa tisular o diferenciar un coágulo de un proceso neoplásico. Sin herramientas ópticas cuantitativas, no es posible evaluar el grado de angiogénesis, hipervascularización típica de tumores malignos frente a la baja vascularización de una masa benigna o la oclusión total por un trombo, lo que retrasa la derivación prioritaria del paciente a una biopsia o a un tratamiento anticoagulante inmediato. 

###### :house_with_garden: Desprotección en Zonas Rurales y Centros de Atención Primaria en Equipos de Imagenología:
Muchas postas médicas rurales (niveles I-1 e I-2) operan con equipamiento mínimo o casi nulo. Un paciente con sospecha de coágulo en una zona alejada no cuenta con herramientas de descarte local y debe ser trasladado por carreteras accidentadas durante horas, aumentando exponencialmente el riesgo de desprendimiento del coágulo y embolia pulmonar.

###### :detective: Peligrosidad de Patologías Asintomáticas:
Aproximadamente el 50% de los pacientes con Trombosis Venosa Profunda y una fracción considerable de tumores benignos o malignos, no manifiestan sintomatología clínica evidente en etapas tempranas. Cuando los síntomas agudos aparecen, la condición suele estar en fase avanzada. Por ende, la ausencia de dispositivos portátiles de bajo costo para el tamizaje rutinario en triaje impide la detección precoz de estas condiciones en la población general.

### 2. Aplicación :pushpin:
Se propone el desarrollo y mejoramiento de un sistema de caracterización y diagnóstico óptico no invasivo, portátil y de ultra bajo costo que medirá las concentraciones de oxihemoglobina Δ[HbO₂] y desoxihemoglobina Δ[Hb] mediante luz y sensores IR. Utilizando las propiedades de transporte de radiación electromagnética no ionizante en medios turbios (tejidos biológicos) y la Ley de Beer-Lambert para traducir densidades ópticas en datos de Δ[HbO₂] y Δ[Hb]. El dispositivo permite realizar descartes rápidos en triaje o atención primaria en un par de minutos, sin requerir personal altamente especializado ni infraestructura compleja.

### 3. Antecedentes :pushpin:
La necesidad de detectar trombos y masas tumorales sin cirugías exploratorias impulsó, desde mediados del siglo XX, el desarrollo de la imagenología moderna. Aunque la llegada del ultrasonido Doppler, la tomografía y la resonancia magnética consolidó el estándar de oro diagnóstico, su elevado costo e infraestructura limitaron su uso a hospitales de alta complejidad. Para cubrir este vacío en la atención primaria, en los años 90 emergió la biofotónica como una alternativa no invasiva, portátil y de bajo costo basada en la interacción de la luz infrarroja con el tejido biológico [1]. Es en esta evolución donde se enmarca el presente proyecto, buscando optimizar la detección vascular mediante un sistema óptico multicanal accesible. 

Partiendo de estos fundamentos, en los últimos años diversas investigaciones han explorado alternativas ópticas e infrarrojas para superar las limitaciones de accesibilidad y costo que presentan las técnicas estándar de imagenología médica [2], [3]. En el ámbito de la termografía infrarroja (TIR), diversos autores evaluaron la asimetría térmica de la piel como indicador indirecto de alteraciones hemodinámicas y procesos inflamatorios agudos asociados a eventos trombóticos o vasculares [4], [5]. Estudios clínicos preliminares, como los desarrollados en modelos animales por Deng et al. [6] y en cohortes de pacientes con sospecha de trombosis venosa profunda (TVP), reportaron altos niveles de sensibilidad entre 88.3% y 96.88% mediante el uso de termografía infrarroja digital como herramienta adyuvante al ecógrafo Doppler en extremidades inferiores [7], [8], [9] o arteria femoral [10]. Sin embargo, la literatura coincide en que la termografía ofrece un desempeño moderado en especificidad frente al Doppler color debido a su alta susceptibilidad a factores ambientales y a que solo mide la radiación térmica superficial cutánea [7]. A partir de estos hallazgos, para el desarrollo de nuestro dispositivo se decide prescindir del monitoreo meramente térmico como técnica principal, reemplazándolo o complementándolo con una arquitectura de detección por espectroscopía activa, la cual permite interrogar directamente el volumen tisular subyacente y reducir la variabilidad por ruido ambiental.

Por otro lado, la Espectroscopía de Infrarrojo Cercano (EINC) y la Reografía de Reflexión de Luz (RRL) han demostrado ser técnicas sólidas y no invasivas para la caracterización vascular y la evaluación hemodinámica cuantitativa [11]. Trabajos pioneros de Scott et al. [12] y Korah et al. [10] establecieron la factibilidad de utilizar dispositivos EINC portátiles para monitorear en tiempo real las variaciones relativas de hemoglobina oxigenada (HbO2) y desoxihemoglobina (HHb) mediante maniobras de provocación vascular. De igual forma, investigaciones clínicas llevadas a cabo por Li et al. [12], Yamaki et al. [13] y Hosoi et al. [14], [15] confirmaron que la NIRS presenta una elevada sensibilidad de hasta del 97% en la evaluación del flujo venoso, el reflujo y la recanalización en la pantorrilla, superando a métodos como la pletismografía por aire, técnica que mide cambios de volumen mediante un brazalete inflable en la pierna, especialmente en la detección de patologías vasculares distales. No obstante, la mayoría de estos desarrollos se enfocan tradicionalmente en equipos voluminosos de laboratorio y poco portátiles, o sistemas monocanal. Esta última configuración impide separar la información de la piel superficial del tejido profundo, limitando su capacidad a detectar únicamente oclusiones venosas severas o muy avanzadas. Para nuestro diseño, se propone modificar la geometría de la sonda implementando un arreglo optoelectrónico multicanal con distancias emisor-detector optimizadas (1.5cm a 3.5cm), permitiendo restar el efecto de la capa cutánea superficial y diferenciar tanto estasis venosa como hipervascularización tumoral.

Finalmente, el desarrollo reciente de instrumentación optoelectrónica dedicada ha enfatizado la necesidad de garantizar estabilidad técnica a bajo costo, trabajos como el de Zhao et al. [16] destacan que el éxito clínico de un monitor NIRS portátil reside en la supresión activa del ruido oscuro, la compensación de deriva térmica y la inmunidad frente a interferencias electromagnéticas. Tomando como referencia estas recomendaciones, nuestro proyecto adoptará un sistema de iluminación multiespectral pulsada (660nm y 850nm) junto con un módulo de amplificación de transimpedancia (AMP-TI) y filtrado pasa-banda activo. Estas modificaciones permitirán obtener un prototipo robusto, inmune a la luz ambiental y de ultra bajo costo, apto para su despliegue en centros de atención primaria y triaje.


### 4. Objetivo :pushpin:
- :dart: Detección de tumores y prevención de muerte por trombosis venosa profunda (TVP) mediante el desarrollo y mejoramiento de un dispositivo NIRS (Near-Infrared Spectroscopy).
- :chart_down: Reducción de coste de pruebas y análisis de TVP.
- :zap: Accesibilidad inmediata y reducción en el tiempo de análisis de TVP.

## :electric_plug: Parte Electrónica del Dispositivo

### 5. Diseño del Sistema Electrónico :pushpin:

El sistema electrónico es el :heart: corazón del dispositivo NIRS. Se encarga de generar la señal de luz infrarroja, controlar la emisión, detectar la luz que atraviesa el tejido, convertirla a señal eléctrica, amplificarla y digitalizarla para su procesamiento. Todo diseñado para ser portátil, de bajo costo y bajo consumo.

---

### :jigsaw: Componentes a Utilizar

| Foto | Componente | Función | Recomendación |
|:---:|---|---|---|
| <img src="Imagenes/images.jfif" width="120"> | :brain: Microcontrolador | Cerebro del sistema: controla emisión, lee sensores, procesa datos | Arduino Nano / ESP32 — económico, fácil de programar, suficiente para NIRS |
| <img src="Imagenes/images (1).jfif" width="120"> | :flashlight: LED Infrarrojo (IR) | Emite luz hacia el tejido biológico | LED 850 nm y 940 nm (dos longitudes de onda para medir HbO₂ y Hb) |
| <img src="Imagenes/images (2).jfif" width="120"> | :eye: Fotodiodo / Fototransistor | Recibe la luz que regresa del tejido y la convierte en señal eléctrica | Fotodiodo BPW21 o similar — sensible en rango visible e IR |
| <img src="Imagenes/images (3).jfif" width="120"> | :loudspeaker: Circuito de Amplificación | La señal del fotodiodo es muy débil → se necesita amplificar | Op-Amp LM358 o TL081 — amplificador operacional de bajo costo |
| <img src="Imagenes/images (4).jfif" width="120"> | :broom: Filtros | Eliminar ruido de la red eléctrica (50/60 Hz) y luces ambientales | Condensadores de 100nF + resistores → filtro pasa-bajos simple |
| <img src="Imagenes/images (5).jfif" width="120"> | :battery: Fuente de Alimentación | Energía portátil para todo el circuito | Batería de 3.7V Li-ion + módulo cargador TP4056 + regulador 5V |
| <img src="Imagenes/images (6).jfif" width="120"> | :battery: Fuente de Alimentación | Energía portátil para todo el circuito | Regulador 5V |
| <img src="Imagenes/images (7).jfif" width="120"> | :gear: Resistencias y Condensadores | Polarización, protección y estabilización del circuito | Varios valores: 220Ω, 1kΩ, 10kΩ, 100nF, 10µF |
| <img src="Imagenes/images (8).jfif" width="120"> | :tv: Pantalla / Indicador | Mostrar resultados en tiempo real | Pantalla OLED 128×64 (I2C) — pequeña, económica y clara |

---

### :gear: Funcionamiento del Circuito

1. :bulb: Emisión: El microcontrolador envía una señal para encender los LEDs IR a frecuencia definida → la luz penetra en el tejido biológico.
2. :eye: Detección: El fotodiodo capta la luz que regresa → genera una corriente muy pequeña proporcional a la intensidad recibida.
3. :loudspeaker: Amplificación: El amplificador operacional convierte esa señal débil en voltaje medible → ajustamos la ganancia según necesidad.
4. :broom: Filtrado: Se eliminan interferencias de luces externas y ruido eléctrico.
5. :bar_chart: Conversión A/D: El microcontrolador lee el voltaje → convierte a valor numérico.
6. :abacus: Cálculo: Aplica la Ley de Beer-Lambert → calcula cambios en concentraciones de oxihemoglobina y desoxihemoglobina.
7. :mobile_phone: Salida: Muestra resultados en pantalla y/o envía datos por USB.

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

- :straight_ruler: Diseño compacto: Colocar emisor y detector muy juntos (~1–2 cm) para que la luz viaje por el tejido y regrese.
- :shield: Protección: Usar cubierta opaca alrededor del sensor → evitar que la luz ambiente interfiera.
- :zap: Estabilidad: Alimentar los circuitos de amplificación con condensadores cercanos a las patas del chip → reducir ruido.
- :test_tube: Calibración: Probar primero con materiales de propiedades ópticas conocidas antes de pruebas en personas.
- :computer: Código: Encender y apagar los LEDs alternadamente → permite diferenciar la señal de luz del dispositivo vs. luz externa.

---

### :chart_with_upwards_trend: Cronograma del Proyecto — Diagrama de Gantt

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

---

## :busts_in_silhouette: Equipo del Proyecto

| Foto | Nombre y Código | Rol |
|:---:|:---|:---|
| <img src="enlace_foto_1" width="90" style="border-radius:50%"> | **Genaro Andres <br> Bello Oviedo**<br>`Código: 20241476H` | ⚙️ **Responsable del diseño, implementación y pruebas del sistema electrónico**<br>— Diseño de circuitos, selección de componentes, montaje, conexionado, calibración y verificación del funcionamiento eléctrico y electrónico del equipo |
| <img src="Fotos/FoTo_XimenaG.jpeg" width="90" style="border-radius:50%"> | **Ximena Valentina <br> Guerra Gonzales**<br>`Código: 20240656B` | :book: **Responsable del estudio de los métodos no invasivos para la detección de TVP**<br>— Estudio, recopilación, análisis y proposición de métodos no invasivos para la detección de TVP y masas tisulares en base a libros y artículos relacionados |
| <img src="Fotos/Renato_Leon.jpg" width="90" style="border-radius:50%"> | **Bryan Renato <br> Leon Ive**<br>`Código: 20240541K` | :book: **Responsable del estudio de los métodos no invasivos para la detección de TVP**<br>— Estudio, recopilación, análisis y proposición de métodos no invasivos para la detección de TVP en base a libros y artículos relacionados |
| <img src="Fotos/Bruno.jpg" width="90" style="border-radius:50%"> | **Bruno Stephano <br> Ocaña Cruzate**<br>`Código: 20251704C` |:microscope: **Responsable de la coordinación general, fundamentación óptica e innovación tecnológica**<br>— Representación técnica y gestión del equipo; estudio y modelado de la interacción luz-tejido (absorción, dispersión y reflexión óptica en escáneres dérmicos) y definición del valor diferencial e innovador frente a métodos diagnósticos tradicionales | 
| <img src="Fotos/jairo.png" width="90" style="border-radius:50%"> | **Jairo Jefferson Ortega Vega**<br>`Código: 20220089E` | ⚙️ **Responsable del diseño, implementación y pruebas del sistema electrónico**<br>— Diseño de circuitos, selección de componentes, montaje, conexionado, calibración y verificación del funcionamiento eléctrico y electrónico del equipo |

---

### Referencias :pushpin:

###### Artículos

1.	Deng, F., Tang, Q., Jiang, M., (...), Liu, G. (2018) Infrared thermal imaging and Doppler vessel pressurization ultrasonography to detect lower extremity deep vein thrombosis: Diagnostic accuracy study. Clinical Respiratory Journal. https://doi.org/10.1111/crj.12639
2.	Liu, X.-T., Zheng, Y.-Y., Jiang, Z.-Z., (...), Huang, Y.-H. (2020) Diagnostic value of infrared thermography in deep venous thrombosis of lower extremities. Chinese Journal of General Practice. https://doi.org/10.16766/j.cnki.issn.1674-4152.001601
3.	Deng, F., Tang, Q., Zeng, G., (...), Zhong, N. (2015) Effectiveness of digital infrared thermal imaging in detecting lower extremity deep venous thrombosis. Medical Physics. https://doi.org/10.1118/1.4907969
4.	Deng, F., Tang, Q., Zheng, Y., (...), Zhong, N. (2012) Infrared thermal imaging as a novel evaluation method for deep vein thrombosis in lower limbs. Medical Physics. https://doi.org/10.1118/1.4764485
5.	Li, T., Sun, Y., Chen, X., (...), Ren, R. (2015) Noninvasive diagnosis and therapeutic effect evaluation of deep vein thrombosis in clinics by near-infrared spectroscopy. Journal of Biomedical Optics. https://doi.org/10.1117/1.JBO.20.1.010502
6.	Zhao, K., Pan, B., Li, Z., (...), Li, T. (2018) Performance evaluation for a novel optoelectronic device for noninvasive monitoring thrombosis. Microelectronics Reliability. https://doi.org/10.1016/j.microrel.2018.03.021
7.	Yamaki, T., Nozaki, M., Sakurai, H., (...), Kono, T. (2006) The utility of quantitative calf muscle near-infrared spectroscopy in the follow-up of acute deep vein thrombosis. Journal of Thrombosis and Haemostasis. https://doi.org/10.1111/j.1538-7836.2006.01859.x
8.	Hosoi, Y., Yasuhara, H., Miyata, T., (...), Shigematsu, H. (1999) Comparison of near-infrared spectroscopy with air plethysmography in detection of deep vein thrombosis. International Angiology. https://www.scopus.com/pages/publications/0033495971
9.	Korah, L.K., Scott, F.D., Williams, G.M., Kang, K.A. (2003) Preliminary studies of the application of near infrared spectroscopy in the diagnosis of deep vein thrombosis. Advances in Experimental Medicine and Biology. https://doi.org/10.1007/978-1-4615-0075-9_70
10.	Arora, S., Lam, D.J.K., Kennedy, C., (...), Negus, D. (1993) Light reflection rheography: A simple noninvasive screening test for deep vein thrombosis. Journal of Vascular Surgery. https://doi.org/10.1016/0741-5214(93)90330-O
11.	Lin, E.P., Bhatt, S., Dogra, V.S. (2008) Lower Extremity Venous Doppler. Ultrasound Clinics. https://doi.org/10.1016/j.cult.2007.12.005
12.	Goodacre, S., Sampson, F., Stevenson, M., (...), Ryan, A. (2006) Measurement of the clinical and cost-effectiveness of non-invasive diagnostic testing strategies for deep vein thrombosis. Health Technology Assessment. https://doi.org/10.3310/hta10150
13.	Scott, Frederick D., Kang, Kyung A., Williams, G.M. (1999) Diagnosis of deep vein thrombosis with NIR spectroscopy. Annual International Conference of the IEEE Engineering in Medicine and Biology - Proceedings. https://www.scopus.com/pages/publications/0033330798
14.	Hosoi, Y., Yasuhara, H., Shigematsu, H., (...), Muto, T. (1999) Influence of popliteal vein thrombosis on subsequent ambulatory venous function measured by near-infrared spectroscopy. American Journal of Surgery. https://doi.org/10.1016/S0002-9610(98)00314-6
15.	Enoch, S., Blair, S.D. (2003) Exclusion of deep vein thrombosis by measuring spot skin temperatures using a hand-held thermo-comparator. Phlebology. https://doi.org/10.1258/026835503322598009
16.	Bagavathiappan, S., Saravanan, T., Philip, J., (...), Jagadeesan, K. (2008) Investigation of peripheral vacular disorders using thermal imaging. British Journal of Diabetes and Vascular Disease. https://doi.org/10.1177/14746514080080020901
17.	Kang, S.-L., Manojlovich, L., Mrozcek, D., Benson, L. (2022) Infrared thermography as an adjunctive tool for detection of femoral arterial thrombosis after cardiac catheterization: A prospective, pilot study. Catheterization and Cardiovascular Interventions. https://doi.org/10.1002/ccd.30115

###### Libros

1. **Wang, L. V., & Wu, H.** (2012). *Biomedical Optics: Principles and Imaging*. John Wiley & Sons.

   📖 [ISBN: 978-0-470-17700-6](https://doi.org/10.1002/9780470177013)

2. **Bigio, I. J., & Fantini, S.** (2016). *Quantitative Biomedical Optics: Theory, Methods, and Applications*. Cambridge University Press.

   📖 [ISBN: 978-0-521-87656-8](https://doi.org/10.1017/CBO9780511805347)

3. **Keiser, G.** (2016). *Biophotonics: Concepts to Applications*. Springer.

   📖 [ISBN: 978-981-10-0945-7](https://doi.org/10.1007/978-981-10-0945-7)

4. **Tuchin, V. V.** (2000). *Tissue Optics: Light Scattering Methods and Instruments for Medical Diagnosis*. SPIE Optical Engineering Press.

   📖 [ISBN: 978-0-8194-3459-3](https://doi.org/10.1117/3.353604)

5. **Hoskins, P. R., Martin, K., & Thrush, A.** (2010). *Diagnostic Ultrasound: Physics and Equipment*. Cambridge University Press.

   📖 [ISBN: 978-1-139-48890-7](https://doi.org/10.1017/CBO9780511761194)

6. **Gloviczki, P.** (2017). *Handbook of Venous and Lymphatic Disorders: Guidelines of the American Venous Forum, Fourth Edition*. CRC Press.

   📖 [ISBN: 978-1-4987-2441-8](https://doi.org/10.1201/9781315111703)

7. **Kasper, D. L., Fauci, A. S., Hauser, S. L., Longo, D. L., Jameson, J. L., & Loscalzo, J.** (2018). *Harrison’s Principles of Internal Medicine* (20th ed., Vols. 1–2). McGraw Hill Professional.

   📖 [ISBN: 978-1-259-64404-7](https://doi.org/10.1036/9781259644030)

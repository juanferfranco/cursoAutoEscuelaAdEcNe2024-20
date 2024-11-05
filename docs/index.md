# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.


**Administración de empresas**

Semestre 1:

| **Asignatura**                  | **Problema a abordar con IA**                                                                                  | **Por qué usar IA**                                                                                              | **Herramienta de IA**                                            | **Herramienta comercial** | **Equivalente en Python**                     |
|---------------------------------|----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------|------------------------------------------------|
| Lengua y Cultura                | Análisis de grandes cantidades de texto para entender temas y estilos de escritura en trabajos de los estudiantes. | Permite análisis rápido y efectivo de características de texto, como frecuencia de palabras o temas comunes.     | NLP, análisis de frecuencia de palabras, modelos de tema          | Grammarly, IBM Watson NLU  | `nltk`, `spacy`, `gensim`, `scikit-learn`     |
| Emprendimiento y Responsabilidad Social | Identificación de necesidades del mercado mediante análisis de redes sociales.                               | Ayuda a identificar tendencias de consumo y preferencias, facilitando el diseño de proyectos más enfocados.      | Análisis de sentimiento, extracción de entidades                  | Brandwatch, Hootsuite      | `TextBlob`, `VADER`, `transformers`           |
| Pensamiento Administrativo       | Diagnóstico de fortalezas y debilidades en el comportamiento organizacional.                                    | Permite observar patrones en la interacción de los colaboradores y áreas que requieren intervención.             | Minería de datos, clustering, análisis de patrones                | Power BI, Tableau          | `pandas`, `scipy`, `scikit-learn`             |
| Estados Financieros             | Clasificación automática de transacciones financieras para optimizar informes.                                 | Facilita la clasificación de grandes volúmenes de transacciones para agilizar el proceso de cierre financiero.   | Clasificación supervisada, redes neuronales                        | QuickBooks, Xero           | `scikit-learn`, `pandas`, `tensorflow`        |
| Sistemas Lineales               | Automatización del análisis de matrices en casos aplicados a modelos de producción.                             | Aumenta la precisión y velocidad en el análisis de sistemas lineales complejos.                                  | Algoritmos de optimización, álgebra lineal                         | MATLAB, Wolfram Alpha      | `numpy`, `scipy`, `cvxpy`                     |
| Matemáticas Operativas          | Resolución automática de problemas de álgebra lineal en sistemas de ecuaciones.                                 | Proporciona rapidez y precisión en la resolución de problemas matemáticos complejos.                             | Algoritmos de álgebra lineal, optimización                         | Wolfram Alpha, MATLAB      | `numpy`, `sympy`, `scipy`                     |

Semestre 2:

| **Asignatura**                  | **Problema a abordar con IA**                                                                                  | **Por qué usar IA**                                                                                              | **Herramienta de IA**                                            | **Herramienta comercial** | **Equivalente en Python**                     |
|---------------------------------|----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------|------------------------------------------------|
| Humanismo y Cultura Ciudadana    | Análisis de datos de encuestas de percepción social en temas de ética y cultura ciudadana.                    | Permite identificar patrones de percepción y comportamiento en diferentes segmentos de la población.             | NLP, análisis de sentimiento, visualización de datos              | SurveyMonkey, Tableau      | `TextBlob`, `pandas`, `matplotlib`            |
| Teoría Organizacional           | Identificación de estructuras organizativas óptimas a partir de datos de desempeño.                           | Facilita el análisis de estructuras más efectivas mediante el análisis de rendimiento y relaciones laborales.    | Clustering, análisis de redes, grafos                             | Gephi, Power BI            | `networkx`, `scikit-learn`, `matplotlib`      |
| Principios de Economía          | Predicción de variables económicas básicas para análisis macroeconómico y microeconómico.                     | Ayuda a predecir tendencias económicas con base en modelos de datos históricos.                                  | Modelos predictivos, regresión                                    | Tableau, Power BI          | `scikit-learn`, `statsmodels`, `pandas`       |
| Fundamentos de Mercadeo         | Segmentación de mercado basada en datos demográficos y comportamiento de clientes.                            | Mejora la efectividad en la creación de estrategias de marketing enfocadas en grupos específicos.                | Clustering, análisis de segmentación                               | HubSpot, Google Analytics  | `scikit-learn`, `pandas`, `seaborn`           |
| Cálculo I                       | Resolución automática de problemas de derivadas e integrales.                                                  | Simplifica y agiliza el proceso de cálculo de problemas complejos en derivación e integración.                   | Resolución simbólica, análisis matemático                          | Wolfram Alpha, MATLAB      | `sympy`, `numpy`, `scipy`                     |
| Costos y Presupuestos           | Predicción de costos futuros en base a datos históricos y variables de inflación.                             | Permite predecir variaciones en costos para mejorar la toma de decisiones presupuestarias.                       | Regresión, series de tiempo                                       | SAP, Oracle                | `statsmodels`, `scikit-learn`, `pandas`       |

Semestre 3:

| **Asignatura**                  | **Problema a abordar con IA**                                                                                   | **Por qué usar IA**                                                                                              | **Herramienta de IA**                                            | **Herramienta comercial** | **Equivalente en Python**                     |
|---------------------------------|-----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------|------------------------------------------------|
| Cristología Básica              | Análisis de textos teológicos para identificar temas y conceptos clave.                                        | Permite analizar grandes volúmenes de texto y descubrir patrones temáticos o conceptuales.                       | NLP, modelado de temas                                          | IBM Watson NLU, MonkeyLearn | `nltk`, `gensim`, `spacy`                     |
| Evolución del Pensamiento Estratégico | Identificación de tendencias en el pensamiento estratégico mediante análisis de textos históricos y actuales. | Facilita el reconocimiento de patrones en la evolución de teorías estratégicas y su relación con el contexto.    | NLP, análisis de sentimiento, clustering de documentos           | Tableau, Power BI           | `TextBlob`, `gensim`, `scikit-learn`           |
| Microeconomía                   | Análisis de comportamiento de mercado y predicción de demanda.                                                 | Proporciona predicciones basadas en datos históricos y patrones de consumo para mejores decisiones estratégicas.  | Modelos predictivos, regresión lineal, análisis de datos         | Stata, EViews               | `scikit-learn`, `statsmodels`, `pandas`        |
| Fundamentos Jurídicos I         | Clasificación de tipos de documentos legales y extracción de información clave.                                | Permite el procesamiento y organización automática de documentos legales.                                        | Procesamiento de lenguaje natural, clasificación de texto        | LexisNexis, IBM Watson      | `nltk`, `spacy`, `transformers`                |
| Cálculo II                      | Resolución automática de problemas avanzados de cálculo, como series y sucesiones.                             | Simplifica la resolución y análisis de problemas matemáticos complejos.                                          | Resolución simbólica, cálculo numérico                           | MATLAB, Wolfram Alpha       | `sympy`, `scipy`, `numpy`                      |
| Estadística I                   | Identificación de patrones en grandes conjuntos de datos para tomar decisiones informadas.                      | Facilita el análisis de tendencias y la predicción en datos empresariales.                                       | Clustering, análisis exploratorio de datos                        | SPSS, Minitab               | `scikit-learn`, `pandas`, `matplotlib`         |
| Ingeniería Económica            | Evaluación de proyectos de inversión mediante simulaciones financieras.                                        | Ayuda a simular diferentes escenarios económicos y evaluar rentabilidad de proyectos.                           | Simulación de Monte Carlo, modelos de optimización               | @Risk, Crystal Ball         | `numpy`, `pandas`, `scipy.stats`               |


Semestre 4:

| **Asignatura**                  | **Problema a abordar con IA**                                                                                   | **Por qué usar IA**                                                                                              | **Herramienta de IA**                                            | **Herramienta comercial** | **Equivalente en Python**                     |
|---------------------------------|-----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------|------------------------------------------------|
| Ética General                   | Análisis de opiniones sobre dilemas éticos para identificar patrones de pensamiento moral.                     | Permite identificar tendencias en percepciones éticas, útil para estudios de cultura organizacional.             | NLP, análisis de sentimiento                                     | MonkeyLearn, IBM Watson    | `TextBlob`, `VADER`, `pandas`                 |
| Macroeconomía                   | Predicción de variables macroeconómicas clave, como el PIB y la inflación.                                     | Facilita la toma de decisiones basadas en tendencias económicas globales.                                        | Series de tiempo, modelos ARIMA, redes neuronales recurrentes     | EViews, Stata              | `statsmodels`, `tensorflow`, `pandas`         |
| Estadística II                  | Análisis predictivo de tendencias para optimizar decisiones de negocio.                                        | Permite prever cambios y realizar ajustes estratégicos basados en tendencias de datos.                           | Modelos de regresión, análisis de series de tiempo               | SPSS, Tableau              | `scikit-learn`, `statsmodels`, `matplotlib`   |
| Cambio y Transformación Organizacional | Análisis de patrones en la cultura organizacional para identificar áreas de mejora.                        | Facilita la detección de áreas críticas en la cultura de trabajo y la relación entre departamentos.              | Análisis de redes, clustering, minería de datos                  | Power BI, Gephi            | `networkx`, `scipy`, `scikit-learn`           |
| Fundamentos Jurídicos II        | Procesamiento de documentos legales y extracción de cláusulas relevantes.                                      | Optimiza la revisión y clasificación de documentos legales.                                                      | NLP, extracción de entidades nombradas                            | LexisNexis, IBM Watson      | `spacy`, `nltk`, `transformers`               |
| Administración Financiera       | Optimización de portafolios de inversión mediante simulaciones y modelos predictivos.                         | Permite maximizar el rendimiento financiero y gestionar el riesgo.                                               | Optimización de portafolio, simulación de Monte Carlo             | Bloomberg, Crystal Ball     | `numpy`, `pandas`, `cvxpy`                    |
| Comportamiento del Consumidor   | Segmentación de consumidores y análisis de comportamiento de compra.                                           | Permite comprender mejor a los consumidores y ajustar las estrategias de marketing.                              | Clustering, análisis de patrones, NLP                             | Google Analytics, HubSpot   | `scikit-learn`, `pandas`, `nltk`              |


Semestre 5:

| **Asignatura**                  | **Problema a abordar con IA**                                                                                  | **Por qué usar IA**                                                                                              | **Herramienta de IA**                                            | **Herramienta comercial** | **Equivalente en Python**                     |
|---------------------------------|----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------|------------------------------------------------|
| Ética Profesional               | Análisis de códigos éticos para detectar puntos de conflicto ético en distintas áreas de una organización.     | Facilita la revisión de normas éticas y permite identificar áreas de riesgo ético en la empresa.                | NLP, clasificación de texto                                      | IBM Watson NLU, LexisNexis | `nltk`, `spacy`, `transformers`               |
| Línea de Formación Humanista I  | Análisis de discursos y textos para entender temas sociales y éticos relevantes.                              | Permite identificar y analizar tendencias en el pensamiento social y ético mediante procesamiento de texto.      | Modelado de temas, análisis de sentimiento                        | MonkeyLearn, Tableau       | `TextBlob`, `gensim`, `scikit-learn`          |
| Gestión Humana                  | Análisis de rotación de personal y predicción de desvinculaciones en base a datos históricos.                  | Ayuda a identificar patrones de rotación y optimizar estrategias de retención de talento.                       | Modelos predictivos, análisis de regresión                         | Workday, IBM Talent Insights | `scikit-learn`, `pandas`, `xgboost`         |
| Economía y Comercio Internacional | Predicción de variables comerciales en mercados internacionales para toma de decisiones estratégicas.        | Facilita la planificación y gestión de estrategias de exportación/importación.                                   | Series de tiempo, modelos de predicción                           | Stata, EViews              | `statsmodels`, `scikit-learn`, `pandas`       |
| Finanzas Corporativas           | Optimización de inversiones y análisis de riesgos mediante simulaciones y modelos predictivos.                | Mejora la gestión financiera y minimiza riesgos mediante predicciones de rendimiento financiero.                | Simulación de Monte Carlo, optimización de portafolios           | Bloomberg, Crystal Ball    | `numpy`, `pandas`, `scipy.stats`              |
| Investigación y Plan de Mercadeo Estratégico | Segmentación avanzada de mercados y análisis de datos de clientes.                        | Permite obtener una visión más precisa de los diferentes segmentos y ajustar estrategias de mercadeo.          | Clustering, análisis de patrones, NLP                             | HubSpot, Google Analytics  | `scikit-learn`, `pandas`, `nltk`              |
| Administración de la Producción | Optimización de procesos de producción y control de inventarios en tiempo real.                               | Mejora la eficiencia y reduce los costos al prever necesidades y optimizar el uso de recursos.                  | Series de tiempo, optimización, redes neuronales recurrentes      | SAP, Oracle                | `scipy.optimize`, `statsmodels`, `keras`      |


Semestre 6:

| **Asignatura**                  | **Problema a abordar con IA**                                                                                  | **Por qué usar IA**                                                                                              | **Herramienta de IA**                                            | **Herramienta comercial** | **Equivalente en Python**                     |
|---------------------------------|----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------|------------------------------------------------|
| Línea de Formación Humanista II  | Análisis de textos para identificar temas sociales relevantes y patrones de pensamiento crítico.              | Ayuda a extraer patrones y temas de gran cantidad de textos de forma automatizada.                               | NLP, modelado de temas                                          | IBM Watson NLU, Tableau    | `spacy`, `gensim`, `nltk`                     |
| Gestión de Procesos             | Identificación de cuellos de botella y optimización de procesos productivos.                                  | Permite optimizar procesos y recursos, reduciendo tiempos y costos de producción.                                | Modelos de optimización, simulación de procesos                  | SAP, Arena Simulation      | `simpy`, `scipy.optimize`, `pandas`           |
| Coyuntura Económica             | Análisis predictivo de tendencias económicas y su impacto en el mercado local.                                | Facilita la toma de decisiones en función de las tendencias económicas futuras.                                  | Modelos de predicción, series de tiempo                          | EViews, Stata              | `statsmodels`, `prophet`, `pandas`            |
| Optimización                    | Resolución de problemas de optimización complejos para maximizar la eficiencia en distintas áreas.            | Automatiza el proceso de encontrar soluciones óptimas en problemas de múltiples variables.                      | Algoritmos de optimización, programación lineal                   | Lindo, MATLAB              | `scipy.optimize`, `cvxpy`, `pulp`             |
| Investigación I                 | Análisis de grandes volúmenes de datos para identificar patrones en la investigación de mercado.              | Permite extraer patrones y tendencias en los datos que pueden guiar las decisiones estratégicas.                 | Clustering, análisis exploratorio de datos                        | Tableau, Power BI          | `pandas`, `seaborn`, `scikit-learn`           |
| Optativa                        | Dependiendo del tema específico de la optativa.                                                               | Puede variar según el enfoque del curso optativo.                                                                | Variado según el área                                           | Variado según el área      | Variado según el área                        |
| Prepráctica I                   | Análisis de datos sobre posibles campos de práctica y desempeño en áreas específicas.                         | Facilita la identificación de oportunidades de prácticas adecuadas para cada perfil.                            | Análisis de datos, clustering, NLP                               | LinkedIn, Tableau          | `pandas`, `scikit-learn`, `nltk`              |

Semestre 7:

| **Asignatura**                  | **Problema a abordar con IA**                                                                                  | **Por qué usar IA**                                                                                              | **Herramienta de IA**                                            | **Herramienta comercial** | **Equivalente en Python**                     |
|---------------------------------|----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------|------------------------------------------------|
| Ética Social                    | Identificación de temas sociales críticos y patrones éticos en el ámbito empresarial.                         | Permite identificar tendencias en la percepción social y ética, útil para entender la responsabilidad social.    | NLP, análisis de sentimiento                                    | MonkeyLearn, IBM Watson    | `TextBlob`, `VADER`, `pandas`                 |
| Auditoría Administrativa y Diagnóstico Organizacional | Análisis de rendimiento organizacional y detección de áreas de mejora. | Facilita el diagnóstico de problemas estructurales y operacionales mediante análisis de datos históricos.       | Clustering, análisis de redes, minería de datos                  | Power BI, Tableau          | `pandas`, `scipy`, `scikit-learn`             |
| Formulación, Evaluación y Gestión de Proyectos | Evaluación de viabilidad de proyectos usando simulación de escenarios y análisis de riesgos.               | Ayuda a optimizar la toma de decisiones y la gestión de riesgos en proyectos complejos.                          | Simulación de Monte Carlo, modelos predictivos                   | Crystal Ball, Primavera    | `numpy`, `scipy.stats`, `pandas`              |
| Investigación II                | Análisis de datos de investigaciones anteriores para identificar nuevas oportunidades de negocio.            | Facilita la identificación de tendencias y nuevas oportunidades basadas en datos históricos.                     | Análisis de patrones, clustering                                  | SPSS, Tableau              | `scikit-learn`, `pandas`, `matplotlib`        |
| Simulación                      | Simulación de escenarios en entornos de negocios para evaluar decisiones estratégicas.                        | Permite observar resultados potenciales de decisiones bajo diferentes condiciones y mejorar la toma de decisiones. | Simulación de Monte Carlo, modelos de optimización               | AnyLogic, Arena Simulation  | `simpy`, `numpy`, `scipy`                    |
| Gestión Logística Integral      | Optimización de la cadena de suministro y predicción de demanda.                                              | Permite reducir costos y mejorar la eficiencia en la cadena de suministro mediante predicción y optimización.    | Series de tiempo, redes neuronales recurrentes                   | SAP SCM, Oracle SCM        | `statsmodels`, `keras`, `scipy.optimize`      |
| Prepráctica II                  | Análisis de desempeño de áreas de práctica y comparación de oportunidades laborales.                          | Facilita la identificación de áreas de mayor crecimiento y oportunidades según el perfil de cada estudiante.     | Análisis de datos, clustering, NLP                               | LinkedIn, Tableau          | `pandas`, `scikit-learn`, `nltk`              |


Semestre 8:

| **Asignatura**                  | **Problema a abordar con IA**                                                                                  | **Por qué usar IA**                                                                                              | **Herramienta de IA**                                            | **Herramienta comercial** | **Equivalente en Python**                     |
|---------------------------------|----------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------|----------------------------|------------------------------------------------|
| Gerencia Estratégica y Prospectiva | Predicción de cambios en el mercado y tendencias para la planificación estratégica a largo plazo.            | Facilita la anticipación de cambios en el mercado y la adaptación de estrategias en consecuencia.                | Series de tiempo, modelos de predicción, redes neuronales        | IBM SPSS, Tableau          | `statsmodels`, `prophet`, `tensorflow`        |
| Electivas                       | Dependiendo del enfoque específico de cada electiva.                                                          | La aplicabilidad de IA puede variar según el tema de cada electiva.                                              | Variable según el área                                           | Variable según el área     | Variable según el área                       |
| Optativa                        | Dependiendo del enfoque específico de cada optativa.                                                          | Puede adaptarse al tema de la optativa para resolver problemas específicos.                                       | Variable según el área                                           | Variable según el área     | Variable según el área                       |
| Práctica                        | Análisis del rendimiento de los estudiantes en prácticas y recomendaciones para mejorar su empleabilidad.     | Permite identificar áreas de mejora en el desarrollo profesional de los estudiantes y su adecuación al mercado.   | Análisis de datos, minería de texto, clustering                   | LinkedIn, IBM Watson       | `pandas`, `scikit-learn`, `nltk`              |



**Administración de Empresas**

| **Curso** | **Opciones Comerciales o Gratuitas** | **Equivalente en Google Colab y Python** |
| --- | --- | --- |
| **Lengua y Cultura** | **Grammarly** (para corrección de texto), **QuillBot** (paráfrasis), **Google Translate** (traducción automática) | **Transformers de Hugging Face** (para traducción automática y análisis de texto), **spaCy** (análisis de estructura del texto) |
| **Emprendimiento y Responsabilidad Social** | **Tableau**, **Power BI** (para análisis de impacto social), **Social Studio** (para monitoreo social) | **Pandas** y **Matplotlib** (análisis de datos sociales), **NLTK** o **TextBlob** (análisis de opiniones de usuarios sobre impacto social) |
| **Pensamiento Administrativo** | **Lucidchart** o **Miro** (para diagramas), **IBM Watson Analytics** (análisis predictivo) | **NetworkX** (para crear y analizar redes organizacionales), **Scikit-learn** (análisis predictivo para optimización administrativa) |
| **Estados Financieros** | **QuickBooks** (contabilidad), **Zoho Books**, **Excel con Power BI** | **Pandas** y **Matplotlib/Seaborn** (análisis financiero), **Statsmodels** o **Prophet** (para pronósticos financieros) |
| **Sistemas Lineales** | **MATLAB**, **Wolfram Alpha**, **GeoGebra** (para resolver sistemas de ecuaciones) | **Numpy** y **SciPy** (para resolución de sistemas lineales y álgebra lineal) |
| **Matemáticas Operativas** | **MATLAB**, **Desmos**, **Symbolab** | **SymPy** (resolución simbólica y álgebra), **Scipy.optimize** (optimización de funciones matemáticas) |
| **Teoría Organizacional** | **Lucidchart**, **OrgWeaver** | **NetworkX** (análisis de estructuras organizacionales), **Matplotlib** (visualización de jerarquías y estructuras) |
| **Principios de Economía** | **Power BI** para visualización de datos, **Tableau** | **Pandas**, **Matplotlib**, **Seaborn** (para análisis y visualización de datos económicos) |
| **Fundamentos de Mercadeo** | **Google Analytics**, **HubSpot** | **Pandas** y **Scikit-learn** (análisis de datos de mercado y clustering), **TextBlob** o **VADER** (para análisis de sentimientos) |
| **Cálculo I & II** | **MATLAB**, **Wolfram Alpha** | **SymPy** (cálculo simbólico y álgebra), **NumPy** (para operaciones vectoriales y matriciales en cálculos) |
| **Costos y Presupuestos** | **Zoho Analytics**, **QuickBooks** | **Pandas** (para análisis de costos y presupuestos), **Matplotlib** para visualizar tendencias y datos financieros |
| **Evolución del Pensamiento Estratégico** | **Lucidchart**, **Miro** | **Matplotlib** (visualización de estrategias y evolución), **NetworkX** (mapas conceptuales de estrategias) |
| **Microeconomía** | **Tableau**, **Power BI** | **Pandas** y **Matplotlib** para análisis de oferta y demanda, **Scikit-learn** (modelos de predicción de comportamiento) |
| **Fundamentos Jurídicos I & II** | **CaseMine** (análisis legal), **LexisNexis** | **spaCy** (análisis de texto legal), **NLTK** (procesamiento de lenguaje natural para extraer conceptos legales) |
| **Estadística I & II** | **IBM SPSS**, **Minitab** | **Scipy.stats** y **Statsmodels** (análisis estadístico y pruebas de hipótesis), **Seaborn** para visualización de estadísticas |
| **Ingeniería Económica** | **Excel** (con Solver), **MATLAB** | **Numpy** y **Scipy.optimize** (análisis de flujos de caja, VAN, TIR), **Statsmodels** para proyecciones financieras |
| **Ética General y Profesional** | **Miro** (para mapas conceptuales), **Tableau** (análisis de impacto) | **NLTK** o **TextBlob** para análisis de texto y opinión, **Wordcloud** (visualización de palabras clave en ética) |
| **Macroeconomía** | **Bloomberg Terminal**, **Power BI** | **Pandas** y **Matplotlib** para análisis macroeconómico, **Statsmodels** (análisis de series temporales y proyecciones) |
| **Cambio y Transformación Organizacional** | **OrgMapper** (para análisis organizacional), **Lucidchart** | **NetworkX** (análisis de redes de cambio organizacional), **Pandas** (visualización de tendencias y datos de cambio) |
| **Administración Financiera** | **QuickBooks**, **Power BI** | **Pandas** y **Matplotlib** (análisis de flujo de caja), **Statsmodels** (pronósticos financieros y simulaciones) |
| **Comportamiento del Consumidor** | **Google Analytics**, **HubSpot** | **Pandas** y **Scikit-learn** (clustering de consumidores), **NLTK** o **VADER** (análisis de sentimientos de consumidores) |
| **Gestión Humana** | **BambooHR**, **Workday** | **Pandas** y **Matplotlib** para análisis de datos de empleados, **Scikit-learn** para modelos de retención y análisis predictivo |
| **Economía y Comercio Internacional** | **Tableau**, **Power BI** | **Pandas** y **Matplotlib** para visualización de datos de comercio, **Statsmodels** (análisis de tendencias en comercio internacional) |
| **Finanzas Corporativas** | **Excel** (con Solver), **Power BI** | **Pandas** y **Statsmodels** para análisis financiero, **Scipy.optimize** (para optimización de portafolios) |
| **Investigación y Plan de Mercadeo Estratégico** | **Qualtrics**, **SurveyMonkey** | **Pandas** para análisis de encuestas, **Seaborn** y **Matplotlib** para visualización, **TextBlob** para análisis de opiniones |
| **Administración de la Producción** | **Microsoft Project**, **SAP ERP** | **Pandas** (análisis de procesos de producción), **SimPy** para simulación de procesos productivos |
| **Gestión de Procesos** | **Lucidchart**, **Microsoft Visio** | **SimPy** (simulación de procesos), **Pandas** (para modelar flujos y analizar tiempos) |
| **Coyuntura Económica** | **Power BI**, **Bloomberg** | **Statsmodels** y **Prophet** para predicción de tendencias macroeconómicas, **Matplotlib** para visualización de tendencias |
| **Optimización** | **Gurobi**, **Excel con Solver** | **Scipy.optimize** para optimización de funciones, **Pyomo** para problemas complejos de optimización |
| **Investigación I & II** | **IBM SPSS**, **Qualtrics** | **Pandas** para manejo de datos de investigación, **Statsmodels** y **Seaborn** para visualización y análisis |
| **Auditoría Administrativa y Diagnóstico Organizacional** | **Tableau**, **Power BI** | **Pandas** (análisis de KPIs y métricas de desempeño), **Scikit-learn** para modelos predictivos |
| **Formulación, Evaluación y Gestión de Proyectos** | **Microsoft Project**, **Asana** | **Pandas** para analizar proyectos, **SimPy** para simulación de tiempos de proyecto |
| **Simulación** | **AnyLogic**, **Arena Simulation** | **SimPy** (simulación de eventos), **Matplotlib** para visualizar simulaciones |
| **Gestión Logística Integral** | **SAP ERP**, **Route4Me** | **Google OR-Tools** para optimización de rutas, **Pandas** y **Scipy.optimize** para análisis de logística |
| **Gerencia Estratégica y Prospectiva** | **Power BI**, **Tableau** | **Statsmodels** y **Prophet** para predicción de tendencias, **Matplotlib** para visualizar análisis estratégico |


**Economía**

| **Curso** | **Opciones Comerciales o Gratuitas** | **Equivalente en Google Colab y Python** |
| --- | --- | --- |
| **Historia Económica** | **Tableau Public** (para visualización de datos históricos), **Google Trends** (análisis de tendencias históricas) | **Pandas** y **Matplotlib** (para análisis de datos históricos), **Seaborn** (visualización de tendencias) |
| **Técnicas de Medición Económica** | **IBM SPSS**, **Minitab** | **Pandas** (análisis de datos), **Statsmodels** (pruebas estadísticas), **Scipy.stats** para análisis estadístico avanzado |
| **Matemáticas Operativas** | **MATLAB**, **GeoGebra**, **Desmos** | **SymPy** para cálculo simbólico y álgebra, **Scipy.optimize** para optimización matemática |
| **Sistemas Lineales** | **MATLAB**, **Wolfram Alpha** | **Numpy** y **SciPy** (resolución de sistemas lineales) |
| **Lenguaje y Cultura** | **Grammarly** (corrección), **Google Translate** | **Transformers** de Hugging Face (traducción y análisis de texto), **spaCy** para procesamiento de lenguaje |
| **Humanismo, Cultura y Ciudadanía** | **Miro** (diagramación), **Lucidchart** | **Matplotlib** y **Wordcloud** para crear visualizaciones de análisis cualitativo |
| **Principios de Economía** | **Tableau**, **Power BI** | **Pandas** y **Matplotlib** (visualización de datos económicos), **Scikit-learn** para predicciones básicas |
| **Hermenéutica de las Doctrinas Económicas** | **Miro**, **Lucidchart** | **spaCy** y **NLTK** (procesamiento de texto para análisis de doctrinas económicas) |
| **Estados Financieros** | **QuickBooks**, **Excel** | **Pandas** y **Matplotlib** (para análisis financiero y proyecciones), **Statsmodels** para modelos de series temporales |
| **Cálculo I & II** | **MATLAB**, **Wolfram Alpha** | **SymPy** (cálculo simbólico), **Numpy** para operaciones vectoriales y matrices |
| **Cristología Básica** | **Bible Gateway**, **Logos Bible Software** | **Transformers** (análisis de textos bíblicos), **spaCy** para procesamiento de lenguaje bíblico |
| **Ética General** | **Lucidchart** (diagramas), **Miro** (mapas conceptuales) | **Wordcloud** (visualización de temas éticos), **NLTK** para análisis de texto ético |
| **Microeconomía** | **Tableau**, **Power BI** | **Pandas** y **Matplotlib** para análisis de demanda y oferta, **Scikit-learn** para modelos de predicción |
| **Macroeconomía** | **Bloomberg Terminal**, **Eikon** | **Pandas** y **Statsmodels** (análisis de series temporales macroeconómicas), **Matplotlib** para visualizar tendencias |
| **Ingeniería Económica** | **Excel con Solver**, **MATLAB** | **Scipy.optimize** (para análisis de valor presente y tasa interna de retorno), **Statsmodels** (para modelos de proyección económica) |
| **Estadística I & II** | **IBM SPSS**, **Minitab** | **Statsmodels** y **Scipy.stats** (análisis estadístico), **Seaborn** para visualización de datos estadísticos |
| **Emprendimiento y Responsabilidad Social** | **Qualtrics** (para encuestas), **Power BI** (visualización) | **Pandas** y **Matplotlib** (para análisis de impacto social), **TextBlob** para análisis de opiniones |
| **Microeconomía Intermedia** | **Tableau**, **Power BI** | **Pandas** y **Scikit-learn** para modelos de predicción en consumo y oferta, **Statsmodels** (análisis de elasticidad) |
| **Macroeconomía Intermedia** | **Bloomberg**, **Eikon**, **Power BI** | **Statsmodels** y **Prophet** (modelos de predicción de tendencias macroeconómicas), **Matplotlib** (visualización de tendencias) |
| **Economía y Comercio Internacional** | **Tableau**, **Power BI** | **Pandas** y **Statsmodels** para análisis de datos de comercio internacional, **Seaborn** para visualización de datos |
| **Administración Financiera** | **QuickBooks**, **Zoho Books**, **Power BI** | **Pandas** (análisis de flujos de caja y proyecciones), **Statsmodels** (para pronósticos financieros) |
| **Economía Matemática (Optimización Dinámica)** | **Gurobi**, **MATLAB** | **Scipy.optimize** y **Pyomo** (optimización), **SymPy** para cálculos simbólicos en optimización dinámica |
| **Microeconomía Avanzada** | **MATLAB**, **Stata** | **Pandas** y **Scipy.optimize** para modelos de teoría del consumidor y productor, **Statsmodels** (para análisis de oferta y demanda avanzada) |
| **Macroeconomía Avanzada** | **Bloomberg**, **Eikon** | **Statsmodels** (modelos de series temporales y predicción), **Prophet** (modelado de tendencias de crecimiento) |
| **Economía y Finanzas Internacionales** | **Power BI**, **Tableau** | **Pandas** y **Statsmodels** (análisis de series temporales), **Matplotlib** para visualización de datos |
| **Teoría del Desarrollo** | **Tableau**, **QGIS** (para análisis de desarrollo económico y geoespacial) | **Pandas** (análisis de indicadores de desarrollo), **Geopandas** y **Matplotlib** (visualización geoespacial) |
| **Finanzas Corporativas** | **Excel** (con Solver), **Power BI** | **Pandas** y **Scipy.optimize** (para optimización de portafolios financieros), **Statsmodels** (proyección de ingresos y gastos) |
| **Teorías de Juegos** | **MATLAB**, **AnyLogic** | **Nashpy** (análisis de juegos), **SymPy** para resolución simbólica de juegos simples |
| **Econometría Básica** | **IBM SPSS**, **Stata** | **Statsmodels** y **Scikit-learn** para regresiones y modelos de predicción, **Seaborn** para visualización |
| **Formulación y Evaluación de Proyectos** | **Microsoft Project**, **Asana** | **Pandas** (análisis de flujos de proyecto), **SimPy** para simulación de tiempos de ejecución |
| **Geografía Económica** | **QGIS**, **Tableau** | **Geopandas** (análisis espacial y geográfico), **Folium** (visualización de datos geográficos en mapas interactivos) |
| **Modelos de Industrialización en Colombia** | **Power BI**, **Tableau** | **Pandas** y **Matplotlib** para análisis de datos históricos, **Seaborn** (visualización de datos industriales) |
| **Econometría Avanzada** | **Stata**, **IBM SPSS** | **Statsmodels** (para modelos avanzados de econometría), **Scikit-learn** (para regresión avanzada y análisis predictivo) |
| **Desarrollo Local y Regional** | **QGIS**, **Tableau** | **Geopandas** (para análisis espacial de datos locales), **Folium** (para visualización interactiva de desarrollo regional en mapas) |
| **Coyuntura Económica** | **Bloomberg**, **Eikon**, **Power BI** | **Statsmodels** y **Prophet** para predicción de tendencias, **Pandas** (análisis y visualización de series temporales) |
| **Investigación I & II** | **Qualtrics**, **IBM SPSS** | **Pandas** (manejo de datos de encuestas), **Scipy.stats** y **Statsmodels** (análisis estadístico y visualización) |
| **Teoría de la Empresa** | **Tableau**, **Miro** | **NetworkX** (análisis de redes y estructuras empresariales), **Matplotlib** para visualización de estructuras de mercado |
| **Práctica (10 créditos)** | **Herramientas específicas del área de práctica** | **Python** y Google Colab para aplicar herramientas de análisis, **Pandas** y **Matplotlib** para visualización y manejo de datos, según las necesidades del área de especialización |


**Gestión del Emprendimiento y la Innovación**

| **Curso** | **Opciones Comerciales o Gratuitas** | **Equivalente en Google Colab y Python** |
| --- | --- | --- |
| **Emprendimiento y Responsabilidad Social** | **Qualtrics**, **Tableau**, **SurveyMonkey** | **Pandas** y **Matplotlib** (para análisis de impacto social), **TextBlob** o **NLTK** (para análisis de opiniones) |
| **Núcleo Taller de Innovación 1, 2, 3, 4** | **Miro** (para mapas de ideas), **Lucidchart** | **NetworkX** (para mapear redes de innovación), **Matplotlib** y **PIL** para prototipos visuales |
| **Gestión Tecnológica** | **JIRA**, **Asana** | **Pandas** y **Matplotlib** para análisis de procesos, **SimPy** para simulación de implementación de tecnología |
| **Matemáticas Operativas** | **MATLAB**, **GeoGebra** | **SymPy** (para operaciones simbólicas y algebraicas), **Scipy.optimize** (para optimización matemática) |
| **Pensamiento Administrativo** | **Lucidchart**, **Miro** | **NetworkX** (para estructuras organizacionales), **Matplotlib** (para visualizar modelos administrativos) |
| **Estados Financieros** | **QuickBooks**, **Zoho Books** | **Pandas** y **Matplotlib** para análisis financiero, **Statsmodels** para predicciones de flujo de caja |
| **Lengua y Cultura** | **Grammarly** (corrección de texto), **Google Translate** | **Transformers** de Hugging Face (traducción y análisis de texto), **spaCy** (para procesamiento de lenguaje natural) |
| **Gestión de la Innovación** | **Miro**, **Lucidchart**, **Trello** | **Pandas** (para análisis de datos de innovación), **NetworkX** (para estructuras de innovación) |
| **Cálculo** | **MATLAB**, **Wolfram Alpha** | **SymPy** y **Numpy** para operaciones de cálculo y álgebra |
| **Principios de Economía** | **Power BI**, **Tableau** | **Pandas** y **Matplotlib** para visualización de datos económicos, **Statsmodels** para modelos económicos |
| **Costos y Presupuestos** | **Excel**, **Zoho Analytics** | **Pandas** y **Matplotlib** para modelado de presupuestos, **Scipy.optimize** para análisis de costos |
| **Fundamentos de Mercadeo** | **Google Analytics**, **HubSpot** | **Pandas** y **Scikit-learn** para análisis de mercado, **TextBlob** para análisis de sentimientos |
| **Humanismo y Cultura Ciudadana** | **Miro** (mapas de conceptos), **Lucidchart** | **Matplotlib** y **Wordcloud** para visualización de temas culturales y humanísticos |
| **Estructuras de I+D+i** | **Lucidchart**, **Miro**, **Asana** | **NetworkX** (para estructuras de innovación), **Matplotlib** para diagramas y prototipos visuales |
| **Estadística** | **IBM SPSS**, **Minitab** | **Statsmodels** y **Seaborn** para visualización y análisis estadístico |
| **Microeconomía** | **Tableau**, **Power BI** | **Pandas** y **Matplotlib** para análisis de oferta y demanda, **Scikit-learn** para modelos predictivos |
| **Ingeniería Económica** | **Excel con Solver**, **MATLAB** | **Pandas** y **Scipy.optimize** para análisis de VAN y TIR, **Statsmodels** para proyecciones económicas |
| **Investigación y Planeación Estratégica de Mercadeo** | **Qualtrics**, **SurveyMonkey**, **Google Trends** | **Pandas** para manejo de encuestas, **Seaborn** y **Matplotlib** para visualización, **TextBlob** para análisis de opiniones |
| **Cristología** | **Bible Gateway**, **Logos Bible Software** | **Transformers** y **spaCy** para procesamiento de textos religiosos |
| **Legislación para el Emprendimiento y la Innovación** | **LexisNexis**, **CaseMine** | **spaCy** y **NLTK** para análisis de documentos legales, **Wordcloud** para resaltar términos clave |
| **Proyecto de Creación de Empresa 1, 2, 3, 4** | **Miro**, **Lucidchart**, **Trello** | **Pandas** y **SimPy** para modelar procesos de creación de empresa, **Matplotlib** para visualización de estrategias de negocio |
| **Estadística II** | **IBM SPSS**, **Minitab** | **Statsmodels** y **Scipy.stats** para pruebas de hipótesis y regresión, **Seaborn** para visualización |
| **Macroeconomía** | **Bloomberg**, **Eikon**, **Power BI** | **Statsmodels** y **Prophet** para series temporales y análisis de tendencias macroeconómicas |
| **Formulación, Preparación, Evaluación y Gestión de Proyectos** | **Microsoft Project**, **Asana** | **SimPy** para simulación de tiempos de proyectos, **Pandas** para cronogramas y presupuestos |
| **E-Commerce y Marketing Digital** | **Google Analytics**, **Shopify Analytics** | **Pandas** y **Scikit-learn** para análisis de ventas, **TextBlob** para análisis de comentarios de usuarios |
| **Ética General** | **Lucidchart**, **Miro** | **NLTK** y **TextBlob** para análisis de texto ético, **Wordcloud** para visualización de temas éticos |
| **Challenge of Entrepreneurship** | **Miro**, **Lucidchart**, **Trello** | **Pandas** y **Matplotlib** para análisis de modelos de negocio, **SimPy** para simulaciones de escenarios de emprendimiento |
| **Gestión del Conocimiento** | **Confluence**, **Notion** | **Pandas** (organización de datos), **NLTK** para análisis de temas en documentación de conocimiento |
| **Economía y Comercio Internacional** | **Tableau**, **Power BI** | **Pandas** y **Statsmodels** para análisis de comercio, **Seaborn** para visualización de datos internacionales |
| **Gestión Humana** | **BambooHR**, **Workday** | **Pandas** para análisis de datos de empleados, **Scikit-learn** para predicciones de retención y modelos de desempeño |
| **Administración Financiera** | **QuickBooks**, **Zoho Books**, **Excel** | **Pandas** y **Statsmodels** para análisis de flujo de caja, **Matplotlib** para visualización de datos financieros |
| **Intraemprendimiento Corporativo** | **Miro**, **Lucidchart**, **Asana** | **NetworkX** para análisis de redes organizacionales, **Matplotlib** para visualizar estructuras de emprendimiento |
| **Economía de la PYME** | **Power BI**, **Tableau** | **Pandas** para análisis de datos financieros de pymes, **Scipy.optimize** para optimización de recursos |
| **Investigación I & II** | **Qualtrics**, **IBM SPSS** | **Pandas** y **Seaborn** para análisis de encuestas, **Statsmodels** para análisis estadístico avanzado |
| **Inmersión a Ecosistemas de Innovación** | **QGIS**, **Google Earth Engine** | **Geopandas** y **Folium** para visualización de mapas, **Pandas** para análisis de datos regionales |
| **Práctica Profesional** | **Herramientas específicas del área de práctica** | **Python** y Google Colab para implementar análisis y visualización, **Pandas** y **Matplotlib** según los datos del área de especialización |


**Negocios Internacionales** 

| **Curso** | **Opciones Comerciales o Gratuitas** | **Equivalente en Google Colab y Python** |
| --- | --- | --- |
| **Lenguaje y Cultura** | **Grammarly** (corrección de texto), **Google Translate** (traducción automática) | **Transformers** (para traducción y procesamiento de lenguaje natural), **spaCy** (análisis de estructura de texto) |
| **Introducción a los Negocios Internacionales** | **Tableau**, **Power BI** | **Pandas** y **Matplotlib** para visualización de datos de mercado global, **Seaborn** para análisis de tendencias económicas |
| **Estados Financieros** | **QuickBooks**, **Zoho Books**, **Excel** | **Pandas** (para análisis financiero), **Matplotlib** para visualización de datos financieros, **Statsmodels** para series temporales |
| **Pensamiento Administrativo** | **Miro**, **Lucidchart** | **NetworkX** para análisis de redes organizacionales, **Matplotlib** para visualización de diagramas |
| **Matemáticas Operativas** | **MATLAB**, **GeoGebra** | **SymPy** (para cálculo simbólico y álgebra), **Scipy.optimize** (para optimización) |
| **Sistemas Lineales** | **MATLAB**, **Wolfram Alpha** | **Numpy** y **SciPy** para resolución de sistemas lineales |
| **Humanismo y Cultura Ciudadana** | **Lucidchart**, **Miro** | **Matplotlib** y **Wordcloud** para visualizar temas de análisis cualitativo |
| **Geopolítica** | **Tableau** para visualización de datos geopolíticos, **Google Trends** para análisis de tendencias | **Pandas** para análisis de datos, **Folium** para mapas interactivos y visualización geoespacial |
| **Geografía** | **QGIS**, **Google Maps** | **Geopandas** y **Folium** para visualización de datos geográficos y análisis espacial |
| **Derecho Comercial Internacional** | **LexisNexis**, **CaseMine** | **spaCy** y **NLTK** para procesamiento de textos legales, **Wordcloud** para resaltar términos clave |
| **Cálculo I** | **MATLAB**, **Wolfram Alpha** | **SymPy** y **Numpy** para operaciones de cálculo y algebra |
| **Principios de Economía** | **Power BI**, **Tableau** | **Pandas** y **Matplotlib** para visualización de datos económicos, **Statsmodels** para análisis de datos económicos |
| **Cristología Básica** | **Bible Gateway**, **Logos Bible Software** | **Transformers** para análisis de textos, **spaCy** para procesamiento de textos religiosos |
| **Relaciones Internacionales** | **Miro** (diagramas de relaciones internacionales), **Lucidchart** | **NetworkX** para análisis de redes, **Matplotlib** para visualización de conexiones internacionales |
| **Cátedra Interdisciplinaria** | **Miro**, **Lucidchart** | **Matplotlib** para visualización de temas interdisciplinarios |
| **Ingeniería Económica** | **Excel con Solver**, **MATLAB** | **Scipy.optimize** (análisis de VAN y TIR), **Statsmodels** para modelos de proyecciones económicas |
| **Estadística I & II** | **IBM SPSS**, **Minitab** | **Scipy.stats** y **Statsmodels** para pruebas de hipótesis, **Seaborn** para visualización de datos estadísticos |
| **Cálculo II** | **MATLAB**, **Desmos** | **SymPy** y **Numpy** para cálculos avanzados y visualización de funciones |
| **Microeconomía** | **Tableau**, **Power BI** | **Pandas** y **Matplotlib** para análisis de demanda y oferta, **Scikit-learn** para predicciones básicas |
| **Culturas Internacionales** | **Qualtrics** (para encuestas culturales), **Google Trends** (análisis de intereses culturales) | **Pandas** y **Matplotlib** para análisis de datos culturales, **TextBlob** o **VADER** para análisis de opiniones |
| **Ética General** | **Miro**, **Lucidchart** | **Wordcloud** para visualización de temas éticos, **NLTK** para procesamiento de textos |
| **Emprendimiento y Responsabilidad Social** | **Power BI**, **Tableau** | **Pandas** y **Matplotlib** para análisis de impacto social, **TextBlob** para análisis de opiniones y percepciones |
| **Historia de los Negocios Internacionales** | **Tableau**, **Google Trends** | **Pandas** y **Matplotlib** para visualización de datos históricos, **Seaborn** para análisis de tendencias |
| **Macroeconomía** | **Bloomberg**, **Power BI** | **Statsmodels** y **Prophet** para series temporales y proyecciones, **Pandas** para análisis de datos macroeconómicos |
| **Fundamentos de Negociación** | **Qualtrics** (para encuestas), **Miro** (para diagramas de negociación) | **NLTK** para análisis de lenguaje en negociaciones, **Matplotlib** para visualización de estrategias |
| **Administración Financiera** | **Zoho Books**, **QuickBooks**, **Excel** | **Pandas** y **Matplotlib** (para análisis financiero), **Statsmodels** para proyecciones y análisis de flujos de caja |
| **Logística DFI** | **SAP ERP**, **Route4Me** | **Google OR-Tools** para optimización de rutas, **Pandas** y **Scipy.optimize** para modelos de logística |
| **Gestión Internacional del Recurso Humano** | **Workday**, **BambooHR** | **Pandas** para análisis de datos de empleados, **Scikit-learn** para modelos de predicción de retención |
| **Administración de la Producción** | **SAP ERP**, **Microsoft Project** | **SimPy** para simulación de procesos productivos, **Pandas** para análisis de datos de producción |
| **Economía y Comercio Internacional** | **Tableau**, **Power BI** | **Pandas** y **Statsmodels** para análisis de series temporales, **Matplotlib** para visualización de datos |
| **Régimen de Comercio Exterior** | **LexisNexis**, **CaseMine** | **spaCy** y **NLTK** para análisis de textos legales en comercio exterior, **Wordcloud** para resaltar términos clave |
| **Investigación I & II** | **Qualtrics**, **IBM SPSS** | **Pandas** (manejo de datos de encuestas), **Statsmodels** y **Seaborn** (análisis estadístico y visualización) |
| **Optimización** | **Gurobi**, **Excel con Solver** | **Scipy.optimize** para optimización de funciones, **Pyomo** para modelos de optimización complejos |
| **Economía y Finanzas Internacionales** | **Bloomberg**, **Power BI** | **Statsmodels** y **Prophet** (predicciones de finanzas internacionales), **Pandas** (análisis y visualización de series temporales) |
| **Acuerdos Multilaterales y Regionales** | **Tableau**, **Power BI** | **Pandas** y **Matplotlib** (para análisis y visualización de datos de acuerdos), **spaCy** (procesamiento de texto de documentos legales) |
| **Coyuntura Económica** | **Bloomberg**, **Eikon** | **Pandas** y **Statsmodels** para análisis de datos macroeconómicos, **Prophet** para predicción de series temporales |
| **Mercadeo Internacional** | **Google Analytics**, **HubSpot** | **Pandas** y **Scikit-learn** (para segmentación y clustering), **TextBlob** para análisis de sentimientos y opiniones |
| **Gerencia Internacional** | **Miro**, **Lucidchart** | **NetworkX** para análisis de redes de negocios internacionales, **Pandas** para análisis de datos |
| **Formulación, Evaluación y Gestión de Proyectos** | **Microsoft Project**, **Asana** | **SimPy** para simulación de tiempos de proyectos, **Pandas** (análisis de cronogramas y presupuestos) |
| **Simulación** | **AnyLogic**, **Arena Simulation** | **SimPy** para simulación de eventos discretos, **Matplotlib** para visualización de datos de simulación |
| **Práctica Profesional** | **Herramientas según el área de práctica** | **Python** y Google Colab para implementar técnicas de análisis, **Pandas** y **Matplotlib** para procesamiento y visualización de datos de acuerdo a la especialización |
![](https://unal.edu.co/typo3conf/ext/unal_skin_default/Resources/Public/images/escudoUnal_black.png)

### Predicción del número de vehículos registrados en el sistema de tránsito nacional

 El RUNT se define como un sistema de información que permite registrar y mantener actualizada , centralizada, autorizada y validada la misma sobre los registros de automotores, conductores, licencias de tránsito, empresas de transporte público, infractores, seguros, entre otros. Claro está, que se trata de un sistema que está siendo actualizado constantemente, girando alrededor de un sistema centralizado de información de tránsito y transporte el cual opera bajo un esquema de colaboración que depende de la información provista, en línea y en tiempo real.

El gran objetivo de este trabajo, es la implementación de un modelo que nos permita predecir el número de vehículos registrados diariamente en el Registro Único Nacional de Tránsito (RUNT), utilizando como insumo principal, la base de datos proporcionada para su elaboración, con el nombre de registros_autos_entrenamiento, la cual incluye la fecha y el número de registros de vehículos en determinada fecha. 

#### Breve introducción al problema
 El Registro Único Nacional de Tránsito, es un sistema que permite consolidar y actualizar la información del registro de tránsito, la cual garantiza una alta confiabilidad y transparencia en los procesos. Esta concebida como una solución en la que se integran gran bases de datos con información, permitiendo registrar, validar y autorizar de una forma unificada cada uno de los trámites.

La creación de un modelo que permita predecir el número de vehículos registrados diariamente, puede ser de gran utilidad para el organismo de tránsito de la ciudad, ya que con dicha información, pueden replantear futuros mecanismos en la metodología de registros, pueden obtener datos de gran utilidad, como la cantidad aproximada de vehículos registrados en un determinado año a futuro, lo que podría conducir a la implementación de nuevas medidas de tránsito, también se puede analizar que días puntuales se ven reflejados cambios drásticos en números de registros en el RUNT. 

#### Justificación de variables
 La base de datos que tenemos como insumo para analizar e implementar modelos predictivos, contiene 2 columnas con las variables **Fecha** dato numerico de fecha y **Unidades** dato entero real ,las cuales son muy dicientes, y pueden ser usadas, especialmente la primer variable mencionada, para la creación y reclasificación de nuevas variables que puedan tener efectos significativos sobre la variable respuesta, que en este caso es el número de registros diarios.

La estructura de las variables que contiene los datos es la siguiente:

![](https://github.com/Universidad-Nacional-TAE/Segundo-Trabajo-TAE/blob/main/Images/ImagenBase.png)

Se realiza un grafica de los datos adquiridos para ver su comportamiento en el tiempo en esos 6 años, a como cambia la adquisición de los vehiculos legales mes a mes en el pais colombiano.

Se puede observar que cada mes es variable en su icremento de inscripción de vehiculos, por tanto a simple inspección no se puede denotar como un sistema lineal variable en el tiempo, graficamente se aporta que cada año que pasa del 2012 a 2017 tiende a disminuir el numero de vehiculos inscritos, ecxeptuando el año 2013 y 2014, siendo este ultimo mayor ante su antecesor, ademas de que en el ultimo mes de cada uno de los años se reportan el mayor ingreso de vehiculos al registro del sistema de transito nacional, esto puede ser debido a la fiestas dicembrinas del pais y su cultura de compra en estas fechas en el pais colombiano.
#### Metodologia

#### Resultados obtenidos


#### Video
En siguiente enlace es un video promocional del trabajo realizado.[Video](https://youtu.be/K-YZjpwqD_Q)

#### Aplicación Web
Se realizó una aplicación web para mostrar los diferentes modelos de los datos de los vehiculos registrados, para que de esta forma el público libre pueda visualizar los datos y los modelos predictivos.[link](https://share.streamlit.io/sigomezgi/aplicacion-incidentes-viales/main/Main.py)


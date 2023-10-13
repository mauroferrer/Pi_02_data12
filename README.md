<img src=https://d31uz8lwfmyn8g.cloudfront.net/Assets/logo-henry-white-lg.png><p>


<p align="center">
<img src="https://tse4.mm.bing.net/th?id=OIP.reSA0MFdOEL-ygYTvIYe8AHaCw&pid=Api&P=0&h=180"  height=300>

</p>



## **ANALISIS**

<hr>

### **PAGINA 1**
<img src="Captura de pantalla 2023-07-18 195459.png"  height=500>


### **PAGINA 2**
 
<img src="Captura de pantalla 2023-07-18 202446.png"  height=500>

<hr>

# PROYECTO INDIVIDUAL Nº 2  
# Telecomunicaciones

## Objetivo  
Análisis para describir el comportamiento de la industria de las telecomunicaciones en Argentina, en particular el servicio de internet.

## Contenido del repositorio  
* **main**:  dashboard y pdf generado  
* **dataset**:  archivos fuente originales bajados de la página ENACOM, y otros modificados convenientemente para su análisis y utilización
* **EDA**: EDA.ipynb
* **ETL**: ETL.ipynb
  
## Análisis en base al dashboard  
Organizado por *pagina*  
### 1. Internet en Argentina ###  
- Contexto en grandes números para entender el desarrollo del servicio intenet en Argentina con datos actualizados al 3er trimestre de 2023  
### 2. Evolución de los accesos y de la velocidad ###  
- 2014 a 2017
    - las *"telcos"* utilizan la red de dispersión de cables de CU y tecnología *ADSL* para brindar el servicio de internet, la velocidad está limitada a 10Mbps con medias mucho menores entre 2 y 3 Mbps. *ADSL* es el acceso más utilizado en 2014 va disminuyendo suavemente (58 a 44%). Se observa una expansión muy lenta de la *FO* dirigida a los segmentos de clientes TOP
  
- 2017
    - el *ADSL* sobre par de CU pierde terreno a manos del *CM*, esta última tecnología posibilita mayor velocidad.  Se produce migración de clientes y cambio de estrategia de las *telcos* para poder seguir en el negocio: reinversión p/cambiar el medio físico *CU* a *coaxil* o *FO*, asociación/fusión con empresas de cable
- 2018
    - la velocidad media de bajada supera los 10Mbps, el *ADSL* ya no es viable para competir en el mercado
- 2018 a 2023
    - crecen los accesos *CM* en un +52% y el *CU* disminuye en -61%
    - para *FO* el crecimiento muy significativo, 13 veces más accesos lo que representa un +1220 %
- Conclusiones
    - para continuar en el negocio hay que brindar un servicio de alta velocidad, lo cual lleva a contar con una infraestructura que permita competir ahora y prepararse para el futuro (muy próximo).  El medio físico es sin duda alguna la *FO* muy superior al *cable oaxil*.
### 3. Localidades y tecnologías ###  
- mapa interactivo con filtros de:
    - provincia y localidad
    - tecnologías disponibles
        - telefonía fija (TF, WL, SAT)
        - telefonía móvil (3G, 4G)
        - accesos de internet (DU, ADSL, WL, SAT, CM, FO)
        - tecnología red de transporte (FO)
    - tabla con información relevante
    - para la toma de desiciones es fundamental el conocimiento del territorio, tecnologías disponibles y un concepto fuerte sobre las áreas y distancias dada la gran superficie a cubrir y cantidad de aglomerados urbanos en Argentina
### 4. Areas de interés ###  
- pagina interactiva con el objetivo de reconocer rápidamente las áreas de mayor interés para focalizar esfuerzos en la calidad de servicio y/o expansión de la red.
- un *área de interés* se conceptualiza como un agromerado urbano con gran cantidad de población y cuya penetración *accessos cada 100 habitantes* sea menor en relación a otras áreas similares.
- los siguientes filtros permiten visualizar estas áreas interactivamente:
    - provincia, partido
    - accesos cada 100 hab (límite superior)
- visualización de tabla con información relevante y cantidad de *áreas de interés* de acuerdo a la selección elegida de filtros


### 5. KPI - ARPU ### 
- promedio de ingresos por usuario
    - en este ejemplo, por no contar con *base de clientes* el kpi se ha calculado como el *promedio de ingresos por acceso*, cuyo resultado no es igual al ARPU real (por cliente)
    - kpi referido a la *rentabilidad del negocio* 
### 6. KPI - Penetración Internet ###  
- cantidad de accesos internet fija cada 100 habitantes
    - kpi referido al *desarrollo de la red de accesos internet fija*


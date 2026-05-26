# Proyecto_Analisis-de-embudo-y-retencion-para-MercadoLibre
Proyecto Bootcamp - TripleTen

## Objetivo

Identificar en qué etapa del proceso del embudo de conversión se pierden usuarios y cómo se puede mejorar para la retención a lo largo del tiempo. 

Identificar los principales puntos de fuga y evaluar la retención de usuarios por cohortes, para proponer mejoras accionables. 

Dicho análisis de información se realizara en el perido de [01/01/2025] al [31/08/2025] para identificar la etapa de perdida de usuarios. 

Para la retención de usuarios a lo largo del tiempo se realizara  entre el [01/01/2025] y el [01/06/2025], y se medira la tasa de retención en D7, D14, D21, D28.
## Herramientas 

* Google Colab. 
* PHYTON (PANDAS, NUMPY, SEABORN).
* SQL.

## Preguntas clave

#### ¿En qué etapa se pierden más usuarios?

1. Entre el [01/01/2025] y el [31/08/2025], ¿cuál es la tasa de conversión entre cada etapa clave del embudo?.
2. ¿En qué paso se observa la mayor caída porcentual de usuarios?
3. ¿Cómo varía esta pérdida por país (country)?

#### ¿Qué tan bien retenemos a los usuarios a lo largo del tiempo?

1. Para los usuarios que se registraron entre el [01/01/2025] y el [01/06/2025], ¿cuál es la tasa de retención en D7, D14, D21, D28?
2. ¿Cómo se comporta la retención por país (country)?

## Metodología

* Visualización de datos:
Examinar de los dataset.

* Construcción de embudo
Realizar el embudo de conversiones y calcular la tasa de caídas. 

* Ánalisis de información
Analizar la retención y cohortes, realizar la somulación de mejoras y redacción de informe ejecutivo.

#### Definición del Macro Journey (Embudo General)

El negocio esta interesado particularmente en el siguiente embudo de conversión.

<img width="1590" height="460" alt="image" src="https://github.com/user-attachments/assets/aaa58665-a3a7-4ffb-b011-7f2d5e1633ff" />


## Hallazgos y recomendaciones

#### Hallazgos:






D7 → Retención sólida →  > 80 % en todos los países
D14  →   Caída significativa →  52.33 % 
D21  →  Declive crítico → 22.89 %
D28  →  Retención mínima → 2.34 % 




#### Recomendaciones:

* Auditoría técnica inmediata en países criticos para identificar barreras esecíficas en la etapa "agregar al carrito".		

* Auditoria de integraciones de pago por país, moneda, regulación fiscal y forma de pago.		

* Revisar la app: Validar si existen porblemas de oferta, precios o usabilidad en esa etapa (UX, tiempo de carga, claridad de precios y disponibilidad).		

* Ofertas de marketing y notificaciones  (ofertas, promociones, cupones).
  
* Implementar notificaciones personalizadas entre los días D10 y D12 para prevenir caídas. 		

* Realizar dinámicas en los primeros rangos (D7,D14 y D21).		

* Impacto esperado de reducir > 50% la pérdida entre D7 → D14 y mejorar la retención hasta D21.
    
* Personalizar acciones por país según comportamiento para priorizar acciones en los segmentos con mayor perdida. 









## Diccionario de datos
 
 #### *Mercadolibre_funnel:*

   * Nombre del dataset: mercadolibre_funnel.csv

   * Descripción: Registra los eventos de usuarios durante el proceso de compra.

   * Campos


<img width="784" height="601" alt="image" src="https://github.com/user-attachments/assets/ad9aa042-d8f3-4096-af4c-95a8296575b0" />




#### *Mercadolibre_retention:* 

 * Nombre del dataset: mercadolibre_retention.csv

 * Descripción: Mide la actividad recurrente por usuario y periodo. 

 * Campos


<img width="727" height="649" alt="image" src="https://github.com/user-attachments/assets/7a359351-e7ab-4e7c-89ab-2e9770ea33f7" />

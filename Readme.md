# <h1 align=center>**`Proyecto Grupal: Análisis de factibilidad de inventarios de la distribuidora de licores "Elixir Emporium"`**</h1>

_Este proyecto tiene como objetivo abordar los desafíos que enfrenta la empresa distribuidora de licores en la gestión de su inventario. Mediante el análisis de datos se pretende resolver problemas de trazabilidad y variación de precios que afectan la proyección de ventas y la gestión de inventarios._
_A través del análisis de datos históricos, herramientas como SQL Server, Python y Power BI se utilizarán para optimizar niveles de inventario, prever la demanda y mejorar la eficiencia operativa. El resultado incluirá un dashboard interactivo con insights clave para la toma de decisiones estratégicas._

<p align="center">
<img src="fondo4.png"  height=300>
</p>

## 🤝 Integrantes de JBR ANALYTICS GROUP

* 👩‍💼**Jerez Perez, Laura Daniela - Data Engineer**
* 👨‍💼**Bonilla Abello, Diego Felipe- Data Scientist**
* 👩‍💼**Rincon de Vasquez, Mariugenia Edith- Data Analyst**

##  🏢 *Datos de la empresa:* **Elixir Emporium**

### Logo

<p align="center">
  <img src="LogoLicores.png" alt="Logo" width="350" height="350">
</p>

## 🏢 Descripción de la Empresa
_La compañía se dedica a la comercialización y distribución de una extensa variedad de bebidas alcohólicas, ofreciendo productos de reconocidas marcas nacionales e internacionales. Con una sólida red de proveedores, la empresa se encarga de abastecer tanto a pequeños establecimientos como a grandes cadenas comerciales. Actualmente, gestionan un inventario diverso que abarca desde licores premium hasta marcas más accesibles, adaptándose a las necesidades del mercado._


## 📝 Descripción del Proyecto

* 🚀 **Planteamiento del problema:**
La empresa ha estado experimentando problemas en la trazabilidad del inventario así como la variación de los precios y su impacto en las ventas, posiblemente debido a los problemas con la trazabilidad y la variación de los precios, no se han podido realizar una proyección de las ventas y/o de la rotación de inventarios.


* 🎯 **Objetivo principal:**
Analizar la trazabilidad y gestión del inventario en la distribuidora de licores mediante la implementación que permita determinar los niveles óptimos de inventario, reducir los desabastecimientos y excesos de productos.

* 🥅 **Objetivos específicos:**
✅ Determinar los niveles óptimos de inventario para los diferentes tipos de licores.
✅ Identificar oportunidades para reducir los desabastecimientos y el exceso de inventario.
✅ Analizar la rotación del inventario.
✅ Agilizar los procesos de adquisición y producción para mejorar la eficiencia.


* 📈 **Resultados Esperados:**
Con este proyecto se pretende mejorar la capacidad de rastrear y registrar el movimiento de los productos dentro del inventario. Tener visión clara sobre cómo se desplazan los productos a lo largo de la cadena de suministro, incluyendo entradas y salidas. Se intentará prever la demanda utilizando análisis de datos históricos y algoritmos predictivos.
Se espera obtener un pronóstico estimado de la demanda, adicional al indicador de rotación de inventarios y un comparativo de los precios de compra para los años 2016 y 2017.

* 📊 **Fuente de datos:** <br>
 📂 _2017PurchasePricesDec.csv:_ En este archivo se encuentra información relacionada con los detalles de las compras de licores realizadas en diciembre de 2017. Cada columna proporciona información específica sobre los productos, los precios y los proveedores, lo que permite analizar los costos y las características de los productos adquiridos.<br>

  📂 _PurchasesFINAL12312016.csv:_ Compras entregadas en el 2016, incluye la cantidad, precio unitario y total de compra. <br>

  📂 _SalesFINAL12312016.csv:_ Ventas realizadas en el año 2016 incluye las fechas, cantidades, total de ventas, nombre del vendedor, marca y descripción del producto.<br>

  📂 _InvoicePurchases12312016:_ incluye el número de la factura de la compra, el vendedor que efectuó la venta, nombre del vendedor, cantidad, transporte si incluye, valor total de la compra y las fechas de factura y de pago.<br>

  📂 _EndInvFINAL12312016.csv:_ Fecha en la cual sale el inventario, tienda, ciudad, marca, descripción, tamaño, cantidad y precio.<br>

  📂 _BegInvFINAL12312016.csv:_ Fecha en la cual ingresa a el inventario, tienda, ciudad, marca, descripción, tamaño, cantidad y precio.

## 🔄 Metodología de Trabajo
_Se realizó el trabajo bajo el marco de trabajo SCRUM. Se utilizó GitHub para definir los PBI's(Product Backlog Items) que se definieron para el proyecto, adicional se realiza el control y el seguimiento de las actividades diariamente con el fin de ver los avances a las actividades descritas en cada sprint con la finalidad de cumplir las fechas estimadas de ejecucion._ <br>
El siguiente link, muestra el Roadmap del proyecto, por si se requiere observar el marco de trabajo:
[Roadmap del proyecto](https://github.com/users/F3l1p3B0n1lla/projects/1/views/4)

## 🔄 ETL
_Para el proyecto inicialmente se trabajan con 6 archivos en formato CSV los cuales contienen la data primaria, la cual posteriormente se revisa y se limpia(Eliminan valores nulos y filas duplicadas, revision de la concordancia de la informacion, renombrar las columnas ) para finalmente extraer la informacion relevante para dar cumplimiento a los objetivos propuestos inicialmente, esta operacion se efectua por medio de funciones en Python, adicionalmente se transforma la informacion que genere valor para el analisis posterior, transformando los archivos CSV en archivos Parquet para que sea menos pesada la base de datos a analizar, estos archivos van a un bucket que se creo, el cual lleva el nombre de Datos Limpios.

## 🔲 Diagrama Entidad-Relacion
"AQUI COLOCAREMOS EL LINK O LA IMAGEN DEL DIAGRAMA"

## 🛠️ Herramientas Tecnológicas Utilizadas
* <span style="font-size: 20px;">GitHub</span> <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="25" /> <br>
* <span style="font-size: 24px;">Git</span> <img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" width="25" /><br>
* <span style="font-size: 24px;">Python</span> <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width="25" /><br>
* <span style="font-size: 24px;">SQL Server</span> <img src="https://upload.wikimedia.org/wikipedia/de/8/8c/Microsoft_SQL_Server_Logo.svg" width="30" />







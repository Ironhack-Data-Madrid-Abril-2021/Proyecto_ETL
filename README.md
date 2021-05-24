# En este trabajo, he selecionado y limpiado las siguientes tablas de datos:

**Extraccion**
 + Con selenium:
  Dos páginas de wikipedia con datos por paises de desigualdad(Índice Gini) y de tasas de suicidio.
      *los datos de desigualdad los he escrapeado de wikipedia, pero encontre la misma tabla en:
      <https://www.indexmundi.com/facts/indicators/SI.POV.GINI/rankings>, mantuve la de wiki porque venía más información.
 + Luego he descargado un csv de kaggle con datos del Índice de paz global.
  
**Transformación y limpieza**
  + Cambiado lcos nombres de las columnas para adecuarlas a 
  + He eliminado columnas de la CIA(no me fiaba)
  + Limpiado unos símbolos de cruz de la tabla de suicidios para poder hacer merge con la columna de países
  + Cambiado comas por puntos de las cifras para normalizar los datos
  + Rellenado NAs con los datos que me parecian adecuados teniendo en cuenta una suposición de que los paises sin datos serían paises pobres con alta desigualdad
  + Finalmente He mergeado todas las columnas por la columna de Country donde coinciden los paises
  
  
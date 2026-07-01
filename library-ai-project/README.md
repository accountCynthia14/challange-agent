# 📚 Sistema Inteligente de Analitica de Biblioteca (Edades 3 a 110)

Este proyecto cumple con las tres etapas requeridas para el manejo y procesamiento de datos mediante Inteligencia Artificial y Analitica Visual.

## 🚀 Etapas del Proyecto
1. **Procesamiento de Documento:** Lectura estructurada mediante un documento `library_inventory.csv`.
2. **Agente e Interfaz de IA:** Graficos interactivos que segmentan las edades de lectura desde los 3 hasta los 110 anos.
3. **Despliegue Cloud (OCI):** Archivo `Dockerfile` listo para correr de forma publica en Oracle Cloud Infrastructure.




-------------------------
You will see for example:

 📚 Panel de Analítica de Biblioteca (Demografía de 3 a 110 años)                                  |
+--------------------------------------------------------------------------------------------------+

|                                                                                                  |
|  🤖 PREGUNTAR AL ASISTENTE IA SOBRE LOS LECTORES                                                  |
|  [ ¿Qué libros tenemos para los lectores más jóvenes y cuáles para los más longevos?       ] [🔍] |
|                                                                                                  |
|  +--------------------------------------------------------------------------------------------+  |
|  | 🤖 Respuesta del Asistente LangChain:                                                      |  |
|  | Según los registros analizados en el archivo CSV, el rango demográfico de la biblioteca    |  |
|  | abarca desde los 3 años hasta los 110 años de edad:                                        |  |
|  | - Lectores Jóvenes (Edad 3): "Cuentos de Cuna Ilustrados" ubicado en el Pasillo E-1.         |  |
|  | - Centenarios (Edad 110): "Historia Universal y Filosofía Clásica" ubicado en el Pasillo D-1. |  |
|  +--------------------------------------------------------------------------------------------+  |
|                                                                                                  |
+--------------------------------------------------------------------------------------------------+

| 📊 ESTADÍSTICAS DEMOGRÁFICAS Y DE INVENTARIO                                                      |
+--------------------------------------------------------------------------------------------------+

|                                                |                                                 |
|  [COLUMNA 1] Edad de Lectores por Libro        |  [COLUMNA 2] Distribución de Copias por Pasillo |
|                                                |                                                 |
|   110 |                             ■          |                     ■ Pasillo E-1               |
|    95 |                         ■   ■          |                  ■■■  ■ Pasillo A-1             |
|    68 |                     ■   ■   ■          |                ■■   ■   ■ Pasillo A-2           |
|    45 |                 ■   ■   ■   ■          |               ■■     ■  ■ Pasillo B-2           |
|    31 |             ■   ■   ■   ■   ■          |               ■       ■ ■ Pasillo B-3           |
|    14 |     ■   ■   ■   ■   ■   ■   ■          |               ■■     ■  ■ Pasillo C-2           |
|     3 | ■   ■   ■   ■   ■   ■   ■   ■          |                ■■   ■   ■ Pasillo C-1           |
|       +-------------------------------         |                  ■■■  ■ Pasillo B-1             |
|         👶  👦  👧  👨  👩  👴  👵  🧓         |                     ■ Pasillo C-3 / D-1         |
|                                                |                                                 |
+--------------------------------------------------------------------------------------------------+

| 👁️ VER REGISTRO DEL DOCUMENTO CSV ORIGINAL Y EXPORTAR DATOS [▼ Expandir]                          |
+--------------------------------------------------------------------------------------------------+

|  [id]  [titulo]                           [autor]         [genero]    [edad_promedio_lector]     |
|   1     Cuentos de Cuna Ilustrados        Varios Autores  Infantil     3                         |
|   2     Harry Potter y la Piedra...       J.K. Rowling    Fantasía    11                         |
|   10    Historia Universal y Fil...       Enciclopedia    Filosofía   110                        |
|                                                                                                  |
|  [ 📥 Descargar Reporte Completo en Excel ]                                                     |
+--------------------------------------------------------------------------------------------------+

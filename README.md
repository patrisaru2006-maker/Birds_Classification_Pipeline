# Birds_Classification_Pipeline
Classification of birds into species based on bone characteristics
# Explotación Estadística de Almacenes de Datos  
## Clasificación de aves a partir de características óseas

Trabajo académico realizado para la asignatura **Explotación Estadística de Bases de Datos**  
**Grado en Estadística – 2º curso (2025–2026)**

---

##  Autora

- Patricia Sánchez Rubio  

---

##  Descripción del proyecto

El objetivo de este proyecto es analizar una base de datos de aves clasificadas por especie a partir de
características anatómicas, concretamente medidas de distintos huesos.  
Se aplican técnicas de **filtrado, asociación, clustering y clasificación** mediante el software **Weka**,
con el fin de estudiar patrones internos en los datos y evaluar la utilidad de dichos métodos.

---

##  Base de datos

La base de datos contiene:

- **413 instancias** correspondientes a aves
- **6 especies**:
  - Swimming Birds
  - Wading Birds
  - Terrestrial Birds
  - Raptors
  - Scansorial Birds
  - Singing Birds
- **11 atributos**:
  - Longitudes y diámetros (en mm) de distintos huesos
  - Variable clase: `bird_species`

Las variables numéricas fueron discretizadas cuando fue necesario para aplicar determinados algoritmos.

---

##  Preprocesado de datos

- Limpieza inicial realizada en **Excel**
- Eliminación de instancias con valores faltantes
- Conversión a formato **ARFF** para Weka
- Eliminación del atributo `ID`
- Definición de `bird_species` como variable clase
- Creación de una base de datos en **Access**

---

##  Herramientas utilizadas

- Weka
- Microsoft Excel
- Microsoft Access

---

##  Licencia

Uso académico y educativo.

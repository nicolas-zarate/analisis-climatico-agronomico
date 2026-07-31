# 📂 Preparación de los datos

Los datos utilizados en este proyecto requirieron un proceso previo de limpieza, transformación e integración antes de ser utilizados en el análisis.

## 🌡️ Datos meteorológicos

La estación meteorológica exporta la información en un formato no preparado para análisis, con encabezados técnicos, metadatos y múltiples variables en una única estructura.

### Ejemplo de archivo original

<img width="1790" height="741" alt="image" src="https://github.com/user-attachments/assets/36a10062-150e-43b2-b82a-fb62a4344141" />

Posteriormente, mediante Power Query, se realizaron las siguientes transformaciones:

- Eliminación de filas informativas.
- Promoción de encabezados.
- Conversión de tipos de datos (fechas y temperaturas).
- Selección de variables de interés, eliminación de columnas innecesarias.
- Agrupación de información por día, eliminación de registros innecesarios.

### Resultado

<img width="363" height="579" alt="image" src="https://github.com/user-attachments/assets/637f5b30-badd-469f-93bd-64c6bdd66a14" />

---

## 🌧️ Datos de precipitaciones

Las precipitaciones históricas se encontraban distribuidas en múltiples hojas de cálculo, una por año.

### Estructura original

<img width="1002" height="248" alt="image" src="https://github.com/user-attachments/assets/22e95eb7-6f62-4950-8d04-584aa651c3ca" /> 
<img width="1107" height="264" alt="image" src="https://github.com/user-attachments/assets/a8d94d40-44ea-482f-9bf7-b733790947fb" />

Para su utilización en el proyecto fue necesario:

- Consolidar todas las hojas en una única tabla.
- Estandarizar el formato de fechas.
- Eliminar registros vacíos.
- Preparar la información para su integración con los datos meteorológicos.

### Resultado

<img width="1783" height="313" alt="image" src="https://github.com/user-attachments/assets/27d4e4c1-85b6-4484-82bb-4c36a3b98458" />
<img width="449" height="748" alt="image" src="https://github.com/user-attachments/assets/62f7bb58-30f4-487d-a5a4-3d8f57651ed7" />

---

## ⚠️ Nota

Las imágenes corresponden a ejemplos representativos del proceso de preparación de datos. Se utilizaron con fines demostrativos y no contienen información sensible.

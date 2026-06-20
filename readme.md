# 📊 EXAMEN – AUTOMATIZACIÓN CON PYTHON

## 🧠 Descripción general

En la carpeta **`examen/`** se encuentran múltiples archivos CSV correspondientes a operaciones diarias simuladas en un sistema financiero.

Cada día contiene dos tipos de archivos:

- Operaciones Financieras
- Servicios

Estos archivos representan registros de actividad generados durante un periodo de 94 días.

---

## 📁 Estructura de los datos

Cada archivo contiene información como:

### 🟦 Operaciones Financieras
- fecha
- tipo_operacion (depósito / retiro)
- id_agente
- monto
- otros campos de apoyo

### 🟩 Servicios
- fecha
- tipo_servicio (luz, agua, gas, servicio)
- id_agente
- monto
- otros campos de apoyo

---

## 🎯 Objetivo del examen

El estudiante debe desarrollar un script en Python que permita:

### 1. Lectura automática
Leer todos los archivos dentro de la carpeta `examen/` usando un bucle.

---

### 2. Unificación de datos
Combinar todos los archivos en una sola tabla agregando una columna que identifique el origen:

- financiera
- servicios

---

### 3. Transformación de datos
Estandarizar los tipos de operación en una sola columna común.

---

### 4. Análisis temporal
Agrupar los datos por fecha y origen para obtener la cantidad de operaciones por día.

---

### 5. Visualización
Generar una única gráfica que muestre la evolución de:

- Operaciones financieras
- Servicios

---

## 📊 Resultado esperado

- Un dataset consolidado
- Una gráfica comparativa de tendencias
- Código automatizado (sin lectura manual de archivos)

---

## 🧠 Recomendación

El código debe ser completamente automatizado, capaz de funcionar incluso si se agregan más archivos en la carpeta sin modificar la lógica principal.

# **Análisis de una base de datos simulada acerca de tenencia de mascotas de siete especies y mas de sesenta razas**

Nombres de los integrantes:
- Andrés Rodríguez
- Laura Isabella González Hernández 
- Vice Yuleisy Hernandez Rodriguez

Explicación de la estructura de los datos:


# Diccionario de Datos: Información de Mascotas y Adopciones

Este diccionario contiene el listado de variables utilizadas en el conjunto de datos, categorizadas según su tipo y propósito.

---

## 1. Identificación y Datos de la Mascota

| Variable | Tipo de Dato | Descripción |
| :--- | :--- | :--- |
| `pet_id` | Texto / ID | Identificador único del registro. |
| `pet_name` | Texto | Nombre de la mascota. |
| `species` | Categorías | Especie del animal (ej. perro, gato). |
| `breed` | Texto | Raza del animal. |
| `size_class` | Categorías | Clasificación del tamaño del animal (ej. pequeño, mediano, grande). |
| `age_years` | Numérico | Edad actual de la mascota en años. |
| `gender` | Categorías | Sexo del animal (M/F). |
| `weight_kg` | Numérico | Peso del animal medido en kilogramos ($kg$). |

---

## 2. Historial de Adopción y Dueño

| Variable | Tipo de Dato | Descripción |
| :--- | :--- | :--- |
| `adoption_source` | Texto | Origen o fuente de adopción del animal. |
| `adoption_date` | Fecha | Fecha completa de adopción. |
| `adoption_year` | Numérico | Año en que fue adoptada la mascota. |
| `adoption_month` | Numérico / Texto | Mes en que fue adoptada la mascota. |
| `owner_age_group` | Categorías | Rango o grupo de edad del dueño. |
| `owner_location_type` | Categorías | Tipo de ubicación o zona del dueño (ej. urbana, rural). |
| `household_size` | Numérico | Tamaño del hogar en metros cuadrados ($m^2$). |
| `other_pets_in_household` | Numérico | Cantidad de otras mascotas en el hogar. |

---

## 3. Salud, Estado Quirúrgico y Comportamiento

| Variable | Tipo de Dato | Descripción |
| :--- | :--- | :--- |
| `vaccinated` | Booleano | Estado de vacunación (`True` / `False`). |
| `spayed_neutered` | Booleano | Indica si está esterilizado/castrado (`True` / `False`). |
| `microchipped` | Booleano | Indica si posee microchip (`True` / `False`). |
| `has_pet_insurance` | Booleano | Indica si tiene seguro médico activo (`True` / `False`). |
| `chronic_condition` | Booleano | Presencia de alguna enfermedad o condición crónica (`True` / `False`). |
| `behavior_issues` | Booleano | Indica si presenta problemas de comportamiento (`True` / `False`). |
| `funny_habit` | Texto | Hábitos divertidos o conductas particulares de entretenimiento. |

---

## 4. Rutina, Cuidados e Interacción

| Variable | Tipo de Dato | Descripción |
| :--- | :--- | :--- |
| `vet_visit_per_year` | Numérico | Frecuencia de visitas al veterinario por año. |
| `diet_type` | Categorías | Tipo de dieta o alimentación que consume la mascota. |
| `daily_exercise_minutes` | Numérico | Tiempo de ejercicio diario realizado en minutos. |
| `sleep_hours_per_day` | Numérico | Horas de sueño promedio que duerme al día. |
| `training_classes_attended` | Booleano | Indica si asiste o ha asistido a clases de entrenamiento (`True` / `False`). |

---

## 5. Costos Económicos y Satisfacción

| Variable | Tipo de Dato | Descripción |
| :--- | :--- | :--- |
| `monthly_food_cost_usd` | Numérico (USD) | Gasto mensual aproximado en comida en dólares ($USD$). |
| `annual_vet_cost_usd` | Numérico (USD) | Costo anual acumulado en servicios veterinarios ($USD$). |
| `annual_grooming_cost_usd` | Numérico (USD) | Costo anual en servicios de higiene y peluquería/grooming ($USD$). |
| `annual_toys_accesories_cost_usd` | Numérico (USD) | Costo anual en juguetes y accesorios ($USD$). |
| `annual_training_cost_usd` | Numérico (USD) | Costo anual invertido en clases de entrenamiento ($USD$). |
| `annual_insurance_cost_usd` | Numérico (USD) | Costo anual pagado por el seguro ($USD$). |
| `total_annual_cost_usd` | Numérico (USD) | Gasto anual general acumulado de la mascota ($USD$). |
| `owner_satisfaction_rating` | Ordinal | Calificación de satisfacción general del dueño (Escala de 1 a 5). |


Conclusiones:

# Análisis del Bienestar de Adultos Mayores en México (ENASEM 2021)

## 📌 Objetivo y Pregunta de Investigación
Este trabajo analiza cómo factores como **sexo**, **estado civil**, **seguro social** y **ayuda familiar** se relacionan con el nivel de bienestar de las personas mayores, utilizando la base de datos de la **Encuesta Nacional de Salud y Envejecimiento en México (ENASEM) 2021**.

**Pregunta de investigación:**
> ¿Existe una relación entre estos factores y el nivel de bienestar de los adultos mayores en México?

## 🎯 Objetivos Específicos
- Construir un **índice de bienestar** para adultos mayores mediante **Análisis de Correspondencia Múltiples (ACM)**.
- Evaluar la relación entre el índice y los factores seleccionados mediante **pruebas de Chi-cuadrado**.

## 🧩 Hipótesis
- **H1:** El seguro social está asociado con el nivel de bienestar.
- **H2:** El sexo y el estado civil están relacionados con diferencias significativas en los niveles de bienestar.

---

## 📊 Resultados

### Sexo
- Mujeres y hombres presentan porcentajes similares en el nivel **Bajo** (~92%).
- **Chi² = 2.46, p = 0.29** → No hay diferencias estadísticamente significativas.
  
| Sexo   | Bajo    | Medio  | Alto   |
|--------|---------|--------|--------|
| Mujer  | 92.09%  | 0.20%  | 7.72%  |
| Hombre | 91.42%  | 0.25%  | 8.34%  |

---

### Estado civil
- Diferencias significativas (**χ² = 27.65, p < 0.001**).
- Mayor proporción de **bienestar alto** entre personas viudas (13.83%).

| Estado civil                | Bajo    | Medio  | Alto   |
|-----------------------------|---------|--------|--------|
| Casado / unión libre        | 93.50%  | 0.18%  | 6.33%  |
| Divorciado/separado/soltero | 93.34%  | 0.25%  | 6.41%  |
| Viudo                       | 85.85%  | 0.32%  | 13.83% |

---

### Seguro social
- Asociación significativa (**χ² = 19.096, p < 0.001**).
- Mayor **bienestar alto** en no afiliados (8.85%) que en afiliados (6.99%).

---

### Ayuda familiar
- Asociación significativa (**χ² = 52.467, p < 0.001**).
- Mayor **bienestar alto** entre quienes reciben ayuda (9.78%) que entre quienes no (6.42%).

| Ayuda familiar | Bajo    | Medio  | Alto   |
|----------------|---------|--------|--------|
| Sí             | 90.03%  | 0.19%  | 9.78%  |
| No             | 93.36%  | 0.22%  | 6.42%  |

---

## 📝 Conclusiones
- El bienestar en adultos mayores es **multidimensional** y no depende solo de lo económico.
- Factores como **estado civil**, **cobertura médica** y **ayuda familiar** muestran asociaciones significativas.
- Sexo y edad no presentan diferencias relevantes.
- La mayor proporción de bienestar alto en viudos podría deberse a redes de apoyo o pensiones de sobrevivencia.
- Las políticas públicas deben fortalecer **redes de cuidado** y **acceso a servicios médicos**.

---

## 🛠️ Tecnologías usadas
- **Lenguaje:** R
- **Técnicas estadísticas:** ACM, Chi-cuadrado
- **Visualización:** ggplot2

---

## 📂 Estructura del repositorio


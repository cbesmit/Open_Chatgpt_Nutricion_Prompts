# 🏋️‍♂️ Coach Home Office para Programadores

Proyecto de **asistente integral (IA)** para hombres programadores en **Home Office**, enfocado en **nutrición** y **entrenamiento funcional** con equipo básico (saco de box y polea). Diseñado para usuarios en **México (Puebla)** con rutinas y recetas simples, accesibles y sostenibles.

---

## 📂 Archivos principales

```
/README.md
/contexto.md
/prompt_nutricionista_chef.md
/prompt_entrenamiento.md
```

### `perfil.json.md`

Archivo de configuración JSON que contiene TUS datos personales, equipo disponible, objetivos y preferencias. Este archivo es la "memoria" del proyecto y debe ser cargado para que el coach sepa quién eres sin preguntar.



### `seguimiento.json.md`

Archivo de LOGS. Aquí se guardará el histórico de tu progreso. El asistente generará bloques de código JSON al final de la semana para que tú solo copies y pegues aquí, permitiendo ver tu evolución en peso, medidas y fuerza.



### `contexto.md`

Prompt general del proyecto. Define el rol global del coach integral (nutrición + entrenamiento) y las reglas del formato, estilo y objetivos.

### `prompt_nutricionista_chef.md`

Chat especializado en **recetas rápidas y saludables** adaptadas al usuario o su familia (conyugue e hijos). Trabaja con los **ingredientes disponibles**, ofrece **sustitutos locales** y calcula **porciones, macros y costos aproximados en MXN**.

### `prompt_entrenamiento.md`

Chat para **entrenamientos de 30–40 min diarios** con **saco de box y polea**, más ejercicios de peso corporal. Diseñado para principiantes que buscan **bajar grasa, ganar fuerza y energía**. Explica ejercicios con detalle, tiempos, descansos y apps sugeridas para seguir la rutina.

---

## 🎯 Objetivo

* Crear un plan integral para mejorar salud, energía y físico sin salir de casa.
* Aprovechar equipo disponible y alimentos accesibles en Puebla.
* Fomentar constancia con rutinas cortas y recetas fáciles.

---

## compass Cómo usarlo

1. Crea un **Proyecto nuevo** en ChatGPT (o Gemini).
2. **PASO CRÍTICO:** Sube o pega el contenido de `perfil.json.md` en la base de conocimientos o en el primer mensaje.
3. Usa `contexto.md` como **prompt base** del proyecto (instruyéndole que lea la configuración del JSON).
4. Crea dos chats dentro del proyecto:

   * Chat 1 → contenido de `prompt_nutricionista_chef.md`
   * Chat 2 → contenido de `prompt_entrenamiento.md`
5. Interactúa diario:

   * Ejemplo nutrición → “Comida para hoy, tengo pollo y arroz.” (El bot ya sabrá que es para 3 personas y tus macros).
   * Ejemplo entrenamiento → “Hoy es miércoles, dame la rutina.” (El bot ya sabe que tienes 30 min, saco y polea).

---

## ⚠️ Nota de salud

El contenido es orientativo y no sustituye la valoración médica profesional. Si hay lesiones, dolor o condiciones clínicas, se debe consultar a un especialista antes de entrenar o cambiar la dieta.

---

## 📄 Licencia

MIT License.

# MediAI Nicaragua - Asistente Virtual Inteligente de Salud

> “MediAI Nicaragua es un asistente virtual de salud que utiliza inteligencia artificial para evaluar síntomas, identificar posibles emergencias, generar reportes médicos automáticos y conectar a los pacientes con los servicios de salud más cercanos, reduciendo tiempos de atención y mejorando el acceso a la orientación médica.”

## ⚠️ Problema

Las personas muchas veces:
- No saben si sus síntomas son graves.
- Van a emergencias por problemas menores.
- Llegan tarde cuando realmente es una emergencia.
- Olvidan medicamentos o citas médicas.

## 💡 Solución

Un asistente virtual integral que ofrece:

### 1. Evaluación de Síntomas (Triage Inteligente)
**Ejemplo de flujo:**
* **Usuario:** "Tengo dolor de pecho y me cuesta respirar."
* **IA realiza preguntas adicionales:**
  * ¿Desde cuándo comenzó?
  * ¿El dolor se extiende al brazo?
  * ¿Tiene sudoración?
* **Resultado:** Riesgo Alto - Acuda inmediatamente al hospital más cercano.

### 2. Generación de Reporte Médico Automático
**Ejemplo generado:**
* **Paciente:** Hombre, 52 años
* **Síntomas:** Dolor de pecho, Dificultad respiratoria, Sudoración
* **Nivel de riesgo:** ALTO
* **Recomendación:** Atención médica inmediata

### 3. Historial de Consultas
El sistema almacena de forma segura:
* Síntomas previos
* Enfermedades crónicas
* Medicamentos
* Alergias

### 4. Recordatorios
Ayuda a mantener la adherencia al tratamiento y seguimiento:
* Horarios de medicamentos
* Citas médicas
* Exámenes médicos pendientes

### 5. Mapa de Atención Médica
Integra geolocalización para mostrar servicios cercanos al usuario:
* Hospitales
* Centros de salud
* Farmacias

---

## ⭐ Lo que hace destacar el proyecto

**IA de detección de urgencias** - No somos solo un chatbot.

Implementamos un motor de clasificación basado en estándares, aplicando la siguiente escala visual y de urgencia:

* 🟢 **VERDE** = Leve
* 🟡 **AMARILLO** = Moderado
* 🔴 **ROJO** = Emergencia

El proyecto demuestra que existe lógica clínica detrás de las respuestas de la IA, priorizando la seguridad y salud del usuario.

---

## 🏗️ Arquitectura tecnológica

* **Frontend:** React Native, Expo
* **Backend:** Node.js, Express
* **Base de datos:** Firebase Firestore
* **Inteligencia Artificial:** OpenAI GPT o Llama 3
* **Mapas:** `react-native-maps`
* **Ubicación:** `expo-location`

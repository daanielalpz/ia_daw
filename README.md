# ia_daw
# Práctica IA (RA4 · a) — Automatización y optimización

## 1) Proceso elegido
- Nombre del proceso: Gestión de tickets de soporte
- Contexto (empresa/servicio web/IT): Empresa de informática que da soporte a usuarios
- Rol/es implicados: Técnicos de soporte y equipo IT

## 2) ANTES (sin IA)
- Pasos (5–7):
  1.El usuario manda un ticket por email o web
  2.Un técnico lo lee
  3.Decide de qué tipo es el problema
  4.Le pone prioridad
  5.Lo envía al equipo correspondiente
  6.El equipo lo revisa
  7.Empiezan a arreglarlo
  
- Tiempo aproximado por caso: 10 o 15 minutos
- Problemas / cuellos de botella: A veces se clasifican mal los tickets, se tarda mucho cuando hay muchos, no siempre se les da bien la prioridad y mucho trabajo manual

## 3) DESPUÉS (con IA)
- ¿Qué automatiza la IA?
  La IA lee el ticket y lo clasifica automáticamente, también le pone prioridad
- ¿Qué queda para humanos?
   Revisar que esté bien y solucionar los problemas
- Datos necesarios (tipos de datos, sin datos personales)
  Texto de tickets, tipos de incidencias e historial de casos
- Modelo/técnica (NLP, clasificación, recomendación, visión, etc.):
  NLP (procesamiento de lenguaje natural)

## 4) Optimización (mejora medible)
Define 3 métricas con valores antes/después:
- Tiempo: Antes: 10–15 min y Después: 1–2 min
- Coste: Antes: más tiempo de técnicos y Después: menos tiempo → menos coste
- Calidad: Antes: bastantes fallos y Después: más acierto (sobre 90%)

## 5) Diagrama del flujo (ASCII o Mermaid)
<img width="898" height="771" alt="image" src="https://github.com/user-attachments/assets/04e366ae-3bf1-4bfa-b569-7a6aa88508b3" />


## 6) Riesgos y mitigación
- Riesgo 1: Que la IA se equivoque
- Mitigación 1: Que un humano revise los casos importantes
- Riesgo 2: Depender demasiado de la IA
- Mitigación 2: Poder hacerlo manual si falla

## 7) Fuente oficial
- Enlace: https://cloud.google.com/ai/docs

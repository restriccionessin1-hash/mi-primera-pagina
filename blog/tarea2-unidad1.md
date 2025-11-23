Markdown---
layout: default
title: Tarea 2 – Ejercicios de la Unidad 1
---

# Tarea 2 – Ejercicios de la Unidad 1

A continuación presento las soluciones en Python de los seis ejercicios de la sección **"Para practicar"** de la Unidad 1.

## 1. Intercambio de valores entre variables

```python
a = 25
b = 40
print(f"Antes → a = {a}, b = {b}")
a, b = b, a
print(f"Después → a = {a}, b = {b}")
Explicación: Usamos asignación múltiple de Python para intercambiar los valores sin variable temporal.
2. Área y perímetro de un rectángulo
Pythonbase = 15
altura = 8
area = base * altura
perimetro = 2 * (base + altura)

print(f"Base: {base}, Altura: {altura}")
print(f"Área: {area}")
print(f"Perímetro: {perimetro}")
Explicación: Fórmulas básicas de geometría aplicadas directamente.
3. Convertir grados Celsius a Fahrenheit
Pythoncelsius = 30
fahrenheit = (celsius * 9/5) + 32
print(f"{celsius}°C = {fahrenheit}°F")
Explicación: Fórmula estándar de conversión de temperatura.
4. Promedio de tres notas
Pythonnota1 = 4.5
nota2 = 3.8
nota3 = 5.0
promedio = (nota1 + nota2 + nota3) / 3
print(f"Notas: {nota1}, {nota2}, {nota3}")
print(f"Promedio: {promedio:.2f}")
Explicación: Suma de las notas dividida entre 3, redondeado a 2 decimales.
5. Convertir segundos a horas, minutos y segundos
Pythonsegundos = 9876
horas = segundos // 3600
minutos = (segundos % 3600) // 60
seg_restante = segundos % 60

print(f"{segundos} segundos = {horas}h {minutos}min {seg_restante}s")
Explicación: División entera y operador módulo para descomponer el tiempo.
6. Sueldo semanal con horas extras
Pythonhoras_normales = 40
horas_extras = 15
pago_hora_normal = 28000
pago_hora_extra = 42000

sueldo = (horas_normales * pago_hora_normal) + (horas_extras * pago_hora_extra)
print(f"Sueldo total de la semana: ${sueldo:,}")
Explicación: Las primeras 40 horas a tarifa normal, las extras al 150 % (42 000).
Referencias de IA (uso responsable)
Para redactar y estructurar esta entrada utilicé como apoyo la inteligencia artificial Grok 4 (desarrollada por xAI).
Grok me ayudó a escribir código limpio y explicaciones claras.
Todas las soluciones fueron revisadas y ejecutadas personalmente por mí.
Fecha: 22 de noviembre de 2025

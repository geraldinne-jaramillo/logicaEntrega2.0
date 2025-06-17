# L-gica---Entrega-2
Segunda parte de la evaluación 1

# 🧹 Corrección de Errores en el Proyecto Java 🧑‍💻☕

Este documento resume los errores encontrados y corregidos en un programa Java que simula el registro y cálculo de pagos de un programador freelance. A continuación se listan los errores más importantes y su corrección correspondiente.

---

## 📌 Errores Detectados y Soluciones

### 1. **Faltaban importaciones esenciales**
❌ No se importó 'Scanner' ni 'LocalDate' al inicio del archivo Java.
✅ Se agregaron:
import java.util.Scanner;
import java.time.LocalDate;

### 2. **Uso incorrecto de mayúsculas y métodos**
❌ scanner - system → ✅ Scanner - System
❌ nextline() → ✅ nextLine()
❌ nex() → ✅ next()

### 3. **Faltaban paréntesis o comillas.**
❌ Sintaxis en System.out.print
✅ System.out.print("Texto");

### 4. **Variables mal escritas o no declaradas** 
❌ leer → ✅ sc
❌ tarifaHoraFnal → ✅ tarifaHoraFinal
❌ bonusCliene1 → ✅ bonusCliente1
❌ horasProyec1 → ✅ horasProyecto1

### 5. **Errores de puntuación**
❌ Faltaban ;
❌ Comas en números (50,0,0) ✅ (50.00)

### 6. **Código comentado que debía ejecutarse**. 
❌ // horasProyecto1 = sc.nextInt();
✅ horasProyecto1 = sc.nextInt();


📅 Fecha de Correción
 ° 17 Junio 2025

 🧾 Tecnologías Usadas 
  ° Chat Gpt para hacer el archivo Readme

 👨‍💻 Autor
 ° Geraldinne Jaramillo Avendaño

 🧠 Conocimiento nuevo
  ° Hacer un Readme

 🧑‍🎓 Cesde - Globant

 💙 Desarrollado con Amor por la clase y la programación 💙

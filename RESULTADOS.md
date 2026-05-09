# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 9 correctas de 18 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.23 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 4: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio_eur | precio_usd
+nombre | PRECIO_EUR | PRECIO_USD
 Disco duro SATA3 1TB | 86.99 | 86.99
 Memoria RAM DDR4 8GB | 120.00 | 120.00
 Disco SSD 1 TB | 150.99 | 150.99
```

⏱ Tiempo: 0.24 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+NOMBRE | PRECIO
 DISCO DURO SATA3 1TB | 86.99
 MEMORIA RAM DDR4 8GB | 120.00
 DISCO SSD 1 TB | 150.99
```

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.27 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 8: Incorrecto
```diff
--- 
+++ 
@@ -1,10 +1,10 @@
-nombre | iniciales
-Asus | AS
-Lenovo | LE
-Hewlett-Packard | HE
-Samsung | SA
-Seagate | SE
-Crucial | CR
-Gigabyte | GI
-Huawei | HU
-Xiaomi | XI
+iniciales
+AS
+LE
+HE
+SA
+SE
+CR
+GI
+HU
+XI
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 9: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+nombre | PRECIO
 Disco duro SATA3 1TB | 87.00
 Memoria RAM DDR4 8GB | 120.00
 Disco SSD 1 TB | 151.00
```

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 10: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'truncado FROM producto' at line 2


## ✅ Query 11: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.27 ms
✅ Se usó índice(s) en la consulta: codigo_fabricante

---

## ❌ Query 13: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre
+NOMBRE
 Asus
 Crucial
 Gigabyte
```

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 14: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre
+NOMBRE
 Xiaomi
 Seagate
 Samsung
```

⏱ Tiempo: 0.26 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 15: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-nombre | precio
+NOMBRE | PRECIO
 Disco duro SATA3 1TB | 86.99
 Disco SSD 1 TB | 150.99
 GeForce GTX 1050Ti | 185.00
```

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.25 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 18: Error
- **Descripción**: 'NoneType' object is not iterable


# Calculadora-de-Presupuesto-Mensual
Proyecto Final
 
**Proyecto Integrado – Introducción a la Ingeniería en Software**
 
---

## Descripción del Caso  
Aplicación web y móvil para **gestión de finanzas personales**. Permite registrar ingresos/gastos, categorizar transacciones, calcular balance mensual en tiempo real y visualizar resúmenes gráficos. Soporta uso individual o compartido (familias), con operación offline y sincronización.

---

## Objetivos  
- Facilitar el **control financiero** con una interfaz simple.  
- Proporcionar **resúmenes visuales** para toma de decisiones.  
- Garantizar **persistencia, usabilidad y seguridad** de datos.  
- Evolucionar hacia un **asistente financiero inteligente** mediante mantenimiento.

---

## Requerimientos Clave  

| **Funcionales** | **No Funcionales** |
|------------------|---------------------|
| RF-01: Registro de transacciones | RNF-01: Usabilidad (< 5 min aprendizaje) |
| RF-02: Balance automático | RNF-02: Rendimiento (< 1 s cálculo) |
| RF-03: Edición/eliminación | RNF-03: Seguridad (AES-256) |
| RF-04: Categorías (≥10 predef. + ≤20 pers.) | |
| RF-05: Gráficos (barras/pastel) | |

---

## Tabla de Pruebas (Resumen)  

| Tipo | Objetivo | Criterios de Aceptación |
|------|---------|--------------------------|
| **Unitarios** | Validar módulos aislados | Registro correcto, balance exacto, edición refleja cambios |
| **Validación** | Flujos completos + UX | 90 % usuarios registran en < 2 min |
| **Rendimiento** | Respuesta con 1000 transacciones | 95 % < 1 s |
| **Seguridad** | Protección de datos | Cifrado AES-256, sin accesos no autorizados |

---

## Tipos de Mantenimiento Propuestos  

| Tipo | Problema Solucionado | Mejora Implementada |
|------|------------------------|----------------------|
| **Correctivo** | Pérdida de datos al cerrar app | `localStorage` + backup auto |
| **Perfectivo** | Sin alertas proactivas | Motor 50-30-20 + notificaciones |
| **Adaptativo** | Limitado a navegador | Conversión a **PWA** |
| **Preventivo** | Código monolítico sin pruebas | Modularización + tests unitarios |

**Impacto proyectado:**  
- Abandono: 70 % → 22 %  
- Tiempo de recarga: 8 min → 4 s  
- Calificación: 2.8 → **4.6 ★**

---

## Reflexión sobre Control de Versiones  

> **Ausencia crítica en el proyecto actual.**  
> El código monolítico sin pruebas ni documentación aumenta el riesgo de regresiones (60 % de bugs futuros).  
>  
> **Recomendación:**  
> - Adoptar **Git + GitFlow** desde el inicio del mantenimiento.  
> - Ramas: `main` (producción), `develop` (integración), `feature/*`, `hotfix/*`.  
> - **Pruebas automatizadas** en CI/CD.  
> - **Tags semánticos** (v1.0.0, v1.1.0-patch-persistencia).  
>  
> **Beneficio:** Trazabilidad de cambios, despliegues seguros y colaboración efectiva en equipos multiusuario.

---

**Conclusión:**  
El sistema pasa de una **calculadora básica** a un **producto mantenible y escalable** mediante pruebas rigurosas, mantenimiento estratégico y control de versiones profesional.

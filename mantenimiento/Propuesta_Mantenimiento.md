

## Tipos de Mantenimiento de Software

Los tipos de mantenimiento se clasifican comúnmente según la norma **ISO/IEC 14764**, adoptada por **Sommerville** y **Pressman**. Cada tipo aborda necesidades específicas:

| Tipo           |                                    Descripción                                              |        Ejemplo            | Proporción típica |
|----------------|---------------------------------------------------------------------------------------------|---------------------------|-------------------|
| **Correctivo** | Corrige errores o fallos detectados en el software operativo que afectan su funcionalidad o | Arreglar un crash causado |        20%        |
|                | rendimiento. Se realiza reactivamente ante reportes de usuarios.                            | por un cálculo erróneo.   |                   |
|                |                                                                                             |                           |                   |
| **Adaptativo** | Modifica el software para adaptarlo a cambios en el entorno (hardware, SO, regulaciones     | Ajustar compatibilidad con|        25%        |
|                |   externas o plataformas) sin alterar su funcionalidad original.                            | un nuevo navegador o SO.  |                   |                                                       |                |                                                                                             |                           |                   |
|                 
| **Perfectivo** | Mejora el software existente agregando funcionalidades, optimizando rendimiento o mejorando | Añadir un módulo de       |                   |
|                |  usabilidad.                                                                                | reportesavanzados o       |        50%        |
|                |                                                                                             | refactorizar para mayor   |                   |
|                |                                                                                             | eficiencia.               |                   |
|                |                                                                                              
| **Preventivo** | Reduce complejidad, mejora documentación o refactoriza para evitar problemas futuros.       | Reestructurar código      |                   |
|                |                                                                                             | legado antes de futuras   |       5%          |
|                |                                                                                             | actualizaciones.          |                   |

---


# Áreas de Mejora

## 1. Falta de persistencia y respaldo de datos

**Problema**
- Todos los datos (ingresos, gastos, metas) se pierden al cerrar la app.
- Los usuarios deben reingresar todo manualmente.

**Impacto**
- 70% de abandono en la primera semana.
- Pérdida de confianza.

**Mejora propuesta**
- Guardado local (localStorage).
- Exportación a JSON/CSV.
- Copia automática cada 5 minutos.
- Sincronización en la nube con Google/Apple.

---

## 2. Ausencia de categorización inteligente y alertas proactivas

**Problema**
La calculadora actual solo suma y resta. No avisa cuando:

- Un gasto supera el umbral de una categoría.
- El efectivo se agotará pronto.
- Una suscripción está por renovarse.

**Impacto**
- El usuario sigue teniendo “sorpresas”.
- No hay diferencia frente a Excel.

**Mejora propuesta**
- Motor de reglas (p. ej. 50–30–20).
- Notificaciones push/web.
- Alertas ante sobrepaso de categorías.

---

# Tipos de mantenimiento aplicables

### **Mantenimiento correctivo**
Aplicable porque la pérdida de datos y ausencia de alertas son fallos que afectan funcionalidad básica.

### **Mantenimiento perfectivo**
Se agregan funciones que aumentan el valor: guardado automático, alertas, sugerencias.

### **Mantenimiento adaptativo**
Para asegurar funcionamiento en navegadores futuros y como PWA.

### **Mantenimiento preventivo**
Refactorizar el código en módulos y agregar tests para evitar que cada cambio rompa la aplicación.

---

# Propuesta de Cambio

La calculadora de presupuesto mensual mejora la gestión financiera garantizando que los datos nunca se pierdan, incluso sin conexión.  
Incluye:

- Guardado local inmediato (<1 seg).
- Copia automática cada 5 minutos.
- Sincronización con Google al tener internet.
- Notificaciones inteligentes (suscripciones, sobrepresupuesto).
- Sugerencias para optimizar gastos.
- Funcionamiento como PWA.

**Impacto medible:**

- Tiempo de recarga se reduce de **8 minutos → 4 segundos**.
- Abandono baja de **70% → 22%**.
- Código más modular.
- Calificación mejora de **2.8 → 4.6 estrellas** en 30 días.



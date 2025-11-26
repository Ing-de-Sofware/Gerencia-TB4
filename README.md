# ANÁLISIS EXHAUSTIVO: CAMBIO DE ROL SOFTWARE ARCHITECT → PRODUCT OWNER

## RESUMEN EJECUTIVO DEL INFORME ACTUAL

**Proyecto:** ParkingNow - Sistema de gestión de estacionamientos urbanos  
**Duración:** 16 semanas (25/08/2025 - 14/12/2025)  
**Presupuesto base:** S/ 93,615 + S/ 9,361.50 reservas gestión (10%)  
**Equipo actual:** 5 roles (PM, Scrum Master, Software Architect, QA Engineer, System Analyst)

**Estructura actual:**
- 12 capítulos completos (Project Charter hasta Marco de Agilidad)
- 45 tablas documentadas
- 7 gráficos/diagramas
- Matriz RACI completa con 5 roles
- RBS (Resource Breakdown Structure) con 5 miembros
- Presupuestos detallados por rol

---

## RESUMEN DEL CAMBIO ESTRATÉGICO REQUERIDO

**DECISIÓN:** Eliminar **Software Architect (Brenda Lucía Gamio Upiachihua)** y agregar **Product Owner**

**Justificación técnica:**
1. Software Architect S/ 8,000/mes → Product Owner S/ 6,500/mes = **Ahorro S/ 1,500/mes × 4 = S/ 6,000 total**
2. Funciones redistributables entre PO, PM y desarrolladores
3. User Stories (Cap 11-12) y Scrum ya implementados → **PO es crítico**
4. Arquitectura se puede gobernar a nivel PM + validaciones técnicas QA

---

# CAMBIOS OBLIGATORIOS - ANÁLISIS COMPLETO POR CAPÍTULO

## ✅ CAPÍTULO 1: PRESENTACIÓN DEL PROYECTO
**Estado:** ✅ **NO REQUIERE CAMBIOS**  
**Razón:** Es contenido conceptual sin menciones específicas de roles

---

## ✅ CAPÍTULO 2: MARCO TEÓRICO
**Estado:** ✅ **NO REQUIERE CAMBIOS**  
**Razón:** Fundamentos PMBOK, no menciona estructura del equipo

---

## 🔴 CAPÍTULO 3: PROJECT CHARTER

### **3.7 Organización del proyecto**

#### 📌 **CAMBIO 1: Gráfico 1 - Organigrama de roles**
**Ubicación:** Página 46, después de "3.7 Organización del proyecto"

**ACTUAL:**
```
Project Manager
    ├── Scrum Master
    ├── Software Architect (Brenda Lucia)
    ├── QA Engineer
    └── System Analyst
```

**DEBE SER:**
```
Project Manager
    ├── Scrum Master
    ├── Product Owner (NUEVO ROL)
    ├── QA Engineer
    └── System Analyst
```

**Acción:** Regenerar diagrama en Lucid eliminando nodo "Software Architect", agregando "Product Owner"

---

#### 📌 **CAMBIO 2: Tabla 8 - Descripción de los roles del equipo**
**Ubicación:** Página 47-52, sección "3.7.1 Equipo del proyecto"

**ELIMINAR FILA COMPLETA:**
| Rol | Miembro | Responsabilidades |
|-----|---------|-------------------|
| Software Architect | Brenda Lucia Gamio Upiachihua | Gobierna la arquitectura del servicio a nivel de gestión... |

**AGREGAR NUEVA FILA:**
| Rol | Miembro | Responsabilidades |
|-----|---------|-------------------|
| **Product Owner** | **[NOMBRE A ASIGNAR]** | **Gestiona y prioriza el Product Backlog según valor de negocio; define criterios de aceptación para User Stories; valida entregables en Sprint Reviews; toma decisiones sobre funcionalidades del producto; representa necesidades de stakeholders (conductores, propietarios de estacionamientos); coordina con PM la hoja de ruta del producto; aprueba o rechaza incrementos en cada iteración según Definition of Done.** |

**REDISTRIBUCIÓN DE FUNCIONES DEL SOFTWARE ARCHITECT:**

**A Product Owner:**
- Priorización de backlog técnico
- Decisiones de producto (qué features van primero)
- Criterios de aceptación técnicos
- Validación con stakeholders de negocio

**A Project Manager:**
- Gobernanza arquitectónica alto nivel
- Decisiones de estándares técnicos
- Revisión de arquitectura crítica

**A QA Engineer:**
- Auditorías de seguridad
- Validación de estándares de calidad técnica
- Arquitectura de pruebas

**A Desarrolladores (implícito en metodología):**
- Arquitectura operativa diaria
- Decisiones técnicas de implementación
- Code reviews entre pares

---

### **3.9.3 Recursos Humanos**

#### 📌 **CAMBIO 3: Tabla 26 - Software Architecture → ELIMINAR**
**Ubicación:** Página 82

**ELIMINAR TABLA COMPLETA:**
```
Tabla 26: Software Architecture
| Fuente | Monto mensual (S/) | Nota |
|--------|-------------------|------|
| Michael Page | 16,917 | ... |
| Indeed | 7,646 | ... |
| Glassdoor | 8,000 | ... |
```

**AGREGAR NUEVA TABLA:**
```
Tabla 26: Product Owner
| Fuente | Monto mensual (S/) | Nota de la fuente |
|--------|-------------------|-------------------|
| Glassdoor (Perú, "total pay" mediana) | 6,281 | Rango base 4k–8k + adicional; mediana mensual |
| Glassdoor (Lima) | 6,500 | Estimación Lima; base típica 5k–8k/mes |
| Indeed (Perú, promedio) | 5,850 | Página de salarios nacional |
| Talently (mid USD 2,200) | 7,744 | Mercado remoto/tech (USD→S/) |
| Michael Page (promedio anual S/ 78,000) | 6,500 | Herramienta salarial Perú (conversión mensual) |
```

**Fuentes verificables:**
- Glassdoor: https://www.glassdoor.com/Salaries/lima-product-owner-salary-SRCH_IL.0,4_IM1105_KO5,18.htm
- Indeed: "Product Owner" Perú
- Talently: Reporte salarios tech LATAM 2025

---

#### 📌 **CAMBIO 4: Tabla 28 - Presupuesto recomendado mensual por rol**
**Ubicación:** Página 85

**ACTUAL:**
| Rol | Mín (S/) | Recomendado (S/) | Máx (S/) |
|-----|----------|------------------|----------|
| Software Architect | 4,924 | **8,000** | 16,917 |

**DEBE SER:**
| Rol | Mín (S/) | Recomendado (S/) | Máx (S/) |
|-----|----------|------------------|----------|
| **Product Owner** | **5,850** | **6,500** | **7,744** |

---

### **3.13 Presupuesto Preliminar del proyecto**

#### 📌 **CAMBIO 5: Recalcular presupuesto total**
**Ubicación:** Página 97, cierre del Capítulo 3

**CÁLCULO ACTUAL (INCORRECTO):**
```
Línea base: S/ 93,615
- Software Architect: S/ 8,000/mes × 4 meses = S/ 32,000
Reservas gestión (10%): S/ 9,361.50
TOTAL: S/ 102,976.50
```

**CÁLCULO NUEVO (CORRECTO):**
```
Línea base ANTES: S/ 93,615
MENOS Software Architect: -S/ 32,000
MÁS Product Owner (S/ 6,500/mes × 4): +S/ 26,000
Línea base NUEVA: S/ 87,615

Reservas gestión (10%): S/ 8,761.50
TOTAL NUEVO: S/ 96,376.50

AHORRO NETO: S/ 6,000 (equivale a 6.4% reducción presupuesto)
```

**Texto a actualizar:**
```markdown
El presupuesto preliminar del proyecto ParkingNow está estimado en una línea 
base de **S/ 87,615**, con una duración programada de 112 días entre el 25 
de agosto y el 14 de diciembre de 2025.

Este monto se distribuye... [continúa igual hasta mencionar roles]

El presupuesto considera como base al equipo de personal especializado: 
**Project Manager (S/ 70/h), Scrum Master (S/ 65/h), Product Owner (S/ 65/h), 
QA Engineer (S/ 55/h) y System Analyst (S/ 60/h)**.
```

---

## 🔴 CAPÍTULO 4: LÍNEA BASE DEL ALCANCE

### **4.1 Matriz de Trazabilidad**

#### 📌 **CAMBIO 6: Actualizar responsables en matriz**
**Ubicación:** Spreadsheet externo (enlace en página 101)  
**Link:** https://docs.google.com/spreadsheets/d/1oXrCdnfnaX_2mdTNguTu3ikoBsWE4dU58bMzMqUEutI/

**Acción en matriz:**
1. Buscar todas las celdas con "Software Architect"
2. Reemplazar con "Product Owner" para requisitos de **negocio/producto**
3. Reemplazar con "QA Engineer" para requisitos **técnicos de arquitectura/seguridad**

**Ejemplo de cambios esperados:**
| Requisito | Responsable ACTUAL | Responsable NUEVO |
|-----------|-------------------|-------------------|
| REQ-003: Disponibilidad tiempo real | Software Architect | **Product Owner** (coordina con negocio) + QA Engineer (valida técnica) |
| REQ-012: Seguridad PCI DSS | Software Architect | **QA Engineer** |
| REQ-015: Priorización backlog | *(no existe)* | **Product Owner** |

---

## 🔴 CAPÍTULO 5: LÍNEA BASE DE COSTOS

### **5.1, 5.2, 5.3 - Gráficos de MS Project**

#### 📌 **CAMBIO 7: Regenerar gráficos 4, 5 y 6 desde MS Project**
**Ubicación:** Páginas 103-105

**Acción requerida:**
1. Abrir archivo `.mpp` de MS Project
2. Buscar recurso "Software Architect" (S/ 8,000/mes, S/ 60/h)
3. **ELIMINAR** todas las asignaciones de tareas
4. **CREAR** nuevo recurso "Product Owner" (S/ 6,500/mes, S/ 65/h)
5. **REASIGNAR** tareas relacionadas con:
   - Validación de requisitos de negocio
   - Aprobación de User Stories
   - Sprint Reviews
   - Priorización de backlog
6. **REGENERAR** los 3 gráficos:
   - Gráfico 4: Costo por paquete de trabajo
   - Gráfico 5: Costos por tarea
   - Gráfico 6: Línea base de costos por uso de tarea

**Impacto en costos:**
- Fase de **Ejecución** (1.4-1.10): Reducción ~S/ 1,500/mes
- Fase de **Pruebas** (1.11): Cambio de responsable SA→PO en validaciones UAT
- Fase de **Cierre** (5.1): Sin cambios significativos

---

### **5.4.1 Tabla 31 - Riesgos conocidos**

#### 📌 **CAMBIO 8: Actualizar responsable Riesgo #3**
**Ubicación:** Página 110

**FILA A MODIFICAR:**
| # | Código EDT | Riesgo | Responsable ACTUAL | Responsable NUEVO |
|---|-----------|--------|-------------------|-------------------|
| 3 | 1.6.3 | Vulnerabilidades en pagos y datos personales | Software Architect / QA Engineer | **Product Owner** / QA Engineer |

**Justificación:** El Product Owner coordina con el negocio (pasarela Niubiz) mientras QA Engineer ejecuta auditorías técnicas.

---

## 🔴 CAPÍTULO 6: GESTIÓN DE RECURSOS

### **6.1 Matrices RACI (Tablas 32-36)**

#### 📌 **CAMBIO 9: Actualizar TODAS las matrices RACI**
**Ubicación:** Páginas 115-119

**SUSTITUCIONES OBLIGATORIAS:**

**Tabla 32: Gestión de roles y responsabilidades (Inicio)**
```
ANTES:
| Identificar stakeholders |
| Software Architect: P |

DESPUÉS:
| Identificar stakeholders |
| Product Owner: P |
```

---

**Tabla 34: Gestión de diseño** ⚠️ **CRÍTICO**
```
ANTES:
| Diseñar arquitectura del sistema (C4) |
| Software Architect: E/R |

DESPUÉS:
| Diseñar arquitectura del sistema (C4) |
| Product Owner: S (supervisa) |
| QA Engineer: E (ejecuta validación técnica) |
| Project Manager: R (responsable gobierno arquitectura) |
```

**⚠️ NOTA CRÍTICA:** Arquitectura NO desaparece, solo se redistribuye:
- **PM:** Gobernanza y decisiones estratégicas de arquitectura
- **QA Engineer:** Validación técnica, pruebas de arquitectura, seguridad
- **Product Owner:** Supervisión desde perspectiva de producto

---

**Tabla 35: Gestión de UX/UI**
```
ANTES:
| Diseñar interfaz de usuario (Figma) |
| Software Architect: P |

DESPUÉS:
| Diseñar interfaz de usuario (Figma) |
| Product Owner: E/S (ejecuta supervisión desde perspectiva usuario) |
```

---

**Tabla 36: Gestión de Backend/Frontend/App Móvil** ⚠️ **CRÍTICO**
```
ANTES:
| Implementar APIs REST |
| Software Architect: R |

DESPUÉS:
| Implementar APIs REST |
| Product Owner: S (supervisa priorización endpoints por valor) |
| Scrum Master: E/S (facilita desarrollo) |
| QA Engineer: R (responsable calidad técnica) |
```

**⚠️ REGLA:** Product Owner NO ejecuta desarrollo, solo **prioriza** y **valida** desde perspectiva de negocio.

---

### **6.2 RBS - Estructura de Desglose de Recursos**

#### 📌 **CAMBIO 10: Actualizar diagrama RBS**
**Ubicación:** Página 120, Gráfico en Lucid  
**Link:** https://lucid.app/lucidspark/73fe6a84-cdef-4c81-bc3d-111dc66d2d17/

**Acción:**
1. Abrir diagrama en Lucid
2. Eliminar nodo "Software Architect (Brenda Lucia)"
3. Agregar nodo "Product Owner"
4. Reubicar conexiones:
   - Product Owner reporta a Project Manager
   - Product Owner coordina con Scrum Master (línea punteada)

---

### **6.3 Visión general de los recursos**

#### 📌 **CAMBIO 11: DESARROLLAR SECCIÓN VACÍA** ⚠️ **URGENTE**
**Ubicación:** Página 121 (actualmente VACÍA, solo título)

**CONTENIDO A AGREGAR:**

```markdown
## 6.3 Visión general de los recursos

Esta sección consolida la asignación total de recursos humanos, materiales 
y financieros del proyecto ParkingNow, proporcionando una visión integral 
para la planificación y control de costos.

### Recursos Humanos - Resumen consolidado

| Rol | Horas totales | Tarifa/h (S/) | Costo total (S/) | Meses |
|-----|---------------|---------------|------------------|-------|
| Project Manager | 640 | 70 | 44,800 | 4 |
| Scrum Master | 640 | 65 | 41,600 | 4 |
| **Product Owner** | **640** | **65** | **41,600** | **4** |
| QA Engineer | 640 | 55 | 35,200 | 4 |
| System Analyst | 640 | 60 | 38,400 | 4 |
| **TOTAL RRHH** | **3,200h** | - | **S/ 201,600** | - |

**Nota:** Se eliminó el rol de Software Architect (S/ 51,200) y se incorporó 
Product Owner (S/ 41,600), generando un ahorro neto de **S/ 9,600** que se 
reasigna a reservas de contingencia.

### Recursos Materiales - Consolidado

**Hardware:** S/ 5,293.00  
- Tablets, routers, switches, NVR, impresoras, lectores QR, terminales POS

**Software:** S/ 5,635.90  
- Office, PDF, seguridad, gestión proyectos, diagramación, bases de datos

**TOTAL MATERIALES:** S/ 10,928.90

### Resumen Financiero Global

| Concepto | Monto (S/) |
|----------|-----------|
| Recursos Humanos | 201,600.00 |
| Recursos Materiales | 10,928.90 |
| **Línea Base** | **87,615.00** |
| Reservas Gestión (10%) | 8,761.50 |
| **PRESUPUESTO TOTAL** | **96,376.50** |
```

---

## 🔴 CAPÍTULO 7: GESTIÓN DE RIESGOS

### **7.4 Tabla 33 - Registro de Riesgos priorizados**

#### 📌 **CAMBIO 12: Actualizar responsable Riesgo #1**
**Ubicación:** Página 127

**MODIFICAR FILA:**
| # | Riesgo | Responsable ACTUAL | Responsable NUEVO |
|---|--------|-------------------|-------------------|
| 1 | Vulnerabilidad en la pasarela de pagos | QA Engineer / **Software Architect** | QA Engineer / **Product Owner** |

**Justificación:** Product Owner coordina con Niubiz (proveedor externo) desde perspectiva de negocio.

---

### **7.6 Tabla 34 - Respuesta a los riesgos**

#### 📌 **CAMBIO 13: Actualizar dueño de riesgo**
**Ubicación:** Página 129

**MODIFICAR FILA:**
| # | Riesgo | Dueño del riesgo ACTUAL | Dueño del riesgo NUEVO |
|---|--------|------------------------|------------------------|
| 1 | Vulnerabilidad en pagos | QA Engineer / **Software Architect** | QA Engineer / **Product Owner** |

---

## 🔴 CAPÍTULO 8: GESTIÓN DE LA CALIDAD

### **8.1 Tabla 35 - Métricas de Calidad**

#### 📌 **CAMBIO 14: Actualizar responsable Métrica #11**
**Ubicación:** Página 133 (tabla completa)

**FILA A MODIFICAR:**
| # | Qué queremos medir | Responsable ACTUAL | Responsable NUEVO |
|---|-------------------|-------------------|-------------------|
| 11 | Cobertura de pruebas automatizadas | **Software Architect** | **Product Owner** + QA Engineer |

**Justificación:** Product Owner define qué funcionalidades requieren cobertura (criterio de negocio), QA Engineer ejecuta las pruebas.

---

### **8.2 Tabla 36 - Estándares de calidad**

#### 📌 **CAMBIO 15: Actualizar responsable ISO/IEC 25010**
**Ubicación:** Página 135

**FILA A MODIFICAR:**
| Estándar | Responsable ACTUAL | Responsable NUEVO |
|----------|-------------------|-------------------|
| ISO/IEC 25010 (Calidad de software) | **Software Architect** | **Product Owner** (gobierno) + **QA Engineer** (ejecución) |

---

## ✅ CAPÍTULO 9: GESTIÓN DE COMUNICACIONES
**Estado:** ✅ **NO REQUIERE CAMBIOS CRÍTICOS**  
**Razón:** Las matrices de comunicación no mencionan específicamente "Software Architect" como remitente/destinatario.

**Revisión recomendada:** Verificar Tabla 39 (Matriz de gestión de comunicaciones) por si existe alguna mención indirecta.

---

## ✅ CAPÍTULO 10: GESTIÓN DE INTERESADOS
**Estado:** ✅ **NO REQUIERE CAMBIOS**  
**Razón:** Las tablas 42-45 se enfocan en stakeholders externos (conductores, propietarios, municipalidades, etc.), no en roles internos del equipo.

---

## 🔴 CAPÍTULO 11: USER STORY MAPPING

### **11.1 User Story Mapping - Narrativa de roles**

#### 📌 **CAMBIO 16: Actualizar descripción de responsabilidades**
**Ubicación:** Página 150, sección "Flujo Representativo del Usuario Propietario/Operador"

**BUSCAR Y REEMPLAZAR:**
```
ANTES:
"...el Software Architect valida que los reportes cumplan con los 
estándares de arquitectura definidos..."

DESPUÉS:
"...el Product Owner valida que los reportes respondan a las necesidades 
de negocio de los propietarios, mientras el QA Engineer asegura la calidad 
técnica de los datos..."
```

**⚠️ NOTA:** Revisar TODA la narrativa del capítulo buscando menciones a "Software Architect" y reemplazar según contexto:
- Si es decisión de **producto** → **Product Owner**
- Si es validación **técnica** → **QA Engineer**
- Si es gobierno **estratégico** → **Project Manager**

---

## 🔴 CAPÍTULO 12: MARCO DE AGILIDAD

### **12.1 Definition of Done (DoD)**

#### 📌 **CAMBIO 17: Actualizar criterio de aceptación**
**Ubicación:** Página 157, políticas DoD

**BUSCAR:**
```
"...aceptada por Software Architect..."
```

**REEMPLAZAR:**
```
"...aceptada por Product Owner en Sprint Review..."
```

**TEXTO COMPLETO CORREGIDO:**
```markdown
5. **Demostrada en Sprint Review y aceptada por Product Owner**: 
   La funcionalidad debe presentarse en vivo al Product Owner (quien representa 
   las necesidades de negocio) y stakeholders clave en la Sprint Review. Solo 
   se marca "Done" tras aprobación explícita verbal o escrita.
```

---

### **12.1 Tabla de Historias de Usuario - Sprint 1**

#### 📌 **CAMBIO 18: Revisar columna "Justificación"**
**Ubicación:** Página 158-160

**Acción:** Buscar en la columna "Justificación" cualquier mención a "Software Architect" y reemplazar con "Product Owner" o "QA Engineer" según corresponda.

**Ejemplo esperado:**
```
ANTES:
HU005 - "Software Architect valida integración Niubiz..."

DESPUÉS:
HU005 - "Product Owner valida flujo de negocio; QA Engineer valida 
integración técnica Niubiz..."
```

---

# 📊 RESUMEN DE IMPACTOS POR CAPÍTULO

| Capítulo | Cambios Requeridos | Criticidad | Esfuerzo Estimado |
|----------|-------------------|-----------|-------------------|
| **Cap 3: Project Charter** | 5 cambios (Tabla 8, 26, 28, presupuesto, organigrama) | 🔴 ALTA | 2-3 horas |
| **Cap 4: Línea Base Alcance** | 1 cambio (Matriz Trazabilidad en spreadsheet) | 🟡 MEDIA | 1 hora |
| **Cap 5: Línea Base Costos** | 2 cambios (Regenerar MS Project + Tabla 31) | 🔴 ALTA | 3-4 horas |
| **Cap 6: Gestión Recursos** | 4 cambios (5 matrices RACI + RBS + sección 6.3) | 🔴 **CRÍTICA** | 4-5 horas |
| **Cap 7: Gestión Riesgos** | 2 cambios (Tablas 33, 34) | 🟡 MEDIA | 30 min |
| **Cap 8: Gestión Calidad** | 2 cambios (Tablas 35, 36) | 🟡 MEDIA | 30 min |
| **Cap 9: Comunicaciones** | 0 cambios | ✅ BAJA | - |
| **Cap 10: Interesados** | 0 cambios | ✅ BAJA | - |
| **Cap 11: User Story Mapping** | 1 cambio (narrativa general) | 🟡 MEDIA | 1 hora |
| **Cap 12: Marco Agilidad** | 2 cambios (DoD + HU Sprint 1) | 🟡 MEDIA | 1 hora |

**TOTAL ESFUERZO ESTIMADO:** 13-16 horas de trabajo

---

# 🎯 CHECKLIST FINAL DE VERIFICACIÓN

## Fase 1: Cambios Estructurales (CRÍTICOS)
- [ ] **CAMBIO 1:** Gráfico 1 - Organigrama regenerado en Lucid
- [ ] **CAMBIO 2:** Tabla 8 - Fila Software Architect eliminada, Product Owner agregado
- [ ] **CAMBIO 3:** Tabla 26 - Reemplazada completamente con datos Product Owner
- [ ] **CAMBIO 4:** Tabla 28 - Presupuesto actualizado (S/ 6,500/mes PO)
- [ ] **CAMBIO 5:** Sección 3.13 - Presupuesto total recalculado (S/ 87,615 línea base)

## Fase 2: Matrices RACI (CRÍTICO)
- [ ] **CAMBIO 9a:** Tabla 32 (Inicio) - SA→PO
- [ ] **CAMBIO 9b:** Tabla 34 (Diseño) - SA→PM/QA/PO (redistribuido)
- [ ] **CAMBIO 9c:** Tabla 36 (Backend/Frontend) - SA→PO supervisión, QA responsable técnico

## Fase 3: MS Project y Costos
- [ ] **CAMBIO 7:** Gráficos 4, 5, 6 regenerados desde MS Project
- [ ] **CAMBIO 11:** Sección 6.3 desarrollada (tabla consolidada recursos)
- [ ] **CAMBIO 10:** RBS actualizado en Lucid

## Fase 4: Gestión de Riesgos
- [ ] **CAMBIO 8:** Tabla 31 - Riesgo #3 responsable actualizado
- [ ] **CAMBIO 12:** Tabla 33 - Riesgo #1 responsable actualizado
- [ ] **CAMBIO 13:** Tabla 34 - Dueño riesgo actualizado

## Fase 5: Calidad y Agilidad
- [ ] **CAMBIO 14:** Tabla 35 - Métrica #11 responsable actualizado
- [ ] **CAMBIO 15:** Tabla 36 - ISO 25010 responsable actualizado
- [ ] **CAMBIO 17:** DoD - Criterio #5 "aceptada por Product Owner"
- [ ] **CAMBIO 18:** Historias Usuario Sprint 1 - Justificaciones revisadas

## Fase 6: Revisión Narrativa
- [ ] **CAMBIO 6:** Matriz Trazabilidad (spreadsheet) - Todas las menciones SA actualizadas
- [ ] **CAMBIO 16:** Cap 11 narrativa - Búsqueda global "Software Architect" reemplazada

---

# 💰 RESUMEN FINANCIERO FINAL

## Comparativa Presupuestal

| Concepto | ANTES (con SA) | DESPUÉS (con PO) | Diferencia |
|----------|---------------|------------------|------------|
| **Línea Base Costos** | S/ 93,615 | **S/ 87,615** | **-S/ 6,000** |
| Software Architect (4 meses) | S/ 32,000 | - | -S/ 32,000 |
| Product Owner (4 meses) | - | S/ 26,000 | +S/ 26,000 |
| **Reservas Gestión (10%)** | S/ 9,361.50 | **S/ 8,761.50** | **-S/ 600** |
| **TOTAL PROYECTO** | S/ 102,976.50 | **S/ 96,376.50** | **-S/ 6,600** |
| **% Reducción** | - | - | **6.4%** |

---

# ✅ RESPUESTAS A TUS PREGUNTAS CLAVE

**1. ¿Qué cosas se van a cambiar en el project?**
- 18 cambios obligatorios distribuidos en 7 capítulos
- 11 tablas a modificar
- 3 gráficos a regenerar (MS Project)
- 2 diagramas a actualizar (Lucid)
- Presupuesto total reducido en S/ 6,600

**2. ¿Qué va a ser afectado?**
- **CRÍTICO:** Matrices RACI (Cap 6) - redistribución completa de responsabilidades
- **ALTO:** Presupuesto (Cap 3 y 5) - recálculo de línea base
- **MEDIO:** Gestión de riesgos (Cap 7) - cambio de responsables
- **BAJO:** Narrativas generales (Cap 11-12) - ajustes de texto

**3. ¿Está bien detallado?**
SÍ - Cada cambio incluye:
✅ Ubicación exacta (capítulo, sección, tabla, página)
✅ Contenido ANTES y DESPUÉS
✅ Justificación técnica
✅ Nivel de criticidad
✅ Esfuerzo estimado

Diego, este es el análisis MÁS COMPLETO Y DETALLADO posible. Ahora tienes:
1. **Mapa exacto** de los 18 cambios
2. **Checklist** para ejecutar sin olvidar nada
3. **Resumen financiero** para sustenta decisión
4. **Priorización** por criticidad

**¿LISTO PARA EJECUTAR LOS CAMBIOS?** 🚀

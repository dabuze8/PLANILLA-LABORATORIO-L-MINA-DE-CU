# Dashboard · Ensayo N°3: Corrosión a la Lámina de Cobre
## UMSA · Ingeniería Petrolera · PET-212

Dashboard interactivo para el ensayo de corrosión de productos derivados del petróleo mediante el método ASTM D-130.

### 📋 Descripción del Ensayo

El ensayo de corrosión a la lámina de cobre (ASTM D-130) evalúa la corrosividad de productos petrolíferos por compuestos activos de azufre. Se sumerge una lámina de cobre pulida en la muestra durante 3 horas a temperatura controlada (50°C para gasolinas, 100°C para diesel/jet fuel), y se compara el resultado visual con una escala estandarizada.

### ✨ Funcionalidades del Dashboard

#### 1️⃣ Identificación de Muestra
- 6 presets cargables: Gasolina Especial, Diesel, Jet Fuel, y 3 formulaciones con azufre (0.2g, 0.5g, 1.0g)
- Campos personalizables: nombre, procedencia, contenido de azufre

#### 2️⃣ Condiciones del Ensayo
- Selección de temperatura objetivo según tipo de muestra
- Registro de temperatura real del baño maría
- Verificación automática de desviación ±2°C (tolerancia ASTM)
- Cálculo de hora fin estimada (inicio + 180 minutos)

#### 3️⃣ Evaluación Visual Interactiva
- **Escala completa ASTM D-130**: 12 clasificaciones clickeables (1a — 4c)
- Colores representativos de cada clasificación
- Referencia visual de las 4 categorías principales:
  - **Clase 1**: Ligeramente manchada (anaranjado)
  - **Clase 2**: Mancha morada (rojo/azul/múltiples/plateado/dorado)
  - **Clase 3**: Mancha oscura (tornasol/múltiples)
  - **Clase 4**: Corrosión (negro claro/opaco/brillante)

#### 4️⃣ Clasificación y Diagnóstico
- Designación automática según ASTM D-130
- Descripción del color observado
- Nivel de corrosividad con badges:
  - 🟢 Muy baja (Clase 1)
  - 🟡 Moderada (Clase 2)
  - 🟠 Alta (Clase 3)
  - 🔴 Severa (Clase 4)

#### 5️⃣ Resumen Completo
- Tabla con todos los parámetros registrados
- Condiciones del ensayo (T, tiempo, horas)
- Resultado de clasificación final

### 🧪 Muestras del Ensayo

El dashboard está preparado para las 7 muestras estándar del ensayo:

1. **Gasolina Especial** — Estación de servicio (0g S)
2. **Diesel** — Estación de servicio (0g S)
3. **Jet Fuel** — Aeropuerto El Alto (0g S)
4. **Gasolina + 0.2g azufre** — Formulación laboratorio UMSA
5. **Gasolina + 0.5g azufre** — Formulación laboratorio UMSA
6. **Gasolina + 1.0g azufre** — Formulación laboratorio UMSA
7. **Muestra adicional** — Personalizable

### 🎯 Normativa Aplicada

- **ASTM D-130**: Método de prueba estándar para corrosividad al cobre de productos derivados del petróleo
- Temperatura: 50°C (gasolinas) / 100°C (diesel, jet fuel)
- Tiempo: 3 horas (180 minutos)
- Tolerancia: ±2°C respecto a temperatura objetivo

### 🚀 Uso del Dashboard

1. **Abrir el dashboard**: https://[usuario].github.io/[repositorio]/
2. **Seleccionar muestra**: Click en preset o ingresar datos manualmente
3. **Registrar condiciones**: Temperatura real y hora de inicio
4. **Realizar ensayo**: Sumergir lámina durante 3 horas
5. **Evaluar visualmente**: Seleccionar clasificación observada en la escala
6. **Obtener diagnóstico**: Revisión automática de nivel de corrosividad

### 📱 Compatibilidad

- Funciona **offline** (una vez descargado)
- Funciona **online** (publicado en GitHub Pages)
- Diseño responsive (desktop y móvil)
- Sin dependencias externas de cálculo
- Tema oscuro optimizado para laboratorio

### 📄 Documentos Adicionales

- **Planilla de laboratorio Word**: Para anotación manual durante la práctica
- **Informe de referencia PDF**: Ejemplo completo con resultados reales

### 🔬 Datos Experimentales de Referencia

Según informe Univ. Queso Escobar (UMSA PTQ-715):

| Muestra | Clasificación | Designación | Descripción |
|---------|--------------|-------------|-------------|
| Gasolina Especial | 1a | Ligeramente manchada | Anaranjado claro |
| Diesel | 1a | Ligeramente manchada | Anaranjado claro |
| Kerosene | 1b | Ligeramente manchada | Anaranjado oscuro |
| Gasolina + 1% S | 4b | Corrosión | Negro opaco |

### 🛠️ Tecnologías

- HTML5 + CSS3 + JavaScript vanilla
- Diseño GitHub dark theme
- Sin frameworks (standalone)
- Sin backend requerido

### 📝 Licencia

Uso académico — Universidad Mayor de San Andrés (UMSA)  
Carrera de Ingeniería Petrolera · Refinación del Petróleo PET-212

---

**Desarrollado para**: Estudiantes de Ingeniería Petrolera UMSA  
**Materia**: Refinación del Petróleo PET-212  
**Norma**: ASTM D-130

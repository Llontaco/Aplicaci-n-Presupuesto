# 💰 Aplicación de Presupuesto Personal

Una aplicación web interactiva para gestionar ingresos y egresos personales, desarrollada con JavaScript vanilla, HTML5 y CSS3. La aplicación permite visualizar el presupuesto disponible, agregar nuevos ingresos/egresos y eliminar elementos existentes con formato de moneda profesional.

## 🚀 Características

- **Gestión de Ingresos**: Agregar, visualizar y eliminar ingresos
- **Gestión de Egresos**: Agregar, visualizar y eliminar egresos con cálculo automático de porcentajes
- **Presupuesto Dinámico**: Cálculo automático del presupuesto disponible (ingresos - egresos)
- **Formato de Moneda**: Formato profesional de moneda en euros (EUR)
- **Formato de Porcentajes**: Visualización de porcentajes de gastos respecto al total
- **Interfaz Intuitiva**: Diseño limpio y fácil de usar
- **Responsive Design**: Adaptable a diferentes tamaños de pantalla

## 🛠️ Tecnologías Utilizadas

- **HTML5**: Estructura semántica de la aplicación
- **CSS3**: Estilos y diseño responsive
- **JavaScript ES6+**: Lógica de la aplicación con clases y programación orientada a objetos
- **Ionicons**: Iconos para la interfaz de usuario

## 📁 Estructura del Proyecto

```
21-17-FormatoMoneda-UJS/
├── index.html          # Página principal de la aplicación
├── css/
│   ├── estilos.css     # Hoja de estilos principal
│   └── fondo.png       # Imagen de fondo
├── js/
│   ├── app.js          # Lógica principal de la aplicación
│   ├── Dato.js         # Clase base para datos
│   ├── Ingreso.js      # Clase para ingresos
│   └── Egreso.js       # Clase para egresos
└── README.md           # Este archivo
```

## 🎯 Funcionalidades

### Visualización del Presupuesto
- **Presupuesto Disponible**: Muestra el total disponible (ingresos - egresos)
- **Total de Ingresos**: Suma de todos los ingresos registrados
- **Total de Egresos**: Suma de todos los egresos con porcentaje respecto a ingresos
- **Actualización Automática**: Todos los valores se actualizan dinámicamente

### Gestión de Transacciones
- **Agregar Ingresos**: Formulario para registrar nuevos ingresos
- **Agregar Egresos**: Formulario para registrar nuevos gastos
- **Eliminar Elementos**: Botón de eliminación para cada transacción
- **Validación**: Verificación de campos obligatorios antes de agregar

### Formato y Visualización
- **Moneda EUR**: Formato europeo para valores monetarios
- **Porcentajes**: Cálculo automático del porcentaje de cada egreso
- **Iconos Intuitivos**: Uso de Ionicons para mejor experiencia de usuario

## 🚦 Cómo Usar

1. **Abrir la Aplicación**: Abrir `index.html` en cualquier navegador web moderno

2. **Agregar Transacciones**:
   - Seleccionar tipo (+ para ingresos, - para egresos)
   - Escribir descripción del movimiento
   - Ingresar valor numérico
   - Hacer clic en el botón de confirmación ✓

3. **Eliminar Transacciones**:
   - Hacer clic en el icono de eliminación (X) junto a cualquier elemento

4. **Visualizar Resumen**:
   - El presupuesto disponible se actualiza automáticamente
   - Los porcentajes de egresos se calculan en tiempo real

## 📊 Ejemplos de Uso

### Datos de Ejemplo Incluidos:
- **Ingresos**:
  - Salario: €2,100.00
  - Venta coche: €1,500.00
- **Egresos**:
  - Renta departamento: €900.00 (21% del total de egresos)
  - Ropa: €400.00 (10% del total de egresos)

### Presupuesto Resultante:
- **Total Ingresos**: €3,600.00
- **Total Egresos**: €1,300.00
- **Presupuesto Disponible**: €2,300.00

## 🔧 Instalación y Configuración

1. **Clonar o Descargar** el proyecto
2. **Abrir** `index.html` en tu navegador preferido
3. **¡Listo!** No requiere instalación de dependencias adicionales

## 🌐 Compatibilidad

- **Navegadores Modernos**: Chrome, Firefox, Safari, Edge
- **JavaScript ES6+**: Requiere soporte para clases y arrow functions
- **Responsive**: Funciona en dispositivos móviles y de escritorio


## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 👨‍💻 Autor

Desarrollado como proyecto educativo para aprender JavaScript moderno y programación orientada a objetos.

Henry Llontop Falcon 


### 🐛 Reportar Problemas

Si encuentras algún error o tienes sugerencias, por favor abre un issue en el repositorio del proyecto.

### 🐛 Vista Previa
<img width="1817" height="733" alt="image" src="https://github.com/user-attachments/assets/38235435-4de2-4fda-8852-fa7617cf4993" />


# SIMREF-HC 2025: Simulador Avanzado de Refinería 🛢️

## ✨ Visión General

SIMREF-HC 2025 es un simulador financiero de vanguardia diseñado específicamente para el análisis de refinerías de hidrocarburos ya establecidas y amortizadas. Desarrollado por el Ing. Benito Cabrera R., este simulador proporciona una visión integral de la operación financiera de una refinería bajo diversas condiciones de mercado y parámetros operativos.

## 🔥 Características Destacadas

- **Modelado Dinámico**: Simula el comportamiento económico de una refinería en tiempo real
- **Análisis de Sensibilidad**: Evalúa el impacto de fluctuaciones de precios del crudo y productos refinados
- **Visualizaciones Interactivas**: Gráficos que ilustran la distribución de productos y contribución al margen
- **Proyecciones Financieras**: Resultados anualizados para facilitar la planificación estratégica
- **Diseño Responsivo**: Funciona perfectamente en dispositivos móviles y de escritorio

## 🚀 Instalación

```bash
# Clonar el repositorio
git clone https://github.com/benitocabrera/simref-hc.git

# Navegar al directorio del proyecto
cd simref-hc

# Abrir directamente en el navegador
open index.html
```

Alternativamente, puedes implementar el simulador en cualquier servidor web o utilizarlo directamente desde GitHub Pages.

## 💻 Tecnologías Utilizadas

- **React 18**: Framework principal para la interfaz de usuario
- **Recharts**: Biblioteca para visualizaciones de datos
- **Tailwind CSS**: Framework de diseño para una interfaz elegante y responsiva
- **Babel**: Compilador JavaScript para compatibilidad entre navegadores

## 📊 Capacidades de Modelado

SIMREF-HC 2025 permite a los usuarios ajustar parámetros clave:

| Categoría | Parámetros |
|-----------|------------|
| Operativos | Capacidad de procesamiento, Calidad API del crudo, Precio del crudo |
| Comerciales | Precios de venta de gasolina, diésel, jet fuel, LPG, coque y otros productos |
| Financieros | Costos operativos, Gastos administrativos, Mantenimiento, Tasa de impuestos, Días operativos |

## 📈 Métricas Clave Calculadas

- Margen bruto por barril
- Proyección de ingresos anuales
- Beneficio neto anual
- Margen de beneficio porcentual

## 🌟 Casos de Uso Sugeridos

- **Evaluación de Rentabilidad**: Determina puntos de equilibrio y umbrales de rentabilidad
- **Planificación Estratégica**: Proyecta escenarios financieros bajo diferentes condiciones de mercado
- **Optimización de Operaciones**: Identifica los productos con mayor contribución al margen
- **Gestión de Riesgos**: Evalúa la vulnerabilidad financiera ante fluctuaciones de precios

## 🔍 Ejemplo de Análisis

```javascript
// Ejemplo de escenario rentable
const escenarioRentable = {
  capacidad: 150000,  // barriles por día
  precioCrudo: 65,    // USD por barril
  precioGasolina: 95, // USD por barril
  costoOperativo: 4.2 // USD por barril
};

// Escenario con riesgo
const escenarioRiesgo = {
  capacidad: 100000,  // barriles por día
  precioCrudo: 85,    // USD por barril
  precioGasolina: 97, // USD por barril
  costoOperativo: 5.5 // USD por barril
};
```

## 📝 Próximas Mejoras (Roadmap)

- [ ] Integración con APIs de precios de crudo en tiempo real
- [ ] Módulo de optimización con algoritmos genéticos
- [ ] Exportación de resultados a Excel y PDF
- [ ] Panel de análisis de tendencias históricas
- [ ] Comparación entre múltiples escenarios simultaneamente

## 🛠️ Para Desarrolladores

SIMREF-HC 2025 está diseñado para ser extensible. El código está estructurado en componentes React modulares que pueden ser fácilmente ampliados:

```jsx
// Ejemplo de cómo extender con un nuevo análisis
function NuevoAnalisis({ datos }) {
  // Tu código aquí
  return (
    <div className="nuevo-analisis">
      {/* Componente personalizado */}
    </div>
  );
}
```

## 🔒 Licencia y Contacto

Este software es propiedad intelectual de Ing. Benito Cabrera R., MBA. Todos los derechos reservados ©2025.

Para consultas sobre licencias comerciales o desarrollo personalizado:
- Email: benito.cabrera@refineria-sim.com
- LinkedIn: [linkedin.com/in/benitocabreramba](https://linkedin.com/in/benitocabreramba)

---

<p align="center">
  <i>"La verdadera rentabilidad se encuentra en el análisis preciso de los datos."</i><br>
  — Ing. Benito Cabrera R.
</p>

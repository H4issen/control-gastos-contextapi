# Planificador de Gastos — Controla tu presupuesto

¿Sabes exactamente cuánto has gastado este mes? ¿Te queda claro en qué se va tu dinero? Esta app te ayuda a **planificar un presupuesto mensual** y registrar cada gasto para que siempre sepas cuánto te queda.

## ¿Qué hace?

Define un presupuesto mensual y empieza a registrar tus gastos por categorías (comida, casa, salud, ocio, ahorro, etc.). La app te muestra:

- Un **gráfico circular** con el progreso de tu gasto vs presupuesto
- El **saldo restante** actualizado en tiempo real
- Tus gastos ordenados y **filtrables por categoría**
- Cada gasto con **fecha, monto, categoría y nombre**

## ¿Qué problemas resuelve?

| Sin control                                    | Con este planificador                    |
|------------------------------------------------|------------------------------------------|
| No sabes en qué se fue tu quincena             | Ves cada gasto por categoría             |
| Llevas cuentas en papel o mental               | Todo digital, actualizado al instante    |
| Difícil saber cuánto te queda                 | El saldo restante se calcula solo        |
| No puedes identificar fugas de dinero          | Filtra por categoría y detecta patrones  |

## Posibles mejoras futuras

- Múltiples presupuestos (uno por mes)
- Exportar gastos a PDF o Excel
- Alertas cuando te acerques al límite
- Modo oscuro y personalización visual
- Sincronización en la nube entre dispositivos
- Registro de ingresos además de gastos

## Stack técnico

React + TypeScript + Context API + useReducer + Tailwind CSS + Vite. Desplegable en GitHub Pages.

```bash
npm install
npm run dev      # desarrollo
npm run deploy   # publicar

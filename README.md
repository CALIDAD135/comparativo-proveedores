# 📊 Comparativo de Proveedores — IES Internacional

> **Repositorio:** `CALIDAD135/comparativo-proveedores`
> **Área:** Coordinación de Activos Fijos y Control Vehicular — ITTSA
> **Versión:** 1.0.0 · Junio 2026

---

## Descripción

Herramienta HTML interactiva para el control y comparación de cotizaciones de proveedores. Permite gestionar múltiples folios de comparativo, capturar registros manualmente o mediante carga de CSV, visualizar indicadores clave (KPIs) y exportar toda la información a Excel.

---

## Características

| Función | Descripción |
|---|---|
| **Multi-folio** | Crea un folio independiente por proceso de compra (COT INTERNA) |
| **Dashboard de indicadores** | KPIs: total, promedio, mínimo, máximo, ahorro potencial, distribución por estatus y zona |
| **Carga de CSV** | Importa registros desde archivo CSV con estructura estándar |
| **Captura manual** | Formulario completo con 28 campos según estructura operativa |
| **Exportar a Excel** | Genera `.xlsx` con una hoja por folio y una hoja de resumen global |
| **Plantilla CSV** | Descarga la plantilla base con ejemplo incluido |

---

## Estructura de campos (CSV)

```
GESTOR, FECHA SOLICITUD, ZONA, UNIDAD, DEPARTAMENTO,
# COT INTERNA, #SOLPED, # COTIZACION PROVEEDOR, JUSTIFICACION,
DESCRIPCION DE ARTICULO, PROVEEDOR (R.Z), MARCA, CANTIDAD, U.M,
SUBTOTAL, IVA, TOTAL, DIFERENCIA / PROVEEDORES, TIEMPO DE GARANTÍA,
FECHA DE AUTORIZACIÓN, UNIDAD.1, PROVEEDOR, CONDICIONES,
TIEMPO DE ENTREGA, FACTURA, ESTATUS, AUTORIZA, OBSERVACIONES
```

---

## Uso

1. Abrir `index.html` en cualquier navegador moderno.
2. Crear un folio con **＋ Nuevo Folio** (Ej. `COMP-2026-001`).
3. Cargar datos vía CSV o capturar manualmente en la pestaña **Captura**.
4. Revisar indicadores en la pestaña **Dashboard**.
5. Exportar con **📊 Exportar Excel** para entrega institucional.

> Los datos se almacenan en `localStorage` del navegador. Para uso compartido, exportar a Excel y redistribuir.

---

## Archivos del repositorio

```
comparativo-proveedores/
├── index.html               # Aplicación principal
└── plantilla_comparativo.csv # Plantilla de carga con ejemplo
```

---

*Coordinación de Activos Fijos — ITTSA · IES Internacional*

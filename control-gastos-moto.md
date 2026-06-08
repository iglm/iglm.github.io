---
layout: page
title: Control de Gastos Moto
description: App Android nativa para control de gastos de moto — gasolina, repuestos, mantenimientos, informes y rendimiento
icon: fas fa-motorcycle
order: 3
---

App Android nativa para llevar el control de **todos los gastos de tu moto**: gasolina, repuestos, mantenimientos. Con gráficos, informes exportables y cálculo de rendimiento (km/galón).

## 🎯 Funcionalidades reales

- ✅ Registro de **motos** con marca, modelo y kilometraje inicial
- ✅ **Gastos** por categoría: GASOLINA, REPUESTOS, MANTENIMIENTO, SEGURO, IMPUESTOS, OTROS
- ✅ Registro de **kilometraje** en cada gasto para calcular rendimiento
- ✅ **Dashboard** con gráficos de gasto mensual, por categoría y rendimiento
- ✅ Resumen por categoría: total, cantidad y promedio
- ✅ **Alertas** configurables de mantenimiento (ej: cada 3000 km)
- ✅ Exportación a **CSV**, **PDF** (informe profesional HTML→PDF) y **backup JSON**
- ✅ Splashscreen y onboarding para primera configuración
- ✅ **Gráficos interactivos** con Vico (barras, dona, línea)
- ✅ 100% offline-first — Room database local

## 📊 Ejemplo de uso

1. Agregás tu moto (marca, modelo, km inicial)
2. Cada vez que tanqueás → registrás GASOLINA con km actual
3. La app calcula el rendimiento automáticamente
4. Dashboard te muestra cuánto gastás por mes y en qué
5. Exportás el informe PDF para tu contador o control personal

## 👥 ¿Para quién es?

- **Motociclistas** que quieren saber cuánto gastan realmente
- **Trabajadores rurales** que usan moto como herramienta de trabajo
- **Cualquiera** que quiera controlar gastos de su vehículo sin apps con suscripción

## 📊 Ficha técnica

| Especificación | Detalle |
|---|---|
| Plataforma | Android Nativo (Kotlin + Compose) |
| API mínima | Android 8.0 (API 26) |
| Tamaño APK | ~19MB |
| Persistencia | Room (SQLite offline) |
| Exportación | CSV, PDF, JSON |
| Gráficos | Vico (compose-m3) |
| DI | Hilt |
| Repositorio | [github.com/iglm/ControlGastosMoto](https://github.com/iglm/ControlGastosMoto) |

## 👤 Créditos

<div class="d-flex gap-3 flex-wrap mt-3">
  <div class="p-3 rounded" style="background:var(--card-bg);border:1px solid var(--border-color);flex:1;min-width:200px;">
    <strong>👨‍💻 Lucas Mateo Tabares Franco</strong><br>
    <small style="color:var(--text-muted-color);">Desarrollador</small>
  </div>
</div>

<div class="d-flex gap-2 mt-3">
  <a class="btn btn-success" href="mailto:mateotabares7@gmail.com?subject=Quiero%20Control%20Gastos%20Moto">📩 Solicitar App</a>
  <a class="btn btn-outline-success" href="https://github.com/iglm/ControlGastosMoto">🐙 Ver en GitHub</a>
</div>

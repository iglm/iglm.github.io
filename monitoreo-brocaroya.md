---
layout: page
title: Monitoreo Broca y Roya
description: App Android nativa para monitoreo de broca y roya en café — evaluación árbol por árbol con relleno estadístico y exportación a Excel
icon: fas fa-leaf
order: 2
---

Aplicación Android nativa para la evaluación de incidencia de **broca** (*Hypothenemus hampei*) y **roya** (*Hemileia vastatrix*) en cultivos de café. Diseñada para ser usada directamente en el lote, árbol por árbol, con campos grandes y accesibles.

## 🎯 Funcionalidades clave

- ✅ Evaluación de hasta **50 árboles por lote** (finalización anticipada con relleno estadístico)
- ✅ **13 campos por árbol**: NFA, FBA, NFS, FBS, NH, HR, NHM, MR, AR, GOT, CHA, ANT, DEF
- ✅ **Relleno estadístico automático**: si se evalúan menos de 50 árboles, la app completa los datos restantes usando distribución normal (media + desviación estándar de los datos reales)
- ✅ **Exportación a Excel** con 3 hojas: Resumen (totales y %), Árboles (datos detallados), Info (créditos)
- ✅ **Pantalla de reporte** visual con barras de progreso de % infestación
- ✅ **Offline-first** — Room database local. Si el celular se apaga, los datos no se pierden
- ✅ **Dark mode** automático
- ✅ **Material 3** — interfaz moderna y responsiva
- ✅ Hecha en **Kotlin + Compose + Hilt + Room + Apache POI**
- ✅ Android nativo 100% (sin Capacitor, sin WebView)

## 📋 Campos evaluados

| Código | Descripción | Tipo |
|--------|-------------|------|
| NFA | Frutos en rama seleccionada | Numérico |
| FBA | Frutos brocados en rama | Numérico |
| NFS | Frutos en plato del árbol | Numérico |
| FBS | Frutos brocados en plato | Numérico |
| NH | Total de hojas en rama | Numérico |
| HR | Hojas con roya | Numérico |
| NHM | Hojas con minas | Numérico |
| MR | Mal rosado | 0/1 |
| AR | Arañita roja | 0/1 |
| GOT | Gotera | 0/1 |
| CHA | Chamusquina | 0/1 |
| ANT | Antracnosis | 0/1 |
| DEF | Deficiencia nutricional | 0-4 (No, N, P, K, Mg) |

## 👥 ¿Para quién es?

- **Caficultores** que quieren tomar decisiones basadas en datos reales de su lote
- **Ingenieros agrónomos** que asesoran múltiples fincas y necesitan informes profesionales
- **Técnicos de campo** que realizan monitoreo fitosanitario sistemático
- **Cooperativas** que certifican calidad y sanidad en café

## 📊 Ficha técnica

| Especificación | Detalle |
|----------------|---------|
| Plataforma | Android Nativo (Kotlin + Compose) |
| API mínima | Android 8.0 (API 26) |
| Tamaño APK | ~25MB |
| Persistencia | Room (SQLite offline) |
| Exportación | Excel .xlsx (Apache POI) |
| DI | Hilt |
| Repositorio | [github.com/iglm/MonitoreoBrocaRoya](https://github.com/iglm/MonitoreoBrocaRoya) |

## 👥 Créditos

<div class="d-flex gap-3 flex-wrap mt-3">
  <div class="p-3 rounded" style="background:var(--card-bg);border:1px solid var(--border-color);flex:1;min-width:200px;">
    <strong>👨‍💻 Lucas Mateo Tabares Franco</strong><br>
    <small style="color:var(--text-muted-color);">Ingeniero Agrónomo & Desarrollador</small><br>
    <small style="color:var(--text-muted-color);">Universidad de Caldas</small>
  </div>
  <div class="p-3 rounded" style="background:var(--card-bg);border:1px solid var(--border-color);flex:1;min-width:200px;">
    <strong>👨‍🌾 Alfredo García Llano</strong><br>
    <small style="color:var(--text-muted-color);">Administrador de Empresas Agropecuarias</small><br>
    <small style="color:var(--text-muted-color);">Universidad de Caldas</small>
  </div>
</div>

<div class="d-flex gap-2 mt-3">
  <a class="btn btn-success" href="mailto:mateotabares7@gmail.com?subject=Quiero%20Monitoreo%20BrocaRoya">📩 Solicitar App</a>
  <a class="btn btn-outline-success" href="https://github.com/iglm/MonitoreoBrocaRoya">🐙 Ver en GitHub</a>
</div>

---
layout: page
title: Drought Early Warning System
description: Probabilistic drought forecasting using multi-source data fusion and Kalman filtering
img:
importance: 1
category: work
---

An automated early warning platform for anticipatory humanitarian action. The system ingests data from multiple sources — satellite vegetation indices, rainfall records, food prices, soil moisture, and seasonal forecasts — and fuses them using a Kalman filter-based state space model to produce probabilistic drought risk forecasts.

## The Problem

Humanitarian organisations rely on manual, retrospective trigger scores to decide when to release pre-positioned aid. By the time a crisis is confirmed, the 6–12 week window needed for anticipatory action has already closed. The system replaces that manual process with an automated, forward-looking forecast.

## Features

- Automated data ingestion from satellite and climate APIs
- Kalman filter fusion of heterogeneous, irregularly-observed indicators
- Probabilistic output — full distributions, not point estimates
- 1, 3, and 6-month forecast horizons
- Explicit uncertainty quantification that varies with data availability
- Structural break detection for climate regime shifts

## Live App

**[earlywarning.gabriel-oduori.com](https://earlywarning.gabriel-oduori.com/)**

## Technologies

- Python (state space models, Kalman filtering)
- Streamlit
- Multi-source remote sensing and climate data

---

*Pilot deployment: Zimbabwe. Built on Harvey's Structural Time Series framework.*

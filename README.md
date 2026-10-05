# ReliefLink – Modular Design of a Disaster Relief Resource Allocation Platform

Micro project for **Software Engineering Practices (CIAP)** · Aligned with **SDG 11: Sustainable Cities and Communities**

## Overview
A modular web prototype that helps relief coordinators collect disaster-relief requests, track inventory, and allocate resources by priority.

## Modules
1. **Request Intake** – submit requests with area, disaster type, severity, people affected, vulnerable groups, and resources needed
2. **Inventory** – view and update stock (Food, Water, Medical, Blankets, Tents)
3. **Allocation Engine** – ranks requests by priority score and allocates stock fairly
4. **Dashboard** – live stats, priority queue, coverage and inventory levels

## Allocation Logic
Priority score = severity × 20 + population factor (max 30) + 15 if children/elderly are present.
Requests are served highest score first, and each request is capped at 60% of current stock (fair-share rule).

## How to Run
Open `index.html` in any browser, or visit the live demo (GitHub Pages link).

## Author
Prathamesh Kini · TYCS · PRN 124BTCS1057

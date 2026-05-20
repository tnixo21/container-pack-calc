# Container Pack Calculator

A free, browser-based warehouse tool for calculating how many shipping containers are needed for a given packing list.

## 🔗 Live tool
**[Open the calculator](https://tnixo21.github.io/container-pack-calc)**

## Features
- Enter skid dimensions (L × W) manually or import a CSV
- Supports 20ft, 40ft Standard, 40ft High Cube, or custom container sizes
- MaxRects 2D bin-packing algorithm with optional 90° rotation
- Visual SVG floor plan per container showing exact skid placement
- Floor utilisation %, total weight, per-skid placement coordinates
- Print-friendly output
- Works fully offline — no server, no login, no install

## CSV format
```
CaseID, Description, Length(cm), Width(cm), Weight(kg), Qty
G1431014, CARRIER, 102, 120, 310, 1
```

## Container dimensions used
| Type | Internal Floor |
|---|---|
| 20ft Standard | 590 × 235 cm |
| 40ft Standard | 1204 × 235 cm |
| 40ft High Cube | 1204 × 235 cm |
| Custom | user-defined |

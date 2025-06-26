# 🇬🇹 JSON de Lugares Poblados de Guatemala

Este repositorio contiene un archivo JSON estructurado con todos los **departamentos**, **municipios** y **lugares poblados** de la República de Guatemala, con sus respectivas **coordenadas geográficas (latitud y longitud)**.

Los datos provienen del archivo oficial publicado por el Instituto Nacional de Estadística (INE) de Guatemala, con base en el **XII Censo Nacional de Población y VII de Vivienda 2018**.

---

## 🧾 Estructura del archivo

El archivo JSON está jerarquizado así:

- **Departamento**
  - **Municipios**
    - **Lugares poblados**

```json
[
  {
    "codigo": "1",
    "nombre": "Guatemala",
    "municipios": [
      {
        "codigo": "101",
        "nombre": "Guatemala",
        "poblados": [
          {
            "codigo": "101001",
            "nombre": "Zona 1",
            "centroide": {
              "latitud": 14.6349,
              "longitud": -90.5069
            }
          }
        ]
      }
    ]
  }
]

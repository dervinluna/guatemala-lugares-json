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
````

---

📌 Usos comunes

* Formularios con selects anidados (Departamento → Municipio → Poblado)
* Aplicaciones móviles y web con enfoque local
* Análisis geográficos o demográficos
* Sistemas de localización



🏛️ Fuente de los datos

Instituto Nacional de Estadística (INE), Guatemala
🔗 [https://www.ine.gob.gt/](https://www.ine.gob.gt/)

Archivo base:
**“Centroides de lugares poblados de la República de Guatemala - Censo 2018”**

---

## 🧑‍💻 Créditos

Conversión a JSON estructurado realizada por \[Tu nombre o tu usuario de GitHub].

---

## ⚠️ Aviso legal

Los datos originales son propiedad del INE de Guatemala. Este repositorio no tiene afiliación oficial con dicha institución. La finalidad de este proyecto es **facilitar el uso técnico de la información pública ya disponible**.

```

---

Cuando tengas el archivo `centroides-lugares-poblados.json` en el mismo repositorio, solo subes esto como `README.md` y estará todo listo para compartir. ¿Te gustaría que te ayude también a crear el nombre del repositorio y una pequeña descripción para GitHub?
```


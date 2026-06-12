# Prototipo-ML-para-Clasificacion-de-Tickets-de-Soporte

### ***[Para probar el Modelo por favor consulta el archivo "Installation.md"]***
### ***[Video de Demostración]:*** https://drive.google.com/file/d/1M6whJJsUWoz_3IwJ4zWuZ8V7VLBbsdKE/view?usp=drivesdk
Sistema de clasificación automática de tickets de soporte usando **Random Forest + SMOTE**. El cual tiene como objetivo automatizar la categorización y derivación de tickets de soporte para reducir la carga manual en el equipo de atención al cliente. El sistema analiza el contenido del email (asunto+cuerpo) y predice dimensiones como: 

- Departamento o Área.
- Nivel de Urgencia: Crítico, Media y Baja
- Tipo de Tema o Categoría: Falla Técnica, Facturación, etc.

## Características Principales
- Clasificación multietiqueta: `type`, `priority` y `queue`
- Soporte para texto en **inglés**
- Uso de **TF-IDF** + **Random Forest**
- Balanceo de clases con **SMOTE** (datos sinteticos)
- Mejor rendimiento en `type` (90% accuracy)

## Resultados

| Variable     | Accuracy | F1-Score (weighted) |
|--------------|----------|---------------------|
| `type`       | 0.90     | 0.8935              |
| `priority`   | 0.75     | 0.7476              |
| `queue`      | 0.73     | 0.7267              |

---

## Tecnologías Utilizadas
- Python 3
- scikit-learn
- pandas, numpy
- imbalanced-learn (SMOTE)
- matplotlib, seaborn

## Beneficios
- Reducción del tiempo de respuesta a clientes.
- Disminución de la saturación y burnout del equipo de atención.
- Escalabilidad para manejar volumenes crecientes de consultas.

Destinado a empresas con alto volumen de atención al cliente que buscan automatizar y optimizar sus procesos administrativos.


# GRUPO 2:
- Alejandro, Jessica Belén
- Durán, Alicia
- Gimenez Soria, Melina Jaqueline
- Guerrero, Daniela Viviana
- Vallejo Guerrero, Nicolás Ezequiel 






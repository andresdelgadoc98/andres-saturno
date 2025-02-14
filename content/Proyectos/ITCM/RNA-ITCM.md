---
title: Clasificador Fluidos
date: 2021-04-03T22:41:10+05:30
draft: false
author: "Andrés"
tags:
  - Redes Neuronales
  - Inteligencia Artificial
  - Tesis
image: /images/projects/algoritmo.png
description: "Elaboración de un algoritmo basado en Redes Neuronales para la clasificación de fluidos en tiempo real."
toc:
categories: ["D -  Instituto Tecnológico de Ciudad Madero"]
---

# Proyecto: Clasificación de Fluidos mediante Redes Neuronales Artificiales

## Descripción del Proyecto

Este documento explora la efectividad de las Redes Neuronales Artificiales (RNA) en la clasificación de fluidos utilizando datos de vibraciones capturados en una tubería. El objetivo principal es desarrollar una metodología que reduzca el número de mediciones necesarias sin afectar significativamente el desempeño del algoritmo de clasificación.

## Metodología

- **Recopilación de Datos**: Los datos fueron recolectados en un laboratorio experimental diseñado específicamente para este estudio, permitiendo obtener información en un ambiente controlado.
- **Fluidos de Referencia**: Se utilizaron dos fluidos principales para el estudio: agua y agua con jabón.
- **Escenarios Secundarios**: Se incluyeron dos escenarios adicionales: tubería vacía con la bomba encendida y tubería vacía con la bomba apagada.

## Resultados

![Comparativa de aprendizaje de los diferentes conjuntos](/images/projects/presicion_epoca.png)  
_Fig. 1: Comparativa de aprendizaje de los diferentes conjuntos_

- **Precisión de Clasificación**: Los modelos de RNA lograron una precisión mayor al 97% en la clasificación de los fluidos Como se puede observar en la Figura 1 en dónde se exploraron multiples conjuntos con diferentes números de mediciones obteniendo una presición aceptalbe para cada uno de ellos.

- **Reducción de Mediciones**: Se realizó una comparativa entre diferentes conjuntos de datos, reduciendo el número de mediciones de 2048 a 1500. Los resultados indicaron que no hubo una diferencia significativa en la precisión del modelo, lo que sugiere una mejora tanto en el espacio como en el tiempo de procesamiento.

## Conclusiones

- **Efectividad de las RNA**: Las Redes Neuronales Artificiales demostraron ser altamente efectivas en la clasificación de fluidos basada en datos de vibraciones.
- **Optimización de Recursos**: La reducción en el número de mediciones no afectó significativamente la precisión del modelo, lo que representa una optimización importante en términos de recursos computacionales y tiempo.

## Beneficios

- **Eficiencia**: Reducción en el número de mediciones necesarias sin comprometer la precisión.
- **Precisión**: Alta efectividad en la clasificación de fluidos, con una precisión superior al 97%.
- **Aplicabilidad**: Metodología aplicable en entornos industriales para la monitorización y clasificación de fluidos en tuberías.

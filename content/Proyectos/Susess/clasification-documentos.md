---
title: "Clasificador Documentos"
date: 2021-04-03T22:41:10+05:30
draft: false
author: "Andrés Delgado"
tags:
  - OPENAI
  - Agente
  - Clasificador
  - Python
  - LangChain
image: /images/projects/clasificador_documentos.jpg
description: "Clasificación masiva de documentos, eliminando la necesidad de que los usuarios tengan que subir archivos uno por uno a un sistema gestor de documentos. En su lugar, el sistema permite la carga de múltiples archivos y realiza una clasificación automática de los mismos"
toc:
categories: ["A - Grupo Susess"]
---

# Clasificación Automática de Documentos

## Descripción del Proyecto

Este proyecto tiene como objetivo principal facilitar la clasificación masiva de documentos, eliminando la necesidad de que los usuarios tengan que subir archivos uno por uno a un sistema gestor de documentos. En su lugar, el sistema permite la carga de múltiples archivos y realiza una clasificación automática de los mismos.

## Tecnologías Utilizadas

- **Computing Vision**: Integrado con modelos de lenguaje grandes (LLM) para obtener referencias y mejorar la precisión en la clasificación.
- **Sistemas de Embeddings**: Utilizados para la búsqueda y coincidencia de palabras clave dentro de los documentos.
- **Conexión a Base de Datos**: El sistema se conecta a la base de datos del negocio para obtener recomendaciones de categorías previamente establecidas, facilitando así una clasificación más precisa y consistente.
- **Python Como Lenguaje de Programación**: Aprovechando las librerias más eficientes y actuales como LangChain hacen de python el lenguaje por exelencia para este tipo de proyectos.

## Funcionalidades Clave

- **Carga Masiva de Documentos**: Permite a los usuarios subir múltiples archivos simultáneamente.
- **Clasificación Automática**: Utiliza avanzadas técnicas de procesamiento de lenguaje natural y visión por computadora para clasificar los documentos automáticamente.
- **Recomendaciones de Categorías**: Integra con la base de datos del negocio para sugerir categorías basadas en clasificaciones anteriores.

## Beneficios

- **Eficiencia**: Reduce significativamente el tiempo necesario para clasificar documentos.
- **Precisión**: Mejora la exactitud de la clasificación mediante el uso de tecnologías avanzadas.
- **Escalabilidad**: Capaz de manejar grandes volúmenes de documentos sin comprometer el rendimiento al utilizar sistemas en paralelo para procesar la información.

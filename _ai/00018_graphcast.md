---
title: "Post 18: GraphCast, una IA que predice el clima 🌍"
collection: ai
permalink: /ai/00018_graphcast
date: 2023-11-08
---

&nbsp;

A veces veo IAs como esta y me asombra lo que se puede modelar solo usando datos 💻

Hace unos días Google presentó GraphCast, una IA que predice el clima de los siguientes 10 días y que le gana a los sistemas actuales basados en ecuaciones de física. Esto es increíble pues a la IA jamás se le enseñaron temas de física, solo al observar los datos es capaz de aprender sobre este tipo de fenómenos. Además, GraphCast es de código abierto!

El clima es muy complicado de modelar dado la infinidad de variables y sus interacciones, lo cual lo convierte en algo caótico. Pero ¿cómo le hicieron? Usaron datos climáticos 38 años (de 1979 a 2017). Luego dividieron la atmosfera en 37 niveles de arriba abajo, cada uno dividido en cuadrantes de 0.25° de longitud-latitud; lo cual significa que cada cuadrante tiene cientos de variables climáticas por cada día/mes/año. Luego, representan estos cuadrantes como una red, siendo cada uno de ellos un nodo interconectado con otros cuadrantes.

Aquí aplican una IA especializada en aprender patrones relacionales llamada “red neuronal de grafos” que permite saber qué condiciones climáticas de un punto especifico son determinadas dado las variables climáticas de todos los cuadrantes de la red. Sin embargo, el proceso de entrenamiento inicia desde cuadrantes a grande resolución y se va refinando hasta llegar a los cuadrantes más chicos de 0.25°. Es decir, este proceso permite estimar que variables climáticas en X punto de la Tierra tienen efecto en otro punto a un tiempo específico comenzando a una escala global y refinándose a una escala especifica.

![img](/images/ai/00018_graphcast.jpg)

Y así, con este enfoque es que pueden preguntarle qué condiciones climáticas son probables de ocurrir dado las condiciones en los otros puntos de la Tierra, lo cual les permitió identificar fenómenos peligrosos como ciclones, temperaturas extremas, etc.

Refs:
* [Blog oficial de GraphCast ](https://deepmind.google/discover/blog/graphcast-ai-model-for-faster-and-more-accurate-global-weather-forecasting)

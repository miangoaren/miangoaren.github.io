---
title: "Post 16: Los demonios detras de la IA ⚠️"
collection: ai
permalink: /ai/00016_soggoth
date: 2023-10-16
---

&nbsp;


Desde que salió GPT4 se ha usado la analogía de un monstruo Lovecraftiano (Soggoth) para ilustrar como es que la parte con la que interactuamos con la IA es la que nos hace percibir que es una maravilla y que "entiende" cosas. 


GPT4 se entrenó con toda la mugre que hay en internet y para que su uso sea seguro, lo tienen que "detoxificar" indicando ejemplos de resultados que tiene que dar y cuales no dar. Como las instrucciones para armar una bomba química. Y finalmente para que se perciba más conversacional se aplica una técnica llamada "aprendizaje por refuerzo con retroalimentación humana" la cual se suele ilustrar con la mascara de una carita feliz amarilla

<figure>
  <a href="/images/ai/00016_sog.jpg">
  <img src="/images/ai/00016_sog.jpg" alt = "IMG" />
    </a>
  <figcaption>xxxxxxx</figcaption>
</figure>

<figure>
  <a href="/images/ai/00016_sog2.jpg">
  <img src="/images/ai/00016_sog2.jpg" alt = "IMG" />
    </a>
  <figcaption>xxxxxxx</figcaption>
</figure>

<figure>
  <a href="/images/ai/00016_sog3.jpg">
  <img src="/images/ai/00016_sog3.jpg" alt = "IMG" />
    </a>
  <figcaption>xxxxxxx</figcaption>
</figure>


<figure>
  <a href="/images/ai/00016_sog4.jpg">
  <img src="/images/ai/00016_sog4.jpg" alt = "IMG" />
    </a>
  <figcaption>xxxxxxx</figcaption>
</figure>

<figure>
  <a href="/images/ai/00016_sog5.jpg">
  <img src="/images/ai/00016_sog5.jpg" alt = "IMG" />
    </a>
  <figcaption>xxxxxxx</figcaption>
</figure>

<figure>
  <a href="/images/ai/00016_human.jpg">
  <img src="/images/ai/00016_human.jpg" alt = "IMG" />
    </a>
  <figcaption>xxxxxxx</figcaption>
</figure>

las IAs como GPT4 pueden dar respuestas debido a que han aprendido una distribución de probabilidad condicional sobre el texto con el que se entrenaron. Por eso es que si pides autocompletar "Anita lava la ..." te va a decir "tina" porque es la palabra cuya probabilidad se ajusta mejor a la distribución que aprendió. La cosa es que cualquier IA de este tipo que veas desplegada en producción ya a pasado por una "moralización artificial" (detoxificación de acuerdo con la empresa creadora) donde se han hecho múltiples pruebas para eliminar respuestas de odio, inclinación política, etc.

Si, puedes ponerlas a prueba para que te den la información que quieres (lo que se le llama jailbreak). Pero aun así lo estás haciendo sobre un modelo cuyas distribuciones de probabilidad ya han sido modificadas. No estas usando el modelos crudo recién salido de entrenarse con los datos de toda internet. Y en internet lo que más abunda es basura como puedes ver en el preprint de acá

En MX nos solemos mofar de todo, pero hacerlo del feminicidio es perpetuar la violencia. Además, dado que tiene que ver con IA, esto ilustra como el problema no son las maquinas, si no las personas detrás de ellas. Porque a algún pen#$% le pareció gracioso hacer esto. Las IAs se entrenan con datos de toda internet, y si algo hay ahí es odio, violencia (setsual) y misoginia. Acá pueden ver un ejemplo técnico del tipo info que hay en las bases de datos con las que se entrenan IAs como DallE o Stable Difussion y desde el titulo lo dejan claro 

https://arxiv.org/abs/2110.01963


Así que al ser modelos probabilísticos, estas IAs aprenden a responder como el texto en internet, con todo su odio y demás bajezas. Con fines de investigación se han liberado varias IAs que no han sido "moralizadas/censuradas". Asi se puede investigar que efecto tiene sobre distintas tareas el sesgar o no las distribuciones de probabilidad aprendidas por el modelo hacia un uso más seguro. Pues a priori no se sabe si hacerlo más seguro baja su rendimiento en tareas matemáticas, o de traducción de lenguajes, por ejemplo.

Un ejemplo de modelo no censurado es este llamado WizardLM
https://huggingface.co/ehartford/WizardLM-13B-Uncensored

Y para que quede claro que tan toxico puede ser una IA que no ha sido censurada/moralizada, aquí hay un ejemplo muy curioso. Se trata de una IA entrenada con todo el texto de 4chan, uno de los foros con más odio. Y veras que sus respuestas son otro pex. De hecho, es tan malo que los repositorios donde se suelen subir varias IAs han prohibido su uso.
https://youtu.be/efPrtcLdcdM?si=CHQX80R5lzQap-Dk

así que si le preguntaras a la versión de GPT4 que no ha sido moralizada/censurada y que tampoco ha pasado por el tuneo para hacerla más conversacional, las respuestas serian horribles. Y eso es justo lo que representa el Soggoth 

de hecho, se ha acusado a OpenAI de ser una empresa OGT (como es de esperarse de cualquier gran empresa) debido a que usaron otra empresa para detoxificar sus IAs como GPT4 o DallE mediante contratos similares al outsourcing; Donde a los empleados se les muestran imágenes o textos con descripciones inenarrables que tienen que etiquetar manualmente como contenidos seguros o no para que eso sirva de retroalimentación para la IA.

https://time.com/6247678/openai-chatgpt-kenya-workers/



<figure>
  <a href="/images/ai/00016_femin.jpg">
  <img src="/images/ai/00016_femin.jpg" alt = "IMG" />
    </a>
  <figcaption>xxxxxxx</figcaption>
</figure>

PENDIENTE
* https://twitter.com/AISafetyMemes/status/1675589349784657922
* https://twitter.com/soumithchintala/status/1671267150101721090
* https://twitter.com/robotson/status/1710849194964160664

explicacion de soggot
* https://knowyourmeme.com/memes/shoggoth-with-smiley-face-artificial-intelligence 
* https://www.youtube.com/watch?v=qsT45AdEVco&ab_channel=Fazt

  
eic
* https://gizmodo.com/pope-francis-vatican-releases-ai-ethics-1850583076
* https://twitter.com/AISafetyMemes/status/1675830112996958212
* https://twitter.com/DavidRozado/status/1599865724037922818
* https://twitter.com/wiczipedia/status/1673021410627710977
* https://www.artfish.ai/p/where-are-all-the-women
* https://www.fast.ai/posts/2023-11-07-dislightenment.html
* https://twitter.com/pandeyparul/status/1687295547915526144
* https://twitter.com/robotson/status/1710849194964160664
* https://twitter.com/Abebab/status/1445723482231173120?t=nbKkVI7JmJtrQBH6qfunwQ&s=19
* https://www.404media.co/inside-the-ai-porn-marketplace-where-everything-and-everyone-is-for-sale/
* https://twitter.com/Abebab/status/1694006441299058998
* https://www.washingtonpost.com/technology/2023/06/19/artificial-intelligence-child-sex-abuse-images/
* https://www.quantamagazine.org/what-does-it-mean-to-align-ai-with-human-values-20221213/
* https://twitter.com/katherine1ee/status/1678775512892854279
* https://twitter.com/AISafetyMemes/status/1672254934383820800
* https://twitter.com/mmitchell_ai/status/1671229552402497567
https://twitter.com/Abebab/status/1445723482231173120


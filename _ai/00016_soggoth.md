---
title: "Post 16: The Demons Behind AI ⚠️"
collection: ai
permalink: /ai/00016_soggoth
date: 2023-10-16
---

&nbsp;

Since the release of GPT-4, the analogy of a Lovecraftian monster (Soggoth) has been used to illustrate how the part we interact with in AI is what makes us perceive it as a marvel and as "understanding" things.

GPT-4 was trained with all the filth on the internet, and to ensure its safe use, it must be "detoxified" by indicating examples of the results it should and should not produce, such as instructions for making a chemical bomb. Finally, to make it more conversational, a technique called "reinforcement learning with human feedback" is applied, often illustrated by the mask of a smiling yellow face.

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

AIs like GPT-4 can provide responses because they have learned a conditional probability distribution over the text they were trained on. That's why if you ask it to autocomplete "Anita washes the ...", it will say "tina" because that's the word whose probability best fits the distribution it learned. However, any AI of this type that you see deployed in production has already undergone "artificial moralization" (detoxification according to the creating company), where multiple tests have been conducted to eliminate responses containing hate speech, political bias, etc.

Yes, you can test them to get the information you want (this is called "jailbreaking"). However, you are still doing this on a model whose probability distributions have already been modified. You are not using the raw model that has just been trained on the data from the entire internet. And on the internet, what abounds the most is garbage, as you can see in the preprint here.

In Mexico, we tend to make fun of everything, but mocking feminicide perpetuates violence. Furthermore, since this is related to AI, it illustrates that the problem is not the machines, but the people behind them. Because some idiot found it funny to do this. AIs are trained on data from the entire internet, and if there's one thing abundant there, it's hate, violence (including sexual violence), and misogyny. Here you can see a technical example of the kind of information found in the databases used to train AIs like DALL-E or Stable Diffusion, and the title makes it clear. 

<https://arxiv.org/abs/2110.01963>


So, being probabilistic models, these AIs learn to respond like the text on the internet, with all its hatred and other lowliness. For research purposes, several AIs have been released that have not been "moralized/censored". This allows researchers to investigate the effects of biasing or not biasing the probability distributions learned by the model towards a safer use. Because it is not known a priori whether making it safer reduces its performance in mathematical tasks or language translation, for example.

An example of an uncensored model is this one called WizardLM: 
<https://huggingface.co/ehartford/WizardLM-13B-Uncensored>

And to make it clear how toxic an AI can be when it has not been censored/moralized, here is a very curious example. It is an AI trained with all the text from 4chan, one of the forums with the most hatred. And you will see that its responses are quite something else. In fact, it is so bad that the repositories where several AIs are usually uploaded have banned its use.
<https://youtu.be/efPrtcLdcdM?si=CHQX80R5lzQap-Dk>

So, if you were to ask the uncensored version of GPT-4, which has not been moralized/censored and has not undergone tuning to make it more conversational, the responses would be horrible. And that is precisely what Soggoth represents.

In fact, OpenAI has been accused of being a shady company (as expected of any big company) because they used another company to detoxify their AIs like GPT-4 or Dall-E through contracts similar to outsourcing; Where employees are shown images or texts with unspeakable descriptions that they have to manually label as safe or unsafe content for feedback to the AI.

<https://time.com/6247678/openai-chatgpt-kenya-workers/>



<figure>
  <a href="/images/ai/00016_femin.jpg">
  <img src="/images/ai/00016_femin.jpg" alt = "IMG" />
    </a>
  <figcaption>xxxxxxx</figcaption>
</figure>

PENDING
* https://twitter.com/AISafetyMemes/status/1675589349784657922
* https://twitter.com/soumithchintala/status/1671267150101721090
* https://twitter.com/robotson/status/1710849194964160664

soggot explanation
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


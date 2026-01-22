---
title: "A roadmap for AI-driven protein design"
collection: teaching
type: "Course"
permalink: /teaching/proteins
venue: "YouTube"
date: 2025-10-10
location: "Mexico"
---

I created this <a href="https://github.com/miangoar/AI-driven-protein-design">free 10-lecture course</a> to introduce you to protein design.

![webinar](https://miangoar.github.io/images/teaching/roadmap.jpg)

## General description

I want more people to learn how to design proteins using Artificial Intelligence (AI). However, I’ve found two problems:
1. there are no comprehensive online courses on the topic  
2. the existing courses are often too expensive for most students in Latin America  

<p>To address these problems, I created this free 10-lecture course as an introduction to AI-driven protein design. The course has two main resources:</p>

<ol>
  <li><a href="https://www.youtube.com/@miangoar_bio">The 10 lectures on YouTube</a></li>
  <li><a href="https://github.com/miangoar/AI-driven-protein-desig">A GitHub repository</a> containing the following resources:
    <ol type="a">
      <li>Tools: recommended libraries organized into +10 categories such as protein sequence and structure processing, data management, machine learning, etc.</li>
      <li>Learning resources: courses and blogs to learn topics such as Python, data science, bioinformatics, etc.</li>
      <li>Databases: recommended sources to download protein data (i.e., sequences, structures, embeddings, (meta)genomes).</li>
      <li>Tutorials: tutorials for learning how to process and analyze protein science data.</li>
      <li>Selected papers: scientific articles I recommend.</li>
    </ol>
  </li>
</ol>


## Access to the slides

This course is composed of +800 slides, each containing image sources, citations, and recommended resources in the notes section. The slides were created in PowerPoint, so I recommend viewing them using that software. You can download the slides in the following two options:

* [Zenodo]()
* [Google Drive]()

This is intended to give you access to more information so you can explore the topics in greater depth. If you are a teacher and have adopted this material for your lectures, please let me know. I would love to hear how you improved the course and to know that more people are learning about protein science. However, if you identify someone who has fully or partially plagiarized this course AND is charging money to access it, I would appreciate it if you notified me.

## Course organization

![webinar](https://miangoar.github.io/images/teaching/lectures.png)

The theoretical lectures are numbered from 01 to 10 to facilitate understanding of the topics. For example, to discuss AlphaFold, it is necessary to know concepts from structural biology and deep learning. Below is a brief description of the lectures and their topics:


<ol>
  <li><strong><a href="https://www.youtube.com/watch?v=TU_LINK_AQUI">Basic computing concepts</a></strong>: how CPUs and GPUs work, as well as the essential software for data analysis.
    <ol type="a">
      <li>Where does your journey begin?</li>
      <li>Hardware
        <ul>
          <li>CPU</li>
          <li>GPU</li>
        </ul>
      </li>
      <li>Software
        <ul>
          <li>Linux/Bash and GitHub</li>
          <li>Python</li>
        </ul>
      </li>
    </ol>
  </li>

  <li><strong><a href="https://www.youtube.com/watch?v=TU_LINK_AQUI">Machine learning</a></strong>: what AI is and its subfields, the current capabilities of algorithms, and how a model is trained.
    <ol type="a">
      <li>Current state of AI</li>
      <li>How AI learns
        <ul>
          <li>Patterns</li>
          <li>Machine learning operations (MLOps)</li>
          <li>Learning paradigms</li>
        </ul>
      </li>
      <li>How to train a model
        <ul>
          <li>Data processing</li>
          <li>How to choose a model</li>
          <li>Training process</li>
        </ul>
      </li>
    </ol>
  </li>

  <li><strong><a href="https://www.youtube.com/watch?v=TU_LINK_AQUI">Deep learning</a></strong>: how neural networks work, the different types of neural networks, and the software used to work with them.
    <ol type="a">
      <li>Neural networks
        <ul>
          <li>Neurons</li>
          <li>Deep learning</li>
          <li>Loss functions</li>
          <li>Backpropagation</li>
          <li>Optimizers</li>
          <li>Architectures</li>
          <li>Explainability (why) and Interpretability (how)</li>
        </ul>
      </li>
      <li>Deep learning frameworks</li>
    </ol>
  </li>

  <li><strong><a href="https://www.youtube.com/watch?v=TU_LINK_AQUI">Transformers and language models</a></strong>: how Transformers and modern language models work.
    <ol type="a">
      <li>Language models</li>
      <li>Transformers
        <ul>
          <li>Original architecture</li>
          <li>BERT and GPT architectures</li>
          <li>Scaling laws</li>
          <li>Pre-training and post-training</li>
          <li>Reinforcement learning</li>
        </ul>
      </li>
      <li>Performance and generalization
        <ul>
          <li>Benchmark saturation</li>
          <li>Hype</li>
        </ul>
      </li>
      <li>How to work with LLMs
        <ul>
          <li>Optimization techniques (for GPU-poors like us)</li>
          <li>Hugging Face and Software 2.0</li>
        </ul>
      </li>
    </ol>
  </li>

  <li><strong><a href="https://www.youtube.com/watch?v=TU_LINK_AQUI">Protein structure</a></strong>: principles of structural biology and organization.
    <ol type="a">
      <li>Structural organization
        <ul>
          <li>Amino acids</li>
          <li>Secondary and tertiary structure</li>
          <li>Experimental workflow for structure determination</li>
          <li>Structure Viewers</li>
        </ul>
      </li>
      <li>Classifications
        <ul>
          <li>Folds and domains</li>
          <li>First classification schemes</li>
          <li>Similarity metrics</li>
          <li>Sequence and structural divergence</li>
          <li>Current classifications schemes</li>
        </ul>
      </li>
      <li>The shape of the protein universe
        <ul>
          <li>Uneven distribution</li>
          <li>Complex homologous relationships</li>
          <li>Switch folds</li>
        </ul>
      </li>
    </ol>
  </li>

  <li><strong><a href="https://www.youtube.com/watch?v=TU_LINK_AQUI">Protein function</a></strong>: how proteins adopt their structure and how function is regulated.
    <ol type="a">
      <li>Protein folding
        <ul>
          <li>Cellular environment</li>
          <li>Thermodynamics and conformational entropy</li>
        </ul>
      </li>
      <li>Protein function
        <ul>
          <li>Diffusion</li>
          <li>Molecular dynamics and energy functions</li>
          <li>Enzymes</li>
          <li>Functional annotation</li>
        </ul>
      </li>
      <li>Functional regulation
        <ul>
          <li>Allosterism</li>
          <li>Transcriptional regulation</li>
          <li>Post translational modifications</li>
          <li>Proteostasis and host physiology</li>
        </ul>
      </li>
    </ol>
  </li>

  <li><strong><a href="https://www.youtube.com/watch?v=TU_LINK_AQUI">Protein evolution</a></strong>: origin and diversification from simpler peptides.
    <ol type="a">
      <li>Levels of biological organization
        <ul>
          <li>Evolution across spatio-temporal scales</li>
          <li>Chemical evolution</li>
        </ul>
      </li>
      <li>Biological evolution
        <ul>
          <li>RNA world hypothesis and ribosome evolution</li>
          <li>Ancestral proteins</li>
          <li>Protein diversification</li>
        </ul>
      </li>
      <li>The sequence space
        <ul>
          <li>Mutations</li>
          <li>Robustness, evolvability and promiscuity</li>
          <li>Evolution of protein function</li>
        </ul>
      </li>
      <li>Epistasis: How interactions shape the evolution
        <ul>
          <li>Residue-residue and protein-protein interactions</li>
          <li>Randomness of mutations</li>
        </ul>
      </li>
    </ol>
  </li>

  <li><strong><a href="https://www.youtube.com/watch?v=TU_LINK_AQUI">AlphaFold</a></strong>: overview of AF2 and AF3 architectures and impact.
    <ol type="a">
      <li>The impact of AlphaFold
        <ul>
          <li>AlphaFoldmania</li>
          <li>Protein structure prediction before AlphaFold</li>
        </ul>
      </li>
      <li>AlphaFold</li>
      <li>AlphaFold2
        <ul>
          <li>Protein language models</li>
          <li>Architecture</li>
          <li>Post-AlphaFold2 era</li>
        </ul>
      </li>
      <li>AlphaFold3
        <ul>
          <li>Diffusion models for macromolecular modeling</li>
          <li>Architecture</li>
          <li>Post-AlphaFold3 era</li>
        </ul>
      </li>
    </ol>
  </li>

  <li><strong><a href="https://www.youtube.com/watch?v=TU_LINK_AQUI">AI-driven protein design</a></strong>: motivations and modern AI methods.
    <ol type="a">
      <li>Protein design
        <ul>
          <li>AI in the biotech market</li>
          <li>Advances from classical methods to AI-driven methods</li>
          <li>Basic considerations to increase the success of a design</li>
        </ul>
      </li>
      <li>Rational design
        <ul>
          <li>Classic experimental and bioinformatic approaches</li>
          <li>Macromolecular modeling and recombineering</li>
        </ul>
      </li>
      <li>Evolutionary design
        <ul>
          <li>Directed evolution, ancestral sequence reconstruction and consensus design</li>
        </ul>
      </li>
      <li>Representation learning
        <ul>
          <li>(Macro)Molecular representations</li>
          <li>Protein language models and ESMFold</li>
          <li>Explainability and interpretability of protein language models</li>
          <li>Scaling laws and multimodality in protein language models</li>
        </ul>
      </li>
      <li>Generative AI
        <ul>
          <li>Integration of multimodal data</li>
          <li>Sequence generation</li>
          <li>Generalization and fitness prediction with protein language models</li>
          <li>Inverse folding and ProteinMPNN</li>
          <li>Structure generation with diffusion models</li>
          <li>Model selection and computational scoring of candidates</li>
          <li>Model generalization and synthetic data</li>
        </ul>
      </li>
      <li>Summary</li>
    </ol>
  </li>

  <li><strong><a href="https://www.youtube.com/watch?v=TU_LINK_AQUI">Data and biases</a></strong>: relevant databases and data processing.
    <ol type="a">
      <li>Big data is Omics
        <ul>
          <li>Properties of a good dataset</li>
        </ul>
      </li>
      <li>Main datasets
        <ul>
          <li>PDB</li>
          <li>UniProt</li>
          <li>NCBI datasets</li>
          <li>Other interesting datasets</li>
        </ul>
      </li>
      <li>Data processing
        <ul>
          <li>Data cleaning in biology</li>
          <li>Basic tools for biological data manipulation</li>
          <li>Data splitting</li>
        </ul>
      </li>
      <li>Generalization in (protein) biology
        <ul>
          <li>Data leakage and other inherent issues</li>
        </ul>
      </li>
      <li>Biases in the data</li>
      <li>A roadmap for AI-driven protein design</li>
    </ol>
  </li>
</ol>

## How to support this project

Creating this course required a lot of time and work. If you found it useful and would like to support me financially, you can make a donation via PayPal. Donations can be of any amount, or of 12, 30, or 45 USD (suggestions based on students’ economic situations and the typical cost of courses like this). Click the image below if you want to donate.

[![Donate](https://miangoar.github.io/images/teaching/paypal.jpg)](https://www.paypal.com/donate/?hosted_button_id=AG42EZTZW9AJN)

If you do not have to much financial flexibility but would still like to express your gratitude, you can send me your comments by email:
* gamamiguelangel@gmail.com

Finally, I would appreciate it if you share this course with your colleagues who are interested in learning about AI-driven protein design.

## About me

I am Miguel Angel Gonzalez Arias. I am a Mexican biologist, and I love proteins, microbes, and computing. For more details about me, my socials and other contact information, please visit:
* [About me](https://miangoaren.github.io/talks/)

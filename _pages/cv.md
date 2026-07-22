---
layout: archive
# title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Artificial Intelligence \
Vrije University Amsterdam, Amsterdam, Netherlands, 2019.9 - present 
* M.S. in Information Science \
Institute of Scientific and Technical Information of China, Beijing, China, 2016.9 - 2019.1
* B.S. Library Science \
Northeast Normal University, Changchun, China, 2010.9 - 2014.7

Work experience
======
* PhD Researcher - AI Engineering & LLM Systems, 2019.09 - present
  * VU Amsterdam, Amsterdam, Netherlands
  * Developed applied AI systems for question answering, retrieval, and recommendation over scientific knowledge, covering problem definition, data preparation, model and retrieval design, evaluation, error analysis, and iterative improvement.
  * Developed FIRESPARQL, an LLM-based natural-language-to-SPARQL framework; fine-tuned Llama 3 8B with LoRA using Hugging Face and LLaMA-Factory, and built reproducible inference and evaluation pipelines for the SciQA Benchmark.
  * Built ontology-grounded RAG workflows using GPT-4, embedding-based retrieval, and structured prompts to generate competency questions across multiple domains.
  * Designed a property-guided subgraph retrieval framework combining semantic entity and property alignment, graph traversal, LLM-based filtering, and structured evidence selection for multi-hop knowledge graph question answering.
  * Engineered batch pipelines to execute and evaluate 2,600+ SPARQL queries on million-scale RDF data using Python, QLever, Virtuoso, Docker, and HPC/SLURM.
  * Built a scholarly paper recommendation pipeline over 100k+ papers, including parsing, preprocessing, embeddings, user profile generation, ranking, and evaluation.

* Visiting PhD Researcher, 2025.08 - 2025.10
  * Open University, United Kingdom
  * Worked on GraphRAG-related research, focusing on retrieval and reasoning over graph-structured knowledge.

* Data Analyst User Growth (Full-time Internship), 2018.9 - 2019.1
  * Beijing Didi Chuxing Technology Co., Ltd., Beijing, China 
  * Duties includes: 
      * Monitored and analyzed product data to identify trends and insights, optimizing user experience and supporting sales targets.
      * Collected, processed, and analyzed user behavior data from multiple channels to develop comprehensive user profiles.

* Data Analyst (Part-time Internship), 2018.3 - 2018.9
  * John Wiley & Sons, Inc, Beijing, China 
  * Duties included: 
      * Conducted comprehensive data analysis on Wiley journal database usage for all universities in China, providing insights into academic resource consumption.
      * Evaluated the cost-effectiveness of journal subscriptions, supporting data-driven decision-making for university libraries.
      * Identified key user behavior patterns and formulated strategies to optimize academic journal access and utilization.

* Library Assistant (Full time), 2014.7 - 2015.9
  * The Chinese University of Hong Kong, Shenzhen, China 
  * Duties included: 
      * Perform copy cataloging of bibliographic records to enhance discoverability and equity of access to materials in the collection. This is achieved by using the Library’s ILS, OCLC Connexion, and other online tools to identify, edit, and import bibliographic records using Dewey Decimal Classification (DDC), Library of Congress Authorities (such as LC Subject Headings) and Resource Description and Access (RDA) standards.
      * Maintain the accuracy of holdings/records in OCLC to support Interlibrary Loan service.
  
Skills
======
* Programming: Python, SQL, Pandas, Numpy, PyTorch, Scikit-learn, Gensim,
Transformers
* LLMs: RAG implementation using GPT Assistant and LlamaIndex
* Semantic web technologies: SPARQL, RDF, RDFS
* Graph databased: Neo4j, GraphDB
* Language: English, Mandarin, Cantonese, Dutch

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks and Posters
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
  
<!-- Service and leadership
======
* Currently signed in to 43 different slack teams -->

Awards
======
* 3rd place in AI and I Hackathon 2024 (Munich): Co-Creativity between Humans and
LLMs
* Post-graduate Academic Scholarship (2nd Class) , 2016-2018, by Institute of
Scientific and Technical Information of China, Beijing, China
* Undergraduate Academic Scholarship (2nd Class) , 2012-2014, by Northeast Normal
University, Changchun, China

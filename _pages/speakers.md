---
title:     byteMAL 2026 Keynotes
permalink: /speakers
layout:    default
speakers:
  - name: "Stefan Janssen"
    subtitle: Professor of Algorithmic Bioinformatics at Justus Liebig University Giessen 
    link: https://www.uni-giessen.de/de/fbz/fb08/Inst/algorithm-bioinformatik
    link_text: Stefan Janssen's Website
    image: stefan-janssen.jpg
    bio: Stefan Janssen is an expert in the development of algorithms for biological data analysis, with a primary focus on microbiome research. Since August 2019, he has served as a Professor for Algorithmic Bioinformatics at Justus Liebig University Giessen (JLU), where he leads the "JLab" research group. His research employs systems biology and machine learning to investigate the rich interplay between the microbiome and its host organisms. Dr. Janssen's group focuses on the development of tools to process and analyze terabyte-scale microbiome datasets, as well as algorithm design for sequential data based on dynamic programming. Previously, he worked as a postdoctoral fellow in Rob Knight’s lab at the University of California San Diego (UCSD), Arndt Borkhardt’s Lab at University Hospital Düsseldorf (UKD), and Alice McHardy’s group at the German Center for Infection Research (DZIF). 
  - name: "Christian Lieven"
    subtitle: "Co-founder and CTO of Unseen Bio"
    link: 
    link_text: 
    image: christian-lieven.jpg
    bio: "Christian is co-founder and CTO of Unseen Bio. With a PhD in systems biology and experience in design, management, and software development, he combines research and product development to explore the human and animal microbiomes. He is passionate about translating scientific findings into user-friendly technologies—from data-based analysis platforms and automated quality assurance to intuitive web apps for professionals and end users. Using design thinking, agile methods, and modern machine learning models, he develops innovative solutions for research and bioproduction. He leads an interdisciplinary team and is working to integrate microbiome analyses into the everyday health practice of Europe in the future.<br><br><strong>Seeing the Unseen</strong><br>In my talk I'll present who the company is, what we do, and how I've made my way from Uni to Unseen. I'll discuss some of the challenges we've overcome and learnings we've made along the way."
  - name: "Jeyashree Krishnan"
    subtitle: "Alumna, Senior Machine Learning Engineer at Siemens AG"
    link: "https://www.jeyashreekrishnan.com/"
    link_text: "Website"
    image: 
    bio: "Jeyashree Krishnan is a Senior Machine Learning Engineer at Siemens AG. Her work focuses on building and operationalizing scalable machine learning services, with an emphasis on foundation models and time series forecasting."
  - name: "Maria Fyta"
    subtitle: "Head of the Computational Biotechnology Group"
    link: 
    link_text: 
    image: maria_fyta.png
    bio: "The Computational Biotechnology group uses computer simulations at various spatiotemporal scales in order to study the interface between biomolecules, materials, and solvent. These simulations provide a fundamental understanding of the specific interactions at such interfaces towards targeted applications in biosensing and selective design of biofunctional templates. In order to accelerate the simulations, assist this design, and interpret experimental data, Machine Learning workflows are applied and further developed.<br><br><strong>Next generation sequencing techniques: nanopore read-out and base-calling</strong><br>Next generation sequencing techniques target high-throughput, accurate, efficient and real-time sequencing of the genome. Relevant devices have reached the market, still challenges exist in relation to either the accuracy or the read-length processed. At the same time, the quest for sequencing the whole genome has shifted to the aim of detecting post-translational modifications in proteins. These are involved in the development of diseases, thus being able to accurately detect them would add a solid stone on the pathway towards the realisation of personalised medicine. In the discussion, focus will be laid on nanopore sequencing, and the main aspects that may control the accuracy in the detection of DNA and proteins. For this, the processing of the relevant recordings, known-as nanopore read-out or base-calling, is key and relies on the efficient implementation of bioinformatics and Machine Learning tools. We will discuss the progress in this field, the challenges, and the societal impact."
nonspeakers:  
  - name: "Dr. Maximilian von Datenrausch"
    subtitle: "Self-Proclaimed Chief Quantum Snack Analyst"    
    link: 
    link_text: "Totally not a Lab"
    image: "A.png"
    bio: Dr. Maximilian von Datenrausch is absolutely not a real scientist, despite his impressive-sounding title. His “research” focuses on understanding why computer simulations always run perfectly until someone is watching. He famously developed the groundbreaking <em>Snack-Driven Workflow Optimization Theory</em>, which proposes that scientific productivity increases by 73% when cookies are within arm’s reach. <br><br> Dr. von Datenrausch claims to have completed a “transdimensional internship” at the Institute for Hypothetical Excellence (a place that does not exist), where he allegedly worked on quantum banana probabilistics — a field he invented to justify buying a very expensive calculator.<br><br> His work is entirely fictional, but he remains committed to collaborating with real researchers by providing emotional support, unsolicited advice, and an unlimited supply of memes.
  - name: "Prof. Dr. Nebula Starlingen"
    subtitle: "Intergalactic Visiting Scholar (unverified)"
    link: "link"
    link_text: "Nebula's Nonexistent Lab"
    image: "B.png"
    bio: Prof. Dr. Nebula Starlingen claims to have arrived from the Andromeda Galaxy to  understand Earth’s strange research funding system.” Although no university officially acknowledges her, she insists she holds a chair in <em>Astro-Bureaucracy</em>, specializing in the navigation of grant applications across multiple dimensions.<br><br>Her notable publications include “Dark Matter and Even Darker Reviewer Comments” and “Why Earth Scientists Keep Rewriting the Same Paper.” She frequently with humans by observing them through a telescope, 
          which she insists counts as “fieldwork.”
  - name: "Günther “Günni” Algorithmus"
    subtitle: "Freelance Data Enthusiast & Full-Time Overthinker"
    link: "link"
    link_text: "Günni's Sock Drawer Lab"
    image: "C.png"
    bio:  Günther Algorithmus has no formal academic background but compensates with excessive confidence. He became famous (in his own living room) for developing the “Günni Model,” a predictive algorithm that attempts to forecast when his cat will jump on the keyboard. Unfortunately, the model has a consistent accuracy of exactly 0%.<br><br>Günni describes his research approach as “chaos-informed and snack-fueled.” He regularly appears at local cafés, where he gives unsolicited TED-Talk–style explanations about why spreadsheets are “the true poetry of our time.” Although he has no lab, he does maintain a very organized sock drawer, which he calls his “data center.”
 
---
<!-- class="card-img-top mx-auto mt-3" -->

<h2 class="mb-4"><b>Keynote speakers</b></h2>
{% for item in page.speakers %}
<div class="card mb-3" style="max-width: 960px;">
  <div class="row no-gutters">
    <div class="col-md-4 d-flex align-items-start p-3">
      {% if item.image %}
      <img src="{{site.baseurl}}/images/Speakers/{{item.image}}"       
      class="card-img mt-3" alt="Speaker Image">
      {% else %}
      <img src="{{site.baseurl}}/images/Speakers/default_speaker_picture.png" class="card-img rounded-lg" alt="Speaker Image">
      {% endif %}
    </div>
    <div class="col-md-8 p-3">
      <div class="card-body">
        <h5 class="card-title">{{item.name}}</h5>
        {% if item.subtitle %}
          <p class="card-text font-weight-bold">{{item.subtitle}}</p>
        {% endif %}

        <p class="card-text">{{item.bio}}</p>

        {%if item.link %}
        <button type="button" class="btn bg-main">
          <a class="text-white" href="{{item.link}}">{{item.link_text}}</a>
        </button>
        {% endif %}
      </div>
    </div>
  </div>
</div>
{% endfor %}

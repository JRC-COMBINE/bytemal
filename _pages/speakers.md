---
title:     ByteMAL 2026 Keynotes
permalink: /speakers
layout:    default
speakers:
  - name: "Stefan Janssen"
    link: 
    link_text: 
    image: 
    bio: 
  - name: "Christian Lieven"
    subtitle: "Industry Speaker"    
    link: 
    link_text: 
    image: 
    bio: 
  - name: "Jeyashree Krishnan"
    subtitle: "Alumna Speaker"    
    link: "https://www.jeyashreekrishnan.com/"
    link_text: "Website"
    image: 
  - name: "TBA"
    subtitle: 
    link: 
    link_text: 
    image: 
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

<h2 class="mb-4"><b>Keynote speakers</b></h2>
{% for item in page.speakers %}
<div class="card mb-3" style="max-width: 960px;">
  <div class="row no-gutters">
    <div class="col-md-4 d-flex align-items-center">    
      {% if item.image %}
      <img src="{{site.baseurl}}/images/Speakers/{{item.image}}" class="card-img rounded-lg" alt="Speaker Image">
      {% else %}
      <img src="{{site.baseurl}}/images/Speakers/default_speaker_picture.png" class="card-img rounded-lg" alt="Speaker Image">
      {% endif %}
    </div>
    <div class="col-md-8">
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

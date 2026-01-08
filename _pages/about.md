---
title: "About ByteMAL"
permalink: /about
layout: default
variables:
  -link: &compbio "https://www.ukaachen.de/kliniken-institute/joint-research-center-for-computational-biomedicine/lehre/institute-for-computational-biomedicine/"
  -link: &disease "https://www.ukaachen.de/kliniken-institute/joint-research-center-for-computational-biomedicine/lehre/institute-for-computational-biomedicine-and-disease-modelling-with-focus-on-phase-transitions-between-phenotypes/"
  -link: $micro "https://www.iamb.rwth-aachen.de/cms/iamb/das-institut/team/gruppe-blank/postdoc/~bhhocr/karan-kumar/?allou=1&lidx=1"
organizers:  
  - name: "Jonas Kupschus"
    affiliation: "Computational Biomedicine"
    affiliation_link: *compbio 
    image: "default.png"
  - name: "Jonas Wolber"
    affiliation: "Computational Biomedicine"
    image: "default.png"
    affiliation_link: *compbio 
  - name: "Marc-Daniel Hagel"
    affiliation: "Computational Biomedicine"
    image: "mahagel.jpg"
    affiliation_link: *compbio 
  - name: "Qiuje Wang"
    affiliation: "Computational Biomedicine and Disease modelling"
    affiliation_link: *disease 
    image: "qiwang.jpg"
  - name: "Dr. Karan Kumar"
    affiliation: "Institute of Applied Microbiology"
    affiliation_link: *micro
    image: "kakumar.png"
  - name: "Titania Sugiarto"
    affiliation: "Institute of Applied Microbiology"
    affiliation_link: *micro
    image: "default.png"
  - name: "Younes Müller"
    affiliation: "Computational Biomedicine"
    affiliation_link: *compbio
    image: "yomueller.jpg"

---

<div class="row">

  <div class="col-sm-12 px-3" style="text-align: justify">
  <h2 id="about-the-bytemal-conference"><b>About byteMAL</b></h2>
  <p><strong>ByteMAL</strong> is a conference created by and for early-career researchers in the fields of bioinformatics and systems biomedicine, 
  and aims to provide a networking platform for knowledge and expertise exchange across borders. All are welcome to <a href="{{site.baseurl}}/register">attend and present</a> at byteMAL, but especially PhD candidates, post-docs, and students (master’s and bachelor’s).</p>
  <p>We aim to vitalize communication amongst researchers from the Netherlands, Belgium, and Germany. ByteMAL has been hosted alternately by the Universities of Maastricht, Aachen, and Liège. </p>
  <p>As researchers in related fields in neighboring regions we are excited to widen our perspectives by creating the opportunity to discuss methods, tools, challenges and successes with people of similar mindset. Participants will have the opportunity to be inspired by our interesting <a href="{{site.baseurl}}/speakers">keynote speakers</a>, present their own work, and discuss ideas, tools and approaches with each other.</p>

  <br>
  <p style="text-align: justify">
    <h2><b>Local Organizing Committee</b></h2>
    <h3><b>Preliminary List</b></h3>
    
    <div class="row">
  {% for item in page.organizers %}

  <div class="col-12 col-sm-6 col-md-4 col-lg-3 mb-4">
    <div class="card h-100 text-center">
      <img
        class="card-img-top mx-auto mt-3"
        src="{{site.baseurl}}/images/committee/{{item.image}}"
        alt="{{item.name}} avatar"
        style="width: 128px; max-height: 800px; object-fit: cover"
      />
      <div class="card-body">
        <h5 class="card-title mb-1">{{item.name}}</h5>
        <p class="card-text text-muted">
          {% if item.affiliation_link %}
          <a href="{{item.affiliation_link}}">{{item.affiliation}}</a>
          {% else %}
          {{item.affiliation}}
          {% endif %}     
        </p>
      </div>
    </div>
  </div>
  {% endfor %}
</div>

  </p>
  <br>
  <p style="text-align: justify">
    <h2><b>Contact</b></h2>
    If you have any questions, feel free to contact us via e-mail: <a href = "mailto:byteMALevents@gmail.com">byteMALevents@gmail.com</a>. You can also check our <a href="https://bytemal.github.io/">main website</a> for general information and links to previous editions of the conference.
  </p>
  
</div>

  </div>






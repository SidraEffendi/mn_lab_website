---
---

# MN Lab Website

An engaging 1-3 sentence description of your lab.

{% include section.html %}

## Highlights

{% capture text %}

Our publications represent the culmination of rigorous scientific inquiry, innovative thinking, and collaborative effort aimed at addressing key challenges and advancing knowledge in Human-Computer Interaction (HCI).

{%
  include button.html
  link="research"
  text="See our publications"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="research"
  title="Our Publications"
  text=text
%}

{% capture text %}

At the heart of our research philosophy lies a passion for humanitarianism, a dedication to integrity, and a belief in the power of collaboration. We actively foster an inclusive and supportive environment that nurtures creativity, critical thinking, and scientific excellence.

{%
  include button.html
  link="projects"
  text="Browse our Research projects"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="projects"
  title="Our Research"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Whether you’re a prospective collaborator, a student interested in joining our team, or simply curious about the individuals behind our research, we invite you to get to know the members of MN Research Lab and discover the passion, expertise, and dedication that drive our collective efforts forward.

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/photo.jpg"
  link="team"
  title="Our Team"
  text=text
%}

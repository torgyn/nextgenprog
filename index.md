# Next Generation Programmers (NGP) 

We are a non-profit educational outreach initative 
aimed to inspire young talent from rural schools in developing countries to pursue programming.

<p align="center"> 
  <img src="https://github.com/torgyn/nextgenprog/blob/main/ngpLogo.png?raw=true" alt="NGP logo" width="256">
</p> 

[2021 Participant Survey](/nextgenprog/resources/2021_survey/)


# Contents:
[App Development](/nextgenprog/app_development/)

[Scratch](/nextgenprog/scratch/)

Web Design
[Markdown](/nextgenprog/web_design/markdown)

Resources for self-learning
[Useful links](/nextgenprog/remote_learning/)

2021 Student projects
[Useful links](/nextgenprog/student_projects/)

2021 volunteers and speakers
[Useful links](/nextgenprog/volunteers/)


<nav>
  {% for item in site._data.navigation %}
    <a href="{{ item.link }}" {% if page.url == item.link %}style="color: red;"{% endif %}>
      {{ item.name }}
    </a>
  {% endfor %}
</nav>

**Disclaimer:** This website is under constant modification.
If you find something isn't right, then we might be implementing changes in the back-end.
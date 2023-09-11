---
# Any further Jekyll instructions here
# Can use markdown OR raw html!
---
<body class="background-image">
    <div align="center" style="background: rgba(0, 0, 0, 0.5);">
        <h1 class="project-name" style="color: white;">{{ page.title | default: site.title | default: site.github.repository_name }}</h1>
        <h2 class="project-tagline" style="color: white;">{{ page.description | default: site.description | default: site.github.project_tagline }}</h2>
        <img src="./assets/img/wildrate.png" height="100" />    
    </div>
</body>

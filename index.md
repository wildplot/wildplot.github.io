---
# Any further Jekyll instructions here
# Can use markdown OR raw html!
---
<body class="background-image">
    <div align="center" style="color: white;">
        <h1 class="project-name">{{ page.title | default: site.title | default: site.github.repository_name }}</h1>
        <h2 class="project-tagline">{{ page.description | default: site.description | default: site.github.project_tagline }}</h2>
    </div>
</body>

---
layout: page-with-side-nav
title: Documenten StUF-ZKN
folder_files:
  - title: Extra-elementen_voor_zkn0310.zip
    path: documenten/Extra-elementen_voor_zkn0310.zip
    group: 310
  - title: KeuzenVerStUFfing_RGBZ.pdf
    path: KeuzenVerStUFfing_RGBZ.pdf
    group: 310
  - title: Zkn0310_20211208_patch32.zip
    path: documenten/Zkn0310_20211208_patch32.zip
    group: 310
---

# Documentatie

## StUF-ZKN 3.10

<ul>
	{% for i in page.folder_files %}
		{% if i.group == 310 %} 
			<li>
			  <a href="{{ i.path | base_url }}">
				{{ i.title }}
			  </a>
			</li>
		{% endif %} 
	{% endfor %}
</ul>


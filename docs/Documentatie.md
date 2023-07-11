---
layout: page-with-side-nav
title: Documenten StUF-ZKN
folder_files:
  - title: Extra-elementen_voor_zkn0310.zip
    path: documenten/Extra-elementen_voor_zkn0310.zip
    group: 310
    versie: 3-12-2021
    status: Definitief
    omschrijving: 
  - title: KeuzenVerStUFfing_RGBZ.pdf
    path: KeuzenVerStUFfing_RGBZ.pdf
    group: 310
    versie: 1.15
    status: Definitief
    omschrijving: 
  - title: Zkn0310_20211208_patch32.zip
    path: documenten/Zkn0310_20211208_patch32.zip
    group: 310
    versie: 32
    status: Definitief
    omschrijving: Bevat alle documentatie, schema's en WSDL's behorende bij patch 32 van StUF-ZKN 3.10 inclusief alle bij de StUF 3.01 onderlaag en StUF-BG 3.10 horende zaken. Tevens bevat de zip het overzicht van de er in verwerkte onderhoudsverzoeken en de lijst met de bij StUF-ZKN 3.10 horende extraElementen.
---

# Documentatie

## StUF-ZKN 3.10

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th>
		</tr>
	</thead>
	<tbody>
		{% for i in page.folder_files %}
			{% if i.group == 310 %} 
				<tr>
					<td>
					  <a href="{{ i.path | base_url }}">
						{{ i.title }}
					  </a>
					</td>
					<td>{{ i.versie }}</td>
					<td>{{ i.status }}</td>
					<td>{{ i.omschrijving }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>


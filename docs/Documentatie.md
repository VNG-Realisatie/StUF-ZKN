---
layout: page-with-side-nav
title: Documentatie StUF-ZKN
folder_files:
  - title: Zkn0310 20250321 patch33 (zip)
    path: documenten/Zkn0310_20250321_patch33.zip
    group: 310
    versie: 33
    status: Definitief
    omschrijving: Patch i.v.m. de wens Tijdelijke verblijfsadressen van niet ingezetene te kunnen uitwisselen. Bevat alle documentatie, schema's en WSDL's behorende bij patch 33 van StUF-ZKN 3.10 inclusief alle bij de StUF 3.01 onderlaag en StUF-BG 3.10 horende zaken. Tevens bevat de zip het overzicht van de er in verwerkte onderhoudsverzoeken en de lijst met de bij StUF-ZKN 3.10 horende extraElementen.
    datum: 20250321
  - title: KeuzenVerStUFfing RGBZ (pdf)
    path: KeuzenVerStUFfing_RGBZ.pdf
    group: 310
    versie: 1.15
    status: Definitief
    omschrijving: 
    datum: 20170701
  - title: Extra elementen voor zkn0310 (zip)
    path: documenten/Extra-elementen_voor_zkn0310.zip
    group: 310
    versie: 21-3-2025
    status: Definitief
    omschrijving: Bevat alle extraElementen t/m patch 33.
    datum: 20250321
---

# Documentatie

## StUF-ZKN 3.10

<table>
	<thead>
		<tr>
			<th>Document</th><th>Versie</th><th>Beheerstatus</th><th>Beschrijving</th><th>Versiedatum</th>
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
					<td>{{ i.datum }}</td>
				</tr>
			{% endif %} 
		{% endfor %}
	</tbody>
</table>


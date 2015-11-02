---
layout: page
title: Global Biodiversity Monitoring
mainpage: false
subpage: true
weight: 1
# permalink: /events/
---

### Future Earth Symposium "Global Biodiversity Monitoring" _Yale, May 2015_.

#### Program
The full program is available [here](GlobalMonitoringSymposium_Program_Yale2015.pdf)  

#### Participants
The full list of  participants is available [here](GlobalMonitoringSymposium_Participants_Yale2015.xlsx)  

#### Presentations

* Day 1 - Morning
  * [1 Ojima_Future_Earth.pdf]
  * [2 Cooper_CBD.pdf]
  * [3 McOwen_Indicators.pdf]
  * [4 Spehn_IPBES.pdf]
  * [5 Beissinger_SpeciesAbundance.pdf]
  * [6 Cardinale_local biodiversity.pdf]
  * [7 Ferrier_biodiversity Monitoring.pdf]
  * [8 Woodward_food webs.pdf]
  * [9 Jetz_Map_of_Life.pdf]
* Day 1 - Afternoon
  * [1 Akcakaya-ThreatenedSpecies.pdf]
  * [2 BÖHNING_Functional Biodiv.pdf]
  * [3 Schimel_BD from Space.pdf]
  * [4 Schaepman_remoteSensing.pdf]
  * [5 Turner_NASA.pdf]
  * [6 Gill_GEOBON.pdf]
  * [7 Yahara_APBON.pdf]
  * [8 Anderson-Teixeira_CTFS-ForestGEO.pdf]
  * [9 Ahumada_TEAM.pdf]
  * [10 Basset_Arthropod CTFS_ForestGEO.pdf]
  * [11 Körner_Mountains.pdf]
  * [12 Kattge_TRY.pdf]
* Day 2 - Morning
  * [1 Ojima_Future Earth.pdf]
  * [2 ellis_GLP.pdf]
  * [3 Mcphearson_Urban.pdf]
  * [4 Broome_CODATA.pdf]
  * [5 bioGENESIS.pdf]
  * [6 bioDISCOVERY.pdf]
  * [7 IMBER.pdf]
  * [8 OBIS.pdf]
  * [9 MBON.pdf]
  * [10 Durance_Freshwater.pdf]
  * [11 Domisch_SpatialModellingFreshwater.pdf]
  * [12 Guralnick_MOLDataUpload.pdf]


{% assign files = site.static_files %}
{% for file in files %}
    {% if file.extname == '.pdf' %}
        {% assign filepart = file.path | split:"/" %}
[{{ filepart | last }}]: {{ file.path }}
    {% endif %}
{% endfor %}

---
layout: page
title: Group
mainpage: true
weight: 3
permalink: /group/
---

## Steering Committee ##

[**Walter Jetz**](http://jetzlab.yale.edu/){: target="blank" }  
Yale University  
[<span class="glyphicon glyphicon-envelope" aria-hidden="true"></span> Email](mailto:walter.jetz@yale.edu)

[**Eva Spehn**](https://botanik.unibas.ch/en/staff/profile/person/spehn/){: target="blank" }  
Universität Basel   
[<span class="glyphicon glyphicon-envelope" aria-hidden="true"></span> Email](mailto:eva.spehn@scnat.ch)

[**Christopher Trisos**](https://www.sesync.org/users/ctrisos){: target="blank" }  
SESYNC / Yale    
[<span class="glyphicon glyphicon-envelope" aria-hidden="true"></span> Email](mailto:ctrisos@sesync.org)

[Paul Leadley](http://www.ese.u-psud.fr/article360.html?lang=en){: target="blank" }  
Université Paris-Sud  

[Guy Woodward](http://www.imperial.ac.uk/people/guy.woodward){: target="blank" }  
Imperial College  

[Dave Schimel](https://science.jpl.nasa.gov/people/Schimel/){: target="blank" }  
JPL Science - NASA  

[Simon Ferrier](http://people.csiro.au/F/S/Simon-Ferrier){: target="blank" }  
CSIRO  

[Henrique Pereira](https://www.idiv.de/the-centre/employees/details/eshow/pereira-henrique-miguel.html){: target="blank" }  
iDiv  

[Bradley Cardinale](http://snre.umich.edu/cardinale/){: target="blank" }  
University of Michigan

## Participants ##

First name | Last name | Affiliation
-- | -- | -- | --  {% for member in site.data.participants2015 %}
{{ member.first }} | **{{ member.last }}** | {{ member.affiliation }}{% endfor %}

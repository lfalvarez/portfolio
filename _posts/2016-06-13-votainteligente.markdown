---
layout: post
title:  "VotaInteligente Chile 2016 - 2017"
date:   2016-06-13 10:51:47 +0530
categories: featured
img: vota.png
year: 2016 - 2017
category: Chile
country: Chile
organization: Fundación Ciudadano Intelingente
role:
colaboration:
    - name: TECHO
      url: http://www.techo.org/paises/chile/
    - name: Junto Al Barrio
      url: http://www.juntoalbarrio.cl/
    - name: Iguales
      url: https://www.iguales.cl/
    - name: TodoMejora
      url: https://todomejora.org/
people: [Catalina Margozzini, Margarita Maira, Gabriel Castillo, Bastián Torres]
responsabilities: Lead developer
one_line_description: Influence the proposals of the candidates.
featured: true
links:
    - url: http://votainteligente.cl
      description: The running version
      type: link
    - url: github.com/ciudadanointeligente/votainteligente-portal-electoral]
      description: Repo in github
      type: github
---

[VotaInteligente](http://votainteligente.cl) is the electoral platfrom from [Fundación Ciudadano Inteligente](http://ciudadanointeligente.org) and it aims to provide as much information about the candidates, their political positions, their background, etc. And this is the description of the last edition that was designed to be online for the [municipal elections in Chile](https://en.wikipedia.org/wiki/Elections_in_Chile#Municipal_elections).

Context
------
The Corruption Perception Index in Chile is among the highest in Latin America (23rd), but in the last couple of years, there have been a series of corruption scandals that have undermined the trust in politicians and politics in general.

We then understood that there was a flaw in our previous versions: We wanted to inform, but the information itself didn't seem to tackle the participation problems or the mistrust in politics. Something needed to change.

My role
-------
As part of the team that envisioned the changes that this year's electoral platform was going to have, I designed experiments (in streets, demonstrations, with previous candidates and authorities) as well as analyzed results of them. Those results led us to propose what later became "citizen's proposals". I also lead the development of the project always adapting to changes in the political and social context and acting as a catalyst for the design and development team and the social sciences team.

Features
--------
It allowed citizens to upload proposals related to their communities, and after a moderation process the candidates were notified of that proposal and could commit to those proposals publicly.

<div class="thumbnail with-caption">
  <img src='/images/vota2.png'>
  <p>Candidates committing with a proposal</p>
</div>

On the other hand, candidates could express their political positions on different issues. That allowed citizens to compare candidates, but also compare themselves, that comparison is called 'Political Soulmate'.

<div class="thumbnail with-caption">
  <img src='/images/vota5.png'>
  <p>Result of the 'Political Soulmate'</p>
</div>

Preliminary results
-------
There were 14,000 candidates in total, of those 1,200 uploaded their information to VotaInteligente.


The citizens uploaded over 3,000 proposals, of which a bit less than 600 had at least one candidate committing to them.

The number of unique visitors was a bit over 3% of all the voters in the elections.

The impact research is still being assembled and this are just preliminary results.

Going technical
-------
The code of VotaInteligente started sometime around 4 years ago, it was only intended to provide information about the candidates, but as the years went by VotaInteligente and I started to evolve. I was influenced by the concepts of [Clean Architecture](https://8thlight.com/blog/uncle-bob/2012/08/13/the-clean-architecture.html) and based on that I refactored quite a bit of the code.

If you are more interested you can check all the code and the history at the [GitHub repo](https://github.com/ciudadanointeligente/votainteligente-portal-electoral/).

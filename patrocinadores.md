---
layout: page
title: Patrocinadores
permalink: /patrocinadores/
---

<p>
  Nossos encontros presenciais são possíveis graças a empresas, pessoas e instituições que nos apoiam fornecendo um local com boa infraestrutura, localização de fácil acesso e coffee-break para os participantes.
</p>

<p>
  Ruby CWB agradece a todas as pessoas e empresas que nos apoiaram de alguma forma.
</p>

<p>
  A seguir uma lista de empresas e instituições que já nos ajudaram em encontros passados.
</p>

<ul class="grid">
{% for item in site.data.sponsors %}
  <li>
    <a href="{{ item.url }}" target="_blank">
      <img width="150" src="/assets/images{{ item.logo.url }}" title="{{ item.name }}">
    </a>
  </li>
{% endfor %}
</ul>

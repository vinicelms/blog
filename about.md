---
layout: page
title: About
share: false
---

# Este projeto

É um projeto para registar o conhecimento que adquiro/adquiri. Sem prentensões de ganhar notoriedade ou ter grande visibilidade. Com dados registrados em diversas fontes, como Gists, Evernote pessoal ou scripts para resolver problemas pessoais, a intenção é centralizar tudo.

Acredito em informação aberta, então muito pode ser compartilhado, desde que anonimizado. Já que tenho bastante coisa anotada, agora o desafio é pensar neste conhecimento compartilhado.

O simples para mim, pode ser complexo para outros e o inverso também é verdadeiro. Então não compreenda este projeto como formação ou nível de conhecimento, apenas usufrua daquilo que precisar, da mesma forma que o estou fazzendo com este projeto.

# Sobre mim

Me chamo Vinicius Celms, comecei a me aprofundar na vida de tecnologia com 13 anos. Comecei aprendendo HTML e CSS, passando por tempo depois para Javascript. Trabalho efetivamente com tecnologia desde 2007. Pretendo continuar trabalhando e aprendendo a cada dia.

Me formei em Análise e Desenvolvimento de Sistemas, por gostar muito de programar. Há algum tempo me deparei com a área de infraestrutura e administração de sistemas, que gostei muito. Por ser exposto a cultura ágil, notei que poderia integrar programação e infraestrutura, intensificando a cultura DevOps.

<div class="read-more">
<div class="author-share">
  <div class="author-container">
    <img class="author-img" src="{{site.url}}/{{site.owner.avatar}}" alt="{{site.owner.name}}" />
    <div class="author-bio">{{site.owner.bio}}</div>
  </div>
  <ul class="list-inline social-buttons" style="text-align: center">
    {% for network in site.social %}
      <li><a href="{{ network.url }}" target="_blank"><i class="fa fa-{{ network.title }} fa-fw"></i></a></li>
    {% endfor %}
  </ul>
</div>
</div>
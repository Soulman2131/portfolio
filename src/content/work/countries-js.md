---
title: En apprendre sur les pays du monde
publishDate: 2023-12-03 12:00:00
img: /assets/collection/countries-js.png
img_alt: Les pays du monde entier
description: |
  Je développe une application qui fournit des informations sur les pays du monde. On envoie une requête en tapant le nom d'un pays sur la barre de recherche. La réponse nous donne le drapeau du pays mais également des informations sur celui-ci comme la capitale, la population et le nombre d'habitants. On peut également récupérer la réponse dans l'ordre croissant, décroissant ou alphabétique.
tags:
  - HMTL
  - CSS
  - Javascript
---

#### Aspects Techniques

- DOM Manipulation.
- API Fetch.
- Les conditions if/else.

#### Liens

<ul class="liens__list" > 
<li class="liens__item"> <a href="https://countries-gv3kdwi0u-soulman2131.vercel.app/" target="_blank" class="liens__link" > Ouvrir le site </a> </li>
<li class="liens__item"> <a href="https://psychic-fiesta-jj59565g6vx3j6r9.github.dev/" target="_blank" class="liens__link"> Ouvrir avec Codespace </a></li>
</ul>

  <style>
    .liens__list {
      display:flex; justify-content: left; align-items: center;
      list-style: none; gap: 20px;  

    }
    
    .liens__link {
      display: block;
       background: rgba(0, 0, 255, 0.8);
      color: white;
      padding: 10px;
      border-radius: 10px;
      text-decoration: none;
      transform: scale(.9);
      transition: all .2s;
    }
    .liens__link:hover {
      background: rgb(61, 4, 249);
      transform: translateY(3px) scale(1);
      color: black;
      
    }

  </style>

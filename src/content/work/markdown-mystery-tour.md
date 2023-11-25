---
title: Jeu de bulles
publishDate: 2023-11-24 16:00:00
img: /assets/collection/bulles.png
img_alt: Jeu de bulles
description: |
  Je développe un jeu de bulles. Le principe est de les éclater à l'aide de la souris. A chaque éclatement, on gagne un point.
tags:
  - React
  - HTML
  - CSS
  - Javascript
  - Dockerfile
---

#### Aspects Techniques

Concept de base de Vanilla Javascript :

- DOM Manipulation.
- SetInterval vs setTimeOut.

#### Liens

<ul class="liens__list" > 
<li class="liens__item"> <a href="https://bulles.netlify.app/" target="_blank" class="liens__link" > Ouvrir le site </a> </li>
<li class="liens__item"> <a href="https://symmetrical-capybara-979w9v9xvwr3pgg.github.dev/" target="_blank" class="liens__link"> Ouvrir avec CodeSpaces </a></li>
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

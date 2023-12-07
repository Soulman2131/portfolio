---
title: La liste des utilisateurs
publishDate: 2023-11-29 11:00:00
img: /assets/collection/randomuser.png
img_alt: La liste des utilisateurs
description: |
  Je liste un groupe de 24 utilisateurs à l'aide de l'API : 
    Random user generator.
tags:
  - HTML
  - CSS
  - Javascript
---

#### Aspects Techniques

Concept de base de Vanilla Javascript :

- DOM Manipulation.
- Constructeur Date (new Date, date.parse ).
- Les fonctions.

#### Liens

<ul class="liens__list" > 
<li class="liens__item"> <a href="https://codesandbox.io/p/devbox/randomuser-tyh27w?file=%2Fsrc%2Fstyles.css%3A64%2C22" target="_blank" class="liens__link" > Ouvrir avec CodeSandBox </a> </li>
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

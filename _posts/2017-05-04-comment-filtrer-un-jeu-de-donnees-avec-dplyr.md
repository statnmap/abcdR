---
ID: 3318
post_title: 'Comment filtrer un jeu de données avec dplyr ? : filter()'
author: colin
post_excerpt: ""
layout: post
permalink: >
  https://abcdr.thinkr.fr/comment-filtrer-un-jeu-de-donnees-avec-dplyr/
published: true
post_date: 2017-05-04 19:55:49
---
<p>Avec ce package du tidyverse, vous pouvez <strong>filtrer votre jeu de données pour ne retenir que les valeurs qui vous intéressent</strong>, grâce à la fonction <em>filter()</em>.</p><p>Cette fonction prend en paramètres votre objet contenant un tableau de données, puis une ou plusieurs variable(s) avec leurs filtres. Vous pouvez utiliser tous les opérateurs classiques (==, !=, &gt;, &lt;, etc.)</p><p> <pre>data(women)<br />women %&gt;%<br /> filter(height == 59)<br />women %&gt;%<br /> filter(height &gt; 59 &amp; weight &lt; 139)</pre> </p><p>Vous pouvez également "piper" vos filtres. Utile pour une meilleure lisibilité, si vous voulez combiner beaucoup de conditions (mais vous aurez plus de ligne  :</p><p> <pre>women %&gt;%<br /> filter(height &gt; 59) %&gt;%<br /> filter(weight &lt; 139)</pre> </p>
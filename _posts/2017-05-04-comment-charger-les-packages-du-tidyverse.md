---
ID: 3310
post_title: >
  Comment charger les packages du
  tidyverse ?
author: colin
post_excerpt: ""
layout: post
permalink: >
  https://abcdr.thinkr.fr/comment-charger-les-packages-du-tidyverse/
published: true
post_date: 2017-05-04 20:01:50
---
<p>Le tidyverse fait référence à l’<strong>ensemble des packages qui partagent la philosophie « tidy »</strong>, et qui ont été pensés pour fonctionner les uns avec les autres.</p><p>Pour installer la version stable depuis le CRAN :</p><p> <pre>install.packages("tidyverse")</pre> </p><p>Quant à la version en développement, vous pouvez l'installer avec : </p><p> <pre>devtools::install_github("hadley/tidyverse")</pre> </p><p>Ensuite, vous pouvez charger les différents packages, en utilisant la méthode classique :</p><p> <pre>library("tidyverse")</pre> </p><p>Pour la petite histoire, le tidyverse s’appelait autrefois le hadleyverse ! Plus d’infos : Bienvenue dans le tidyverse (http://www.thinkr.fr/tidyverse-hadleyverse/).  </p>
---
title: Salut Johnny
permalink: /index.html
description: Websites built with this starter
layout: page
preloads:
  href: '/assets/fonts/robotomono/robotomono-variablefont_wght-webfont.woff2'
  as: 'font'
  type: 'font/woff2'
  crossorigin: true
---

<br>
<div class="container">
<iframe title="Salut Johnny" style="width: 350px; height: 350px;" src="https://bandcamp.com/EmbeddedPlayer/album=1979870981/size=large/bgcol=ffffff/linkcol=63b2cc/minimal=true/transparent=true/" seamless><a href="https://fredmahermusique.bandcamp.com/album/jattends-lprintemps" loading="lazy">J&#39;attends l&#39;printemps by Fred Maher</a></iframe>
<caption></caption>
</div>


<article class="region">
  <div class="wrapper flow">
    {{ content | safe }}
   <iframe  class="printemps" title="J'attends l'printemps" style="width: 250px; height: 250px;" src="https://bandcamp.com/EmbeddedPlayer/album=1979870981/size=large/bgcol=ffffff/linkcol=63b2cc/minimal=true/transparent=true/" seamless><a href="https://fredmahermusique.bandcamp.com/album/jattends-lprintemps" loading="lazy">J&#39;attends l&#39;printemps by Fred Maher</a></iframe>
  </div>
</article>

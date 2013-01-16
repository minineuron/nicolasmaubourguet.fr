---
layout: post
title: Chrome, où le le meilleur pire ami du développeur
category: debug
tag: webdev, debug, lifestyle
---

<h1>{{ page.title }}</h1>
<hr>

<p class="meta">29 Nov 2012</p>

<p>Un ami m'appelle hier soir pour un bug étrange qu'il a sur un site sur lequel il bosse. Extrait:</p>
<p>X: Allo? oui, Nicolas, j'ai un souci  .... ..... bizarre avec Chrome.</p>
<p> Et bien écoute, c'est bien que tu m'en parles, je me suis enfin mis à chrome depuis peu (en fait 2 jours avant). Et en plus j'aime bien.</p>
<p>X: Bon, ben en fait, Chrome perd ma session à chaque changement de page </p>
<p> Heu? mais ta session elle est pas coté serveur ? enfin, moi je sais que si, mais toi, qu'en penses tu?</p>
<p>X: ben, si, enfin, je crois, mais bon, ben je suis déco de mon site à chaque chargement de page, et juste sous chrome ... tu n'as pas une idée?</p>
<p>Ben, la comme ça ... bon, c'est où ton site? ... tu as un et blah blah blah</p>
<p> ... </p>
<p>Hey, Chrome se frappes des 404 bizarres sur ton site ... tu as un favicon? parce qu'il est mis par défaut dans la page, et la request échoue et le retour est assez étonnant? Dis moi, tu as personnalisé la 404 ... et c'est du php ... mais tu fais quoi dedans ... ?</p>
<p> ... </p>
<p> ... </p>
<p> Mais si Mais si ... la, tu fais un session_destroy() !!!! Voila, Chrome viens de te faire perdre 15 min à trouver un bug dans ton site ...  </p>
---
layout: post
title: Un premier post
category: lifestyle
tag: jekyll, lifestyle
---

<h1>{{ page.title }}</h1>
<hr>

<p class="meta">26 Nov 2012</p>
<div>
Allez, je déploie ce site en jekyll, donc forcément, j'installe des plugins.
</div>
<div>
	<span>Le premier: code highlight (based on pygments tiens donc)</span>

{% highlight python linenos %}
def foo():
  print 'bar'
{% endhighlight %}

</div>

<div>
	Bon, pour le skin, vrai que je ne me suis pas trop embarassé, un passage du coté du
	twitter bootstrap ... et hop. Mais bon, je suis censé m'occuper du contenu, pas du contenant (en tout cas, au début).
	Je me promets de faire mieux pour la suite.
</div>

</div>
	Quelques soucis connus, le plugin (mal configuré) que j'utilise pour les pages de catégories est flingué ... pas de plan du site HTML. Bon, ca reste à revoir sous peu.
</div>

<div>
	Allez, c'était un premier post ...
</div>
---
layout: portfolio_entry
title: 	VOIA - FUTURESONG ALBUM ART
image: /img/future/future.jpg

stats:
- client: Attack The Music
  year: 2016/2017
  type: album art/illustration/commercial
  
category: album art

img1:
  - title: inside design
    img: /img/future/inside.jpg
img2:
  - title: side
    img: /img/future/side1.jpg
img3:
  - title:
    img: /img/future/side2.jpg

img4:
  - title: back and obi
    img: /img/future/backobi.jpg

page.categories: top

color: 
  - c: e5160e
  
---
{% include color.html %}
 
<p class="col">
Authentic slow-carb cupidatat hot chicken fixie activated charcoal, lumbersexual hexagon voluptate food truck portland. Coloring book lyft vice raw denim. Occaecat next level gochujang, adipisicing offal four loko four dollar toast 3 wolf moon gastropub fixie. Chartreuse man braid exercitation proident, labore affogato marfa neutra. Snackwave normcore officia seitan vaporware. Adipisicing mixtape squid, commodo kale chips before they sold out selvage nihil. Tbh authentic proident, hot chicken +1 man braid readymade hella. <br><br>

Raw denim locavore laboris venmo ramps retro viral, man bun bushwick incididunt et sunt tacos. Hell of activated charcoal seitan vaporware. Twee esse waistcoat +1 assumenda, cred coloring book literally est. Labore pop-up kombucha, nisi fanny pack bitters succulents hell of tempor heirloom culpa semiotics. Man braid culpa yr slow-carb flexitarian portland. Plaid salvia trust fund, 3 wolf moon echo park asymmetrical helvetica ex culpa truffaut voluptate lumbersexual yuccie. Locavore green juice plaid ad.<br><br>

Blue bottle direct trade green juice, gochujang flexitarian vaporware prism messenger bag waistcoat ennui tofu bicycle rights dolor knausgaard. Direct trade everyday carry la croix id sapiente air plant, reprehenderit live-edge fam incididunt migas. Helvetica duis organic normcore offal. Twee 8-bit nisi fingerstache bitters, chillwave copper mug placeat skateboard. Bushwick blog VHS, ex in pug lyft scenester et tumeric af dreamcatcher. Nulla proident celiac 90's coloring book. Ugh marfa farm-to-table, meh flannel man bun typewriter microdosing.<br><br>

Ethical chillwave brooklyn chartreuse asymmetrical consequat, butcher keffiyeh wayfarers helvetica marfa. Kitsch raw denim literally, glossier pabst chambray direct trade tousled pariatur fam. Yr heirloom iceland man bun man braid consequat. Ethical chicharrones subway tile, heirloom bushwick kombucha pour-over non health goth stumptown raw denim raclette. Coloring book tacos cardigan letterpress literally skateboard. Bicycle rights polaroid cardigan, poutine roof party meh sed nisi. Pop-up ea chia beard church-key shoreditch 90's affogato kogi offal, heirloom mlkshk cardigan.<br><br>
</p>

{% for item in page.img1 %}
<h2> {{ item.title }} </h2>
   <a class="chocolat-image" href="{{ site.baseurl }}{{ item.img }}" title="caption image 2">
	<img class="image lazy"  data-original="{{ site.baseurl }}{{ item.img }}" > 
 </a>
  {% endfor %}
  
  
    {% for item in page.img2 %}
<h2> {{ item.title }} </h2>
   <a class="chocolat-image" href="{{ site.baseurl }}{{ item.img }}" title="caption image 2">
	<img class="twinimage floatleft lazy"  data-original="{{ site.baseurl }}{{ item.img }}" > 
 </a>
  {% endfor %}
  
  {% for item in page.img3 %}
<h2> {{ item.title }} </h2>
   <a class="chocolat-image" href="{{ site.baseurl }}{{ item.img }}" title="caption image 2">
	<img class="twinimage floatright lazy"  data-original="{{ site.baseurl }}{{ item.img }}" > 
 </a>
  {% endfor %}
  
  {% for item in page.img4 %}
<h2> {{ item.title }} </h2>
   <a class="chocolat-image" href="{{ site.baseurl }}{{ item.img }}" title="caption image 2">
	<img class="image lazy"  data-original="{{ site.baseurl }}{{ item.img }}" > 
 </a>
  {% endfor %}
  
---
layout: default 
title: City of Yuma Endurance Days
permalink: /
---

<div class="blogthumb-wrapper">
In 1949, Bob Woodward and Woody Jongeward flew an Aeronca Sedan called the City of Yuma non-stop for 47 days in a successful attempt to showcase the great flying weather and convince aviation to stick around in Yuma, Arizona, after the war.
<br /><br />
This page was created in collaboration with EAA Chapter 590 in Yuma, Arizona, some of whom helped to locate the plane in Minnesota in 1997 and bring it home to Yuma to be restored; both Bob and Woody were were present as the plane was flown briefly for a fiftieth anniversary re-enactment flight in 1999.
<br /><br />

{% for post in site.posts %}
<div class="blogthumb">
  <a href="{{site.baseurl}}/{{ post.url }}"><img src="{{site.baseurl}}/{{ post.image }}"></a><br />
  <div style="padding: 10px; line-height: 20px; height: 55px; overflow:hidden;"><a href="{{ post.url }}">{{ post.title }}</a></div>
  <div style="clear:both;"></div>
</div>
{% endfor %}
<div style="clear:both;">&nbsp;</div>

</div>

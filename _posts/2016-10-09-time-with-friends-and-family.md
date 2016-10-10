---
layout: post
title:  "Time with Friends and Family"
snippet: "I have a goal to spend more time with my friends."
---
I have been talking with my wife and I have a goal to spend more time with my
friends.  It seems like that since moving to the suburbs, I don't spend any
time with my friends.  I know part of it is because we have a 15 month old son
at home, but I want to set aside some time to hang out with friends.

I am planning on tracking some of the time I spend with my friends vs time I spend with my wife's friends.  I am going to keep a simple list here starting this past week to track the amount of time.

<ul>
{% for friend in site.data.friends %}
  <li>
    {{friend.name}} : {{friend.times}}
  </li>
{% endfor %}
</ul>

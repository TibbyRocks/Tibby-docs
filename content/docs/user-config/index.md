---
title: "User config"
date: 2024-01-29T23:31:54+01:00
draft: false
weight: 2
---

Tibby wants to get to know you (not in a weird way). It can store some data on how to address you or it can notify servers of your birthday, for example.

This section also covers the commands that let you request or delete the (limited) data Tibby has stored about you.

<!--more-->


#### /config birthday \<set|unset|get\> [dd-mm[-yyyy]] [global]

Tibby can notify servers of any birthdays that are happening on a day.
If you want this you can use the /birthday command to give Tibby this data.    

{{< callout icon="fa-cake-candles fa-solid fa-3x" bg_colour="#B8E8FC" ol_colour="#B8E8FC" fg_colour="#000">}}
Good to know: this data is only used for the server/guild you use the command in. Other users are also not able to see the date you've set (apart from in the birthday notification, of course).
{{< /callout >}}


To set your birthday you'd use `/birthday set 31-12-2024` or `/birthday set 31-12`.

To remove your birthday from Tibby in this server use `/birthday unset`.  

To remove your birthday for all servers at once use `/birthday unset global`. This also works for servers you've left.  

To see what date you've set for the current server use `/birthday get`. This doesn't take parameters and can only be used for yourself.
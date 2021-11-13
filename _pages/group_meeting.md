---
title: "Group meeting"
layout: textlay
excerpt: "Group meeting"
sitemap: false
permalink: /group_meeting/
---

## Group meeting Schedule

Group meetings are held every other week every week.

The normal time/place for Group meetings is Tues. 9:30-11:00 in 502 rom.

<b>Schedule is subject to change, please check frequently. </b>

<div class="row">
<div class="col-sm-6 clearfix">

### Group meeting

{% for meeting in site.data.seminar %}
  <b>{{ meeting.date}}</b>  {{ meeting.presenter}}
  <br /> 

{% endfor %}


</div>
</div>

---
layout: archive
title: "Publications"
permalink: /project/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}


[High Performance Image Collection for the Mapper Robot II](https://robotics.shanghaitech.edu.cn/node/308)
-----
  * A project of the Robotics 2020 class of the School of Information Science and Technology (SIST) of ShanghaiTech University.
  * Course Instructor: [Prof. Sören Schwertfeger](https://robotics.shanghaitech.edu.cn/people/soeren).
  * To avoid the limitation of the ROS transmission bandwidths on the second version of the MARS Mapper Robot dataset collection, this project develops a new image compression method which can produce fast and highquality image compression and saving.


{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

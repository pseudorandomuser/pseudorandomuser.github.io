---
layout: about
title: Get in touch
permalink: /contact
---

If you have any inquiries about me or my projects and would like to get in touch with me, please don't hesitate to use any of the following means to send a message my way:<br><br>

{%- if site.social_links -%}
{%- for social_link in site.social_links -%}
{%- if social_link.text -%}
<a href="{{ social_link.url | replace: '(email)', site.email }}" style="text-decoration: none;">{{ social_link.text }}</a><br>
{%- endif -%}
{%- endfor -%}
{%- endif -%}

<br>Disclaimer: The above links will take you to external services which I am in no way affiliated with. I am not responsible for any content hosted on these platforms.

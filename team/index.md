---
title: Team
nav:
  order: 1
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are always interested in new members with a passion for applying computational methods to translational cancer research. If you are interested in joining our team, please see our contact page.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}
<br />
{% include list.html data="members" component="portrait" filter="role == 'scientific_associate'" %}
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}
{% include list.html data="members" component="portrait" filter="role == 'programmer'" %}
{% include list.html data="members" component="portrait" filter="role == 'clinical_fellow'" %}
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}
{% include list.html data="members" component="portrait" filter="role == 'research_student'" %}
{% include list.html data="members" component="portrait" filter="role == 'undergrad'" %}
{% include list.html data="members" component="portrait" filter="role == 'mascot'" %}

{% include section.html dark=true %}
Interested in joining our lab? Please reach out to us on our contact page.

{%
  include button.html
  text="Join the Team"
  link="contact"
  icon="fa-solid fa-arrow-right"
%}


{% include section.html %}

## Funding Sources

{% capture content %}

{% endcapture %}

{% include grid.html style="square" content=content %}

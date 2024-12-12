---
layout: default
# title: People

picture-role-groups:
- {roles: [faculty], width: 30}
# - {roles: [postdoc], width: 30}
- {roles: [grad], width: 30}
# - {roles: [visit], width: 30}


no-picture-role-groups:
# - {roles: [alum], width: 30}
---

<section class="people row justify-content-between">
    
    {% for role-group in page.picture-role-groups %}
        <div class="col-md-{{ role-group.width }}">
            {% for role in role-group.roles %}
                {% include role-people.html role=role image=true %}
            {% endfor %}
        </div>
    {% endfor %}
</section>

<section class="people row justify-content-between">
    {% for role-group in page.no-picture-role-groups %}
        <div class="col-md-{{ role-group.width }}">
            {% for role in role-group.roles %}
                {% include role-people.html role=role image=false %}
            {% endfor %}
        </div>
    {% endfor %}
</section>
---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<div>
    <h2>Current members </h2>
    {% include member_list.html collection="postdoc" type="current_member"%}
    {% include member_list.html collection="student" type="current_member"%}
    <h2> Former members </h2>
    {% include member_list.html collection="former" type="former_member"%}
</div>

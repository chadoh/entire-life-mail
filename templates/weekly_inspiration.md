    {{quote}}

Hey {{name}}! Welcome to Week {{week_of_year}} of Year {{age}}.

A fresh new week! {{percent_done}}% through your {{age_ordinal}} trip around the sun.{{#is_birthday}} (Happy birthday!){{/is_birthday}}

Weeks lived so far: {{completed_weeks_count}}
{{#extra}}{{#each .}}{{.}}
{{/each}}{{/extra}}
{{#expired_plans}}
Here's what you planned to do by now:
{{#each .}}
{{emoji}} {{title}} → {{url}}
{{/each}}
{{/expired_plans}}What happened last week? Add it to your calendar → {{last_week_url}}



{{#events}}Week {{../next_week}}:

This week marks the anniversary of:
{{#each .}}
{{emoji}} {{title}} – {{time_ago}} → {{url}}
{{/each}}



{{/events}}What you might do next:
{{#plans}}{{#each .}}
{{emoji}} {{title}} – {{time_from_now}} → {{url}}
{{/each}}{{/plans}}
Plan An Awesome Future → {{calendar_url}}


{{#blog}}From The Blog
→ {{ url }}
{{#each snippets}}{{#h2}}

{{& . }}
{{/h2}}{{#h3}}

{{& . }}
{{/h3}}{{#h4}}

{{& . }}
{{/h4}}{{#p}}
{{& . }}
{{/p}}{{#li}}
* {{& . }}
{{/li}}{{#img}}
image → {{ . }} ({{../caption}})
{{/img}}{{#blockquote}}
> {{& . }}
{{/blockquote}}{{#pullquote}}
  {{& . }}
{{/pullquote}}{{/each}}
{{/blog}}


Copyleft © Entire.Life 2016, some rights reserved
Chad Ostrowski at The Candy Factory, Warehouse D
342 North Queen St, Rear, Lancaster PA 17602, USA

Quote powered by theysaidso.com

Too much email? Unsubscribe → {{unsubscribe}}

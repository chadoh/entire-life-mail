    {{quote}}

Hey {{name}}! Welcome to Week {{week_of_year}} of Year {{age}}.

A fresh new week! {{percent_done}}% through your {{age_ordinal}} trip around the sun.{{#is_birthday}} (Happy birthday!){{/is_birthday}}

Weeks lived so far: {{completed_weeks_count}}
{{#extra}}{{#each .}}
{{.}}
{{/each}}{{/extra}}
{{#expired_plans}}Here's what you planned to do by now:
{{#each .}}
{{emoji}} {{title}} → {{url}}
{{/each}}
{{/expired_plans}}What happened last week? Add it to your calendar → {{last_week_url}}



Week {{next_week}}:

{{#events}}This coming week, {{../next_week_range}}, marks the anniversary of some things for you:
{{#each .}}
{{emoji}} {{title}} – {{time_ago}} → {{url}}
{{/each}}
Did anything else happen from {{../next_week_range}} in past
years of your life? All of it, the good and the bad, is what makes you
who you are. It's all part of your story.
{{/events}}{{^ events}}Is it true that you've never experienced anything significant from
{{../next_week_range}}? Whether happy or heavy, all of our
experiences shape who we are. Adding past events to your life calendar
will help you spot the storylines (or the need for better storylines) in
your life. It will give the present context and make life richer.
{{/events}}Add past events to your calendar → {{calendar_url}}


And Beyond:
{{#plans}}{{#each .}}
{{emoji}} {{title}} – {{time_from_now}} → {{url}}
{{/each}}
Do you have any other hopes, dreams, or goals?{{/plans}}{{^ plans}}
What are your hopes, your dreams, your goals?{{/plans}}
Dream big and then get specific—challenge yourself to reach
those dreams by a set date. You'll be amazed at how much
you can accomplish!

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

# We are DefCon Holland...

We are a collective of people that organize the DC3115 and DC3120 meetups.

DefCon Holland meetups are meetups for Dutch Hackers in a Dutch bar after work or school. We will have a stage with amazing speakers, some oldschool games and if you had too much beer & bitterballen you can do some hacker karaoke if you want.

## Blog

Last 10 posts

<ul>
{% for post in site.posts %}
	{% if forloop.index <= 10 %}
	    <li>
	        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }} ({{ post.date | date: "%Y-%m-%d"}})</a>
	    </li>
	{% endif %}
{% endfor %}
</ul>

[All posts](/blog)

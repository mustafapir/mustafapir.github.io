---
layout: page
title: Contact
nav-menu: true
image: assets/images/tiles/contacts.png
position: 4
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="social"  class="background-accent3">
	<div class="inner">
		<div class="row">
			<div class="6u 12u$(small)">
				<header class="major">
					<h1>Social</h1>
				</header>
				<ul class="social_custom">
					{% if site.twitter_url %}
					<li><a href="{{ site.twitter_url }}" class="icon alt fa-twitter" target="_blank"><span >	&nbsp;Twitter</span></a> </li>
					{% endif %}
					{% if site.googleplus_url %}
					<li><a href="{{ site.googleplus_url }}" class="icon alt fa-google-plus" target="_blank"><span >	&nbsp;Google+</span></a></li>
					{% endif %}
					{% if site.facebook_url %}
					<li><a href="{{ site.facebook_url }}" class="icon alt fa-facebook" target="_blank"><span >	&nbsp;Facebook</span></a></li>
					{% endif %}
					{% if site.instagram_url %}
					<li><a href="{{ site.instagram_url }}" class="icon alt fa-instagram" target="_blank"><span >	&nbsp;Instagram</span></a></li>
					{% endif %}
					{% if site.pinterest_url %}
					<li><a href="{{ site.pinterest_url }}" class="icon alt fa-pinterest" target="_blank"><span >	&nbsp;Pinterest</span></a></li>
					{% endif %}
					{% if site.500px_url %}
					<li><a href="{{ site.500px_url }}" class="icon alt fa-500px" target="_blank"><span >	&nbsp;500px</span></a></li>
					{% endif %}
					{% if site.gitlab_url %}
					<li><a href="{{ site.gitlab_url }}" class="icon alt fa-gitlab" target="_blank"><span >	&nbsp;GitLab</span></a></li>
					{% endif %}
					{% if site.github_url %}
					<li><a href="{{ site.github_url }}" class="icon alt fa-github" target="_blank"><span >	&nbsp;GitHub</span></a></li>
					{% endif %}
					{% if site.slack_url %}
					<li><a href="{{ site.slack_url }}" class="icon alt fa-slack" target="_blank"><span >	&nbsp;Slack</span></a></li>
					{% endif %}
					{% if site.linkedin_url %}
					<li><a href="{{ site.linkedin_url }}" class="icon alt fa-linkedin" target="_blank"><span >	&nbsp;LinkedIn</span></a></li>
					{% endif %}
				</ul>
			</div>	
			<div class="6u 12u$(small)">
				<header class="major">
					<h1>External links</h1>
				</header>
				<ul>
					<li><a href="http://kaplanlab.com/members/" target="_blank">Kaplan Lab members</a></li>
					<li><a href="https://scholar.google.com/citations?user=kAVZ5ocAAAAJ&hl=en" target="_blank">Google Scholar profile</a></li>
				</ul>
			</div>	
		</div>
    </div>
</section>


<!-- Contact -->
<section id="contact">
	<div class="inner">
		<section>
			<form action="https://formspree.io/f/mzboywjp" method="POST">
				<div class="field half first">
					<label for="name">Name</label>
					<input type="text" name="name" id="name" />
				</div>
				<div class="field half">
					<label for="email">Email</label>
					<input type="text" name="_replyto" id="email" />
				</div>
				<div class="field">
					<label for="message">Message</label>
					<textarea name="message" id="message" rows="6"></textarea>
				</div>
				<ul class="actions">
					<li><input type="submit" value="Send Message" class="special" /></li>
					<li><input type="reset" value="Clear" /></li>
				</ul>
			</form>
		</section>
		<section class="split">
			<section>
				<div class="contact-method">
					<span class="icon alt fa-envelope"></span>
					<h3>Email</h3>
					<a href="mailto:{{ site.email }}">{{ site.email }}</a>
				</div>
			</section>
			<section>
				<div class="contact-method">
					<span class="icon alt fa-phone"></span>
					<h3>Phone</h3>
					<a href="tel:{{ site.phone }}">{{ site.phone }}</a>
				</div>
			</section>
			<section>
				<div class="contact-method">
					<span class="icon alt fa-home"></span>
					<h3>Address</h3>
					<span>
					{% if site.street_address %}
					    {{ site.street_address }}<br />
					{% endif %}
					{% if site.city %}
					    {{ site.city }},
					{% endif %}
					{% if site.state %}
					    {{ site.state }} 
					{% endif %}
					{% if site.zip_code %}
					    {{ site.zip_code }}<br />
					{% endif %}
					{% if site.country %}
					    {{ site.country }}
					{% endif %}
					</span>
				</div>
			</section>
		</section>
	</div>
</section>



</div>

---
title: Contact Me
layout: single-project
permalink: /contact
---
If you wish to get in contact for booking or any other reason, feel free to leave me a message in the form below or via any of the social platforms below.
<br><br>

<form id="contact-form" action="#" method="post" class="comment-form contact">
	<div class="contact-item form-name">
		<input name="name" value="" type="text" placeholder="Your Name">
	</div>
	<div class="contact-item form-email">
		<input name="email" value="" type="email" placeholder="Your Email *" required>
	</div>
	<div class="contact-item form-subject">
		<input id="subject" name="subject" value="" type="text" placeholder="Subject">
	</div>
	<div class="contact-item field-full form-message">
		<textarea name="message" placeholder="Message *" rows="6" required></textarea>
	</div>
	<div class="contact-item form-privacy">
		<input name="privacy" type="checkbox" required>
		<span> I accept the <a href="/privacy-policy" target="_blank"> Privacy Policy </a> </span>
	</div>
	<div class="contact-item form-submit">
		<input name="submit" type="submit" id="submit" class="submit" value="Send">
	</div>
	<p class="contact-message"> </p>
</form>

<div class="post-footer">
	<div class="post-share-wrap">
		<div class="post-share">

		{% include social.html %}
		
		</div>
	</div>
</div>
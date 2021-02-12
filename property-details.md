---
layout: default
title: Property Details
permalink: /property-details/
---
<h3>Please tell me about the type of property you’d like to find</h3>
<form class="contact-form" method="post" action="/thankyou" id="property-details-form">
  <textarea name="Message"></textarea>
  <!-- Cloud cannon settings field -->
  <div class="hidden">
    <input type="hidden" name="_to" value="{{site.data.settings.client.email}}">
    <input type="hidden" name="_subject" value="Property Details Message from your Vyral Video Blog">
    <input type="text" name="_gotcha">
  </div>

  <button class="g-recaptcha" data-sitekey="{{site.data.settings.forms.sitekey}}" data-callback='onPropertyDetailsSubmit' data-badge="bottomleft">Submit</button>
</form>

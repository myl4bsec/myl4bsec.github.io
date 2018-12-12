---
layout: default
title: Contact MyL4bSec
---

<div id="contact">
  <h1 class="pageTitle">Contact Me</h1>
  <div class="contactContent">
    <p class="intro">This is an example Contact page. If you want to make changes then do so in the <code>contact.html</code> file.</p>
    <p>The form is provided by <a href="http://formspree.io/">Formspree.</a> Follow the directions on their site to set up the form for use.</p>
    <p>If you have questions about the theme feel free to <a href="mailto:isaac3366@gmail.com">email me</a> or create an issue on <a href="https://github.com/brianmaierjr/long-haul">GitHub</a>. Enjoy!</p>
  </div>


<div id="after_submit"></div>
<form id="contact_form" action="#" method="POST" enctype="multipart/form-data">
  <div class="row">
    <label class="required" for="name">Your name:</label><br />
    <input id="name" class="input" name="name" type="text" value="" size="30" /><br />
    <span id="name_validation" class="error_message"></span>
  </div>
  <div class="row">
    <label class="required" for="email">Your email:</label><br />
    <input id="email" class="input" name="email" type="text" value="" size="30" /><br />
    <span id="email_validation" class="error_message"></span>
  </div>
  <div class="row">
    <label class="required" for="message">Your message:</label><br />
    <textarea id="message" class="input" name="message" rows="7" cols="30"></textarea><br />
    <span id="message_validation" class="error_message"></span>
  </div>
    
    <input id="submit_button" type="submit" value="Send email" />
</form>

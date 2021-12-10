---
layout: archive
title: "Contact"
permalink: /contact/
author_profile: true
---

{% include base_path %}

<h3>Feel free to contact me should you have any queries &#128516;!</h3>

<form action="https://formspree.io/f/xoqrqepg" id="contact-form" name="contact-form" method="POST" >
    <label for="name">Name: </label>
    <input type="text" id="name" name="name" placeholder="Your Name" required/>
    <label for="mail">Email address: </label>
    <input type="email" id="mail" name="mail" placeholder="Your Email Address" required/>
    <label for="message">Message: </label>
    <textarea id="message" name="message" placeholder="Type what you want to!" required></textarea>
    <button type="submit">Send your message</button>
</form>
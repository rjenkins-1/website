---
layout: default
title: Ross Jenkins
---

<h1>Ross Jenkins,<br>etc. unknown permanent,</h1>

<figure>
  <img src="{{ '/assets/ross.jpg' | relative_url }}" alt="Portrait of Ross Jenkins">
</figure>

<section class="intro" aria-label="Introduction">
  <p>
    Ross is a musician and writer.<br>
    His latest album, <em>Free All Day</em>,<br>
    was released in 2022.<br>
    He is easy to find.
  </p>
</section>

<a class="bandcamp" href="https://rossjenkins.bandcamp.com" target="_blank" rel="noopener noreferrer">
  rossjenkins.bandcamp.com →
</a>

<section class="contact">
  <h2>CONTACT</h2>

  <!--
    Replace YOUR_FORMSPREE_ID with the ID Formspree gives you.
    Example:
    action="https://formspree.io/f/abcdwxyz"
  -->
  <form action="https://formspree.io/f/YOUR_FORMSPREE_ID" method="POST">
    <div class="field">
      <label for="name">Name</label>
      <input id="name" name="name" type="text" autocomplete="name" required>
    </div>

    <div class="field">
      <label for="email">Email</label>
      <input id="email" name="email" type="email" autocomplete="email" required>
    </div>

    <div class="field message-field">
      <label for="message">Message</label>
      <textarea id="message" name="message" required></textarea>
    </div>

    <button type="submit">SEND</button>
  </form>
</section>

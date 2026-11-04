---
layout: default
title: Brad Huttash
---

<div class="profile" id="profile">
  <img class="profile-photo" src="{{ '/assets/img/me.jpg' | relative_url }}" alt="Your Name">
  <div class="profile-info">
    <strong>Your Name</strong>
    <span>
      <a href="mailto:you@example.com">you@example.com</a> ·
      <a href="https://linkedin.com/in/yourname">LinkedIn</a> ·
      <a href="https://github.com/yourname">GitHub</a>
    </span>
  </div>
</div>

<script>
  (function () {
    var profile = document.getElementById('profile');
    function update() {
      profile.classList.toggle('scrolled', window.scrollY > 60);
    }
    window.addEventListener('scroll', update, { passive: true });
    update();
  })();
</script>

## About me

# Brad Huttash
Software Engineer

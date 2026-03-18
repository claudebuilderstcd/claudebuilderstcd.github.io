---
layout: default
title: Hackathon 2026
---

<div class="hk-hero">
  <div class="hk-particles" aria-hidden="true">
    <span></span><span></span><span></span><span></span><span></span>
    <span></span><span></span><span></span><span></span><span></span>
  </div>
  <div class="hk-hero__inner">
    <div class="hk-badge">Claude Builders · TCD · 2026</div>
    <h1 class="hk-title">
      <span class="hk-title__line hk-pixel">Claude</span>
      <span class="hk-title__line hk-title__line--gold hk-pixel">Hackathon</span>
    </h1>
    <p class="hk-subtitle">Build something extraordinary. Win free API credits.</p>
    <div class="hk-countdown" id="hk-countdown">
      <div class="hk-countdown__unit">
        <span class="hk-countdown__val hk-pixel" id="cd-days">00</span>
        <span class="hk-countdown__label">Days</span>
      </div>
      <div class="hk-countdown__sep hk-pixel">:</div>
      <div class="hk-countdown__unit">
        <span class="hk-countdown__val hk-pixel" id="cd-hours">00</span>
        <span class="hk-countdown__label">Hours</span>
      </div>
      <div class="hk-countdown__sep hk-pixel">:</div>
      <div class="hk-countdown__unit">
        <span class="hk-countdown__val hk-pixel" id="cd-mins">00</span>
        <span class="hk-countdown__label">Mins</span>
      </div>
      <div class="hk-countdown__sep hk-pixel">:</div>
      <div class="hk-countdown__unit">
        <span class="hk-countdown__val hk-pixel" id="cd-secs">00</span>
        <span class="hk-countdown__label">Secs</span>
      </div>
    </div>
    <div class="hk-meta">
      <div class="hk-meta__item">
        <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"/><line x1="16" y1="2" x2="16" y2="6"/><line x1="8" y1="2" x2="8" y2="6"/><line x1="3" y1="10" x2="21" y2="10"/></svg>
        Friday, March 27, 2026
      </div>
      <div class="hk-meta__item">
        <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"/><polyline points="12 6 12 12 16 14"/></svg>
        10:00 AM – 6:00 PM
      </div>
      <div class="hk-meta__item">
        <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13S3 17 3 10a9 9 0 0 1 18 0z"/><circle cx="12" cy="10" r="3"/></svg>
        The Portal, Trinity Business School
      </div>
    </div>
    <a
      href="https://luma.com/event/evt-ne4HTlEJnF6dWFD"
      class="luma-checkout--button hk-register-btn"
      data-luma-action="checkout"
      data-luma-event-id="evt-ne4HTlEJnF6dWFD"
    >
      Register Now — It's Free
    </a>
  </div>
  <div class="hk-scroll-hint" aria-hidden="true">
    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><polyline points="6 9 12 15 18 9"/></svg>
  </div>
</div>
<script id="luma-checkout" src="https://embed.lu.ma/checkout-button.js"></script>
<script>
(function() {
  var target = new Date('2026-03-27T10:00:00').getTime();
  function pad(n) { return String(n).padStart(2, '0'); }
  function tick() {
    var now = Date.now();
    var diff = target - now;
    if (diff <= 0) {
      document.getElementById('hk-countdown').innerHTML = '<span class="hk-pixel hk-countdown__live">LIVE NOW!</span>';
      return;
    }
    var d = Math.floor(diff / 86400000);
    var h = Math.floor((diff % 86400000) / 3600000);
    var m = Math.floor((diff % 3600000) / 60000);
    var s = Math.floor((diff % 60000) / 1000);
    document.getElementById('cd-days').textContent  = pad(d);
    document.getElementById('cd-hours').textContent = pad(h);
    document.getElementById('cd-mins').textContent  = pad(m);
    document.getElementById('cd-secs').textContent  = pad(s);
  }
  tick();
  setInterval(tick, 1000);
})();
</script>

<div class="hk-section">
  <h2 class="hk-section__title">What is it?</h2>
  <p>A full-day hands-on hackathon where you build real AI applications using Claude's API. Whether you're a total beginner or an experienced developer, this is your chance to ship something cool, learn fast, and compete for prizes.</p>
</div>

<div class="hk-tracks">
  <h2 class="hk-section__title">Tracks</h2>
  <div class="hk-prize-pool">
    <div class="hk-prize-pool__label hk-pixel">// TOTAL PRIZE POOL</div>
    <div class="hk-prize-pool__amount hk-pixel">$1,500</div>
    <div class="hk-prize-pool__sub">in API Credits — <span class="hk-prize-pool__per">$300 per track winner</span></div>
  </div>
  <p class="hk-tracks__intro">Pick a track and build something that matters. All tracks use Claude's API.</p>
  <div class="hk-tracks__grid">

    <div class="hk-track hk-track--bio">
      <div class="hk-track__corner hk-track__corner--tl">┌─</div>
      <div class="hk-track__corner hk-track__corner--tr">─┐</div>
      <div class="hk-track__corner hk-track__corner--bl">└─</div>
      <div class="hk-track__corner hk-track__corner--br">─┘</div>
      <div class="hk-track__inner">
        <div class="hk-track__emoji">🧬</div>
        <div class="hk-track__name hk-pixel">Biology &amp;<br>Physical Health</div>
        <div class="hk-track__desc">Drug discovery, diagnostics, fitness, longevity — make bodies work better.</div>
        <div class="hk-track__prize">$300 API Credits</div>
      </div>
    </div>

    <div class="hk-track hk-track--neuro">
      <div class="hk-track__corner hk-track__corner--tl">┌─</div>
      <div class="hk-track__corner hk-track__corner--tr">─┐</div>
      <div class="hk-track__corner hk-track__corner--bl">└─</div>
      <div class="hk-track__corner hk-track__corner--br">─┘</div>
      <div class="hk-track__inner">
        <div class="hk-track__emoji">🧠</div>
        <div class="hk-track__name hk-pixel">Neuroscience &amp;<br>Mental Health</div>
        <div class="hk-track__desc">Therapy tools, cognitive aids, mood tracking — support minds at scale.</div>
        <div class="hk-track__prize">$300 API Credits</div>
      </div>
    </div>

    <div class="hk-track hk-track--edu">
      <div class="hk-track__corner hk-track__corner--tl">┌─</div>
      <div class="hk-track__corner hk-track__corner--tr">─┐</div>
      <div class="hk-track__corner hk-track__corner--bl">└─</div>
      <div class="hk-track__corner hk-track__corner--br">─┘</div>
      <div class="hk-track__inner">
        <div class="hk-track__emoji">📚</div>
        <div class="hk-track__name hk-pixel">Economic<br>Empowerment &amp; Education</div>
        <div class="hk-track__desc">Tutoring, financial literacy, job access — break down barriers to opportunity.</div>
        <div class="hk-track__prize">$300 API Credits</div>
      </div>
    </div>

    <div class="hk-track hk-track--gov">
      <div class="hk-track__corner hk-track__corner--tl">┌─</div>
      <div class="hk-track__corner hk-track__corner--tr">─┐</div>
      <div class="hk-track__corner hk-track__corner--bl">└─</div>
      <div class="hk-track__corner hk-track__corner--br">─┘</div>
      <div class="hk-track__inner">
        <div class="hk-track__emoji">🗳️</div>
        <div class="hk-track__name hk-pixel">Governance &amp;<br>Collaboration</div>
        <div class="hk-track__desc">Civic tools, deliberation platforms, trust systems — strengthen democracy.</div>
        <div class="hk-track__prize">$300 API Credits</div>
      </div>
    </div>

    <div class="hk-track hk-track--art">
      <div class="hk-track__corner hk-track__corner--tl">┌─</div>
      <div class="hk-track__corner hk-track__corner--tr">─┐</div>
      <div class="hk-track__corner hk-track__corner--bl">└─</div>
      <div class="hk-track__corner hk-track__corner--br">─┘</div>
      <div class="hk-track__inner">
        <div class="hk-track__emoji">🎨</div>
        <div class="hk-track__name hk-pixel">Creative<br>Flourishing</div>
        <div class="hk-track__desc">Music, writing, art, games — help humans create and experience beauty.</div>
        <div class="hk-track__prize">$300 API Credits</div>
      </div>
    </div>

  </div>
</div>

<div class="hk-schedule">
  <h2 class="hk-section__title">Schedule</h2>
  <div class="hk-timeline">
    <div class="hk-timeline__item">
      <div class="hk-timeline__time">10:00–11:00</div>
      <div class="hk-timeline__dot"></div>
      <div class="hk-timeline__content">
        <strong>Introduction & Group Forming</strong>
        <p>Hackathon kickoff, rules briefing, and team formation.</p>
      </div>
    </div>
    <div class="hk-timeline__item">
      <div class="hk-timeline__time">11:00–13:00</div>
      <div class="hk-timeline__dot"></div>
      <div class="hk-timeline__content">
        <strong>Hacking</strong>
        <p>Build your project. Mentors available throughout.</p>
      </div>
    </div>
    <div class="hk-timeline__item">
      <div class="hk-timeline__time">13:00–14:00</div>
      <div class="hk-timeline__dot"></div>
      <div class="hk-timeline__content">
        <strong>Lunch + Talk by Kevin Collins</strong>
        <p>Food provided. Special guest talk during the break.</p>
      </div>
    </div>
    <div class="hk-timeline__item">
      <div class="hk-timeline__time">14:00–16:00</div>
      <div class="hk-timeline__dot"></div>
      <div class="hk-timeline__content">
        <strong>Hacking</strong>
        <p>Final sprint — wrap up and polish your project.</p>
      </div>
    </div>
    <div class="hk-timeline__item">
      <div class="hk-timeline__time">16:00–18:30</div>
      <div class="hk-timeline__dot"></div>
      <div class="hk-timeline__content">
        <strong>Pitching, Judging & Awards</strong>
        <p>Present your project to the panel. Winners announced and prizes distributed.</p>
      </div>
    </div>
  </div>
</div>

<div class="hk-section hk-faq">
  <h2 class="hk-section__title">FAQ</h2>
  <div class="hk-faq__grid">
    <div class="hk-faq__item">
      <strong>Do I need prior experience?</strong>
      <p>No. All skill levels welcome. Mentors will be on hand to help.</p>
    </div>
    <div class="hk-faq__item">
      <strong>Do I need a team?</strong>
      <p>You can sign up solo or as a team of up to 5. We'll help with team formation at the start.</p>
    </div>
    <div class="hk-faq__item">
      <strong>What should I bring?</strong>
      <p>Laptop, charger, and ideas. API access and credits will be provided.</p>
    </div>
    <div class="hk-faq__item">
      <strong>Is it free?</strong>
      <p>Yes, completely free to attend. Just register below.</p>
    </div>
  </div>
</div>

<div class="hk-cta">
  <h2>Ready to build?</h2>
  <p>Spots are limited — secure yours now.</p>
  <a
    href="https://luma.com/event/evt-ne4HTlEJnF6dWFD"
    class="luma-checkout--button hk-register-btn"
    data-luma-action="checkout"
    data-luma-event-id="evt-ne4HTlEJnF6dWFD"
  >
    Register for the Hackathon
  </a>
</div>

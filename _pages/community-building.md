---
layout: single
title: "Community Building Hackathon"
permalink: /community-building/
author_profile: false
sidebar:
  nav: "main"
classes: wide
---
<style>
  p {
      text-align: justify;
      display: block;
      margin-block-start: 1em;
      margin-block-end: 1em;
      margin-inline-start: 0px;
      margin-inline-end: 0px;
    }
  .menu-tab {
    display: flex;
    flex-wrap: wrap;
    padding: 0;
  }
  .menu-tab li.current {
    border-bottom: solid 2px #ff0046;
    opacity: 1;
}
.menu-tab li {
    cursor: pointer;
    font-size: 20px;
    line-height: 40px;
    margin-right: 40px;
    font-weight: 700;
    opacity: .7;
    border-bottom: solid 2px #94949452;
}
body menu>li {
    list-style: none;
}
body menu {
  position: relative;
}
.gr-event-body .gr-event-body__info {
    margin-top: 40px;
}
.gr-event-body .menu-tab {
    display: flex;
    flex-wrap: wrap;
}
</style>
<main class="gr-event-body">
  <menu class="menu-tab">
    <li data-tab="pre-hackathon">Pre-hackathon</li>
    <li data-tab="hackathon">Hackathon</li>
    <li data-tab="post-hackathon">Post-hackathon</li>
  </menu>
  <div class="gr-event-body__info">            
    <article class="pre-hackathon text-block">
      <div style="text-align: justify;">
        <p>Goal - Community building</p>
        <p>Themes - Gateway community, shared resources, infrastructure and practices, e.g., data sharing practices.</p>
        <p>Cooperation - Refer to <a href="{{ relative_url }}/hackathon-planning-kit/competition-cooperation">this page</a> for how to design this process and what the tradeoffs against competition are</p>
        <p>Stakeholder involvement - Refer to <a href="https://guide.mlh.io/organizer-timeline/4-months-before/sponsorship">5-step MLH sponsorship process</a> how to successfully get your event funded</p>
        <p>Participant recruitment - Identify potential participants, e.g., decide if it is a close event or open event which invites participants from outside of the host organization / community / team boundary, send invitations and gather their skills and motivations via pre-hackathon questionnaire</p>
        <p>Tools and technology - Decide what tools to use and set up communication channels and development environments</p>
        <p>Mentoring - Refer to <a href="{{ relative_url }}/hackathon-planning-kit/mentoring">this page</a> for what mentoring strategy to use and how to recruit and support mentors</p>
        <p>Continuity planning - Refer to <a href="{{ relative_url }}/hackathon-planning-kit/continuity-planning">this page</a> for how to support the continuity of hackahton outcomes</p>
        <p>Duration: Typically 48 hours</p>
        <p>Venue, equipments, transportation, promoting the event, food, and other event planning logistics</p>
        <p>Specialized preparation - Introduction of tools, technology, mentors to participants, and environment setup via online tutorials / webinars</p>
      </div>
    </article>
    <article class="hackathon text-block">
      <div style="text-align: justify;">
        <p><b>Day 1 (half-day)</b></p>
        <p>Check-in, snacks</p>
        <p>Opening remarks</p>
        <p>Presentation of ideas</p>
        <p>Team formation</p>
        <p>Hack begins!</p>
        <p><b>Day 2 (full-day)</b></p>
        <p>Coffee & breakfast</p>
        <p>Hack continues!</p>
        <p>Checkpoint #1</p>
        <p>Mentors go around</p>
        <p>Lunch</p>
        <p>Hack continues!</p>
        <p>Breaks - snacks & games</p>
        <p>Checkpoint #2</p>
        <p>Dinner</p>
        <p><b>Day 3 (half-day)</b></p>
        <p>Coffee & breakfast</p>
        <p>Hack continues!</p>
        <p>Checkpoint #3</p>
        <p>Team final presentations & Live stream</p>
        <p>Lunch & networking</p>
      </div>
    </article>  
    <article class="post-hackathon text-block">
      <div style="text-align: justify;">
        <p>Administer post-hackahton questionnaire</p>
        <p>Follow up on the project progress</p>
        <p>Continued engagement with participants via tools that are used before and at the event</p>
      </div>
    </article>                  
  </div>
</main>
<script src="https://cdn.jsdelivr.net/npm/intersection-observer@0.7.0/intersection-observer.js"></script>
<script src="https://cdn.jsdelivr.net/npm/vanilla-lazyload@12.4.0/dist/lazyload.min.js"></script>
<script src="https://code.jquery.com/jquery-2.2.4.min.js" integrity="sha256-BbhdlvQf/xTY9gja0Dq3HiwQF8LaCRTXxZKRutelT44=" crossorigin="anonymous"></script>
<script type="text/javascript" src="http://garage48.org/javascripts/colorextract.js?v2"></script>
<script type="text/javascript" src="http://garage48.org/javascripts/scripts-g19.js?v3"></script>
<script type="text/javascript" src="http://garage48.org/javascripts/jquery.voogAjaxForm.js"></script>
<script>
 var firstTab = $(".menu-tab li").first();
 var initialTab = firstTab.data("tab");
 firstTab.addClass("current");

 $(".gr-event-body").find("article." + initialTab).css("display","block");

 $(document).on("click",".menu-tab li",function() {
     var $name = $(this).data("tab");
     $(this).addClass("current").siblings().removeClass("current");
     $(".gr-event-body").find("article." + $name).css("display","block").siblings("article").css("display","none")
 });
</script>

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
    <div style="text-align: justify;">Technological advancements have flattened the world and brought people from across the globe together via the ever-growing cyberspace. Industry experts predict there will be 6 billion internet users by 2022 (75 percent of the projected world population of 8 billion). Cybercriminals smell blood now, not silicon :)</div>
    </article>
    <article class="hackathon text-block">
    <div style="text-align: justify;">Technological advancements have flattened the world and brought people from across the globe together via the ever-growing cyberspace. Industry experts predict there will be 6 billion internet users by 2022 (75 percent of the projected world population of 8 billion). Cybercriminals smell blood now, not silicon :)</div>
    </article>  
    <article class="post-hackathon text-block">
    <div style="text-align: justify;">Technological advancements have flattened the world and brought people from across the globe together via the ever-growing cyberspace. Industry experts predict there will be 6 billion internet users by 2022 (75 percent of the projected world population of 8 billion). Cybercriminals smell blood now, not silicon :)</div>
    </article>                  
  </div>
</main>
<script src="https://cdn.jsdelivr.net/npm/intersection-observer@0.7.0/intersection-observer.js"></script>
<script src="https://cdn.jsdelivr.net/npm/vanilla-lazyload@12.4.0/dist/lazyload.min.js"></script>
<script src="https://code.jquery.com/jquery-2.2.4.min.js" integrity="sha256-BbhdlvQf/xTY9gja0Dq3HiwQF8LaCRTXxZKRutelT44=" crossorigin="anonymous"></script>
<script type="text/javascript" src="/javascripts/colorextract.js?v2"></script>
<script type="text/javascript" src="/javascripts/scripts-g19.js?v3"></script>
<script type="text/javascript" src="/javascripts/jquery.voogAjaxForm.js"></script>
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

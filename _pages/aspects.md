---
layout: single
permalink: /aspects/
title: "Key Hackathon Aspects"
author_profile: false
classes: wide
sidebar:
  nav: "main"
---
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    tr {
      align: top;
    }
    td {
    vertical-align: top;
    }
    .round-button {
       display:block;
       width:100px;
       height:100px;
       line-height:80px;
       text-align:center;
       border: 0px solid;
       border-radius: 50%;
       opacity: 0.8;
       z-index: 1;
       position:absolute;
    }
    .round-button:hover {
       opacity: 0.5;
    }
    .chover:hover{
      opacity: 0.5;
    }
    i{
      z-index: 2;
      position:absolute;
    }
    svg{
      margin-left: auto;
      margin-right: auto;
      <!-- border: 1px solid black; -->
    }
    svg text{
      font-size: 36px;
      font-family: FontAwesome;
      text-anchor: middle;
    }
    .container{
      text-align: center;
    }
    .col {
      padding: 10px;
      width: 70%;
      height: 350px;
      opacity: 1;
      border-radius: 5px;
      border: 1px solid white;
      display: inline-block;
      text-align: left;
      margin: 0 auto;
      z-index:-1;
      opacity: 0.8;
    }
    .fontnew {
    font-size: 18px;
    font-family: sans-serif;
    color: inherit;
    }
    hr.new1 {
    border: 1px solid white;
    }
    .containerTab {
      padding: 20px 20px;
      color: white;
      width: 700px;
      text-align: left;
      opacity: 0.8;
    }
    <!-- .closebtn {
      float: right;
      color: white;
      font-size: 35px;
      cursor: pointer;
    } -->
    .tooltip {
      position: relative;
      display: inline-block;
      border-bottom: 1px dotted black;
    }
    .tooltip .tooltiptext {
      visibility: hidden;
      width: 120px;
      background-color: black;
      color: #fff;
      text-align: center;
      border-radius: 6px;
      padding: 5px 0; 
      /* Position the tooltip */
      position: absolute;
      z-index: 1;
    }
    .tooltip:hover .tooltiptext {
      visibility: visible;
    }
    p {
    text-align: justify;
    }
</style>
<!-- <script src="https://kit.fontawesome.com/a076d05399.js"></script> -->
<script src="https://kit.fontawesome.com/a65c30b4bb.js" crossorigin="anonymous"></script>

<p>
Desiging a hackahton involves taking consideration of several important aspects depending on the organizational goals. We provides a list of important hackahton aspects which are then grouped into five main categories: <span style="color:#4285F4">projects</span>, <span style="color:#3b99a7">teams</span>, <span style="color:#78C257">process</span>, <span style="color:#F4B400">mentor</span>, and <span style="color:#DB4437">competition</span>.
</p>

<!-- <div id="cc"></div> -->
<!-- <p>Desiging a hackahton involves taking consideration of several important aspects depending on the organizational goals. We provides a list of important hackahton aspects which are then grouped into five main categories: <span style="color:#4285F4">projects</span>, <span style="color:#3b99a7">teams</span>, <span style="color:#78C257">process</span>, <span style="color:#F4B400">mentor</span>, and <span style="color:#DB4437">competition</span>.

<button type="button" name="btn1" class="round-button" style="left: 50px; top: 200px; background: #4285F4;"></button>
<i class="fas fa-briefcase" style="font-size:36px; left: 50px; top: 50px;" aria-hidden="true"></i>

<button type="button" name="btn2" class="round-button" style="left: 100px; top: 20px; background: #3b99a7;"></button>
<i class="fas fa-users" style="font-size:36px; left: 130px; top: 50px;" aria-hidden="true"></i>

<button type="button" name="btn2" class="round-button" style="left: 180px; top: 20px; background: #78C257;"></button>
<i class="fas fa-users" style="font-size:36px; left: 210px; top: 50px;" aria-hidden="true"></i>

<button type="button" name="btn2" class="round-button" style="left: 260px; top: 20px; background: #78C257;"></button>
<i class="fas fa-graduation-cap" style="font-size:36px; left: 290px; top: 50px;" aria-hidden="true"></i>

<button type="button" name="btn2" class="round-button" style="left: 340px; top: 20px; background: #78C257;"></button>
<i class="fas fa-medal" style="font-size:36px; left: 370px; top: 50px;" aria-hidden="true"></i>
</p> -->

<div align="center">
<svg height="250" width="700">
<a href="#p" onclick="openTab('p');">
  <circle cx="150" cy="150" r="50" stroke="#4285F4" stroke-width="3" fill="#4285F4" opacity="0.8" class="chover"/>
  <text class="fas fa-briefcase" x="150" y="160">&#xf0b1;</text>
</a>

<a href="#t" onclick="openTab('t');">
  <circle cx="230" cy="150" r="50" stroke="#3b99a7" stroke-width="3" fill="#3b99a7" opacity="0.8" class="chover"/>
  <text class="fas fa-users" x="230" y="160">&#xf0c0;</text>
</a>


<a href="#pr" onclick="openTab('pr');">
  <circle cx="310" cy="150" r="50" stroke="#78C257" stroke-width="3" fill="#78C257" opacity="0.8" class="chover"/>
  <text class="fas fa-chart-line" x="310" y="160">&#xf201;</text>
</a>

<a href="#m" onclick="openTab('m');">
  <circle cx="390" cy="150" r="50" stroke="#F4B400" stroke-width="3" fill="#F4B400" opacity="0.8" class="chover"/>
  <text class="fas fa-graduation-cap" x="390" y="160">&#xf19d;</text>
</a>

<a href="#c" onclick="openTab('c');">
  <circle cx="470" cy="150" r="50" stroke="#DB4437" stroke-width="3" fill="#DB4437" opacity="0.8" class="chover"/>
  <text class="fas fa-medal" x="470" y="168">&#xf5a2;</text>
</a>
</svg>
</div>

<!-- <div class="container">
  <div class="col fontnew" style="background: #4285F4;">
    <center>Projects<center><hr class="new1">
    <table>
    <tr>
      <td width="25%" style="vertical-align: top; line-height: 1.5;">Innovativeness</td>
      <td width="70%" style="vertical-align: top; line-height: 1.5;">The degree to which the project solves a real-world problem either creating new or reusing existing code</td>
    </tr>
    <tr>
      <td width="25%" style="vertical-align: top; line-height: 1.5;">Scope</td>
      <td width="70%" style="vertical-align: top; line-height: 1.5;">The degree to which the goals, tasks, and deliverables of the project are archivable within the specified time limit</td>
    </tr>
    <tr>
      <td width="25%" style="vertical-align: top; line-height: 1.5;">Technical complexity</td>
      <td width="75%" style="vertical-align: top; line-height: 1.5;">The degree to which the implemented system has the design or implementation that is difficult to understand and verify</td>
    </tr>
    <tr>
      <td width="25%" style="vertical-align: top; line-height: 1.5;">Content complexity</td>
      <td width="70%" style="vertical-align: top; line-height: 1.5;">The degree to which the requirements of the project are precise and complete</td>
    </tr>
    <tr>
      <td width="25%" style="vertical-align: top; line-height: 1.5;">Sustainability</td>
      <td width="75%" style="vertical-align: top; line-height: 1.5;">The degree to which the implemented system or code will be available to use and continue to be maintained even after the hackathon</td>
    </tr>
    </table>
  </div>
</div> -->

<!-- Option 1 start -->
<!-- <div align="center">
<div id="p" class="containerTab" style="display:none; background:#4285F4; border-radius:10%; font-size: 16px;">
  <center><h2>Projects</h2></center>
  <ul style="font-size: 16px;">
    <li>Innovativeness: The degree to which the project solves a real-world problem either creating new or reusing existing code</li>
    <li>Scope: The degree to which the goals, tasks, and deliverables of the project are archivable within the specified time limit</li>
    <li>Technical complexity: The degree to which the implemented system has the design or implementation that is difficult to understand and verify</li>
    <li>Content complexity: The degree to which the requirements of the project are precise and complete</li>
    <li>Sustainability: The degree to which the implemented system or code will be available to use and continue to be maintained even after the hackathon</li>
  </ul>
</div>
</div>

<div align="center">
<div id="t" class="containerTab" style="display:none; background:#3b99a7; border-radius: 10%; font-size: 16px;">
  <center><h2>Teams</h2></center>
  <ul style="font-size: 16px;">
    <li>Motivation(s): What participants want to get out of their hackathon participation</li>
    <li>Background(s): Participants' education and experience before the hackathon</li>
    <li>Skills: The degree to which participants are proficient in coding and designing</li>
    <li>Familiarity: The degree to which the team members have worked together before</li>
    <li>Role distribution; How roles or tasks are distributed among team members</li>
  </ul>
</div>
</div>

<div align="center">
<div id="pr" class="containerTab" style="display:none; background:#78C257; border-radius: 10%; font-size: 16px;">
  <center><h2>Process</h2></center>
  <ul style="font-size: 16px;">
    <li>Pre-hackathon events: Agenda of activities that take place before the hackathons as individually or a team</li>
    <li>Ideation: Teams generating, developing, and combining ideas to form the projects</li>
    Project selection: Teams picking projects to work on during the hackathon<br>
    <li>Checkpoints and Scoping: Teams reporting the progress of the project to the wholeand re-evaluating the project scope</li>
    <li>Duration / Breaks: Mini-events such as games during the hackathon</li>
    <li>Post-hackathon follow-up: Agenda of activities that help the continuation of hackathon projects</li>
  </ul>
</div>
</div>

<div align="center">
<div id="m" class="containerTab" style="display:none; background:#F4B400; border-radius: 10%; font-size: 16px;">
  <center><h2>Mentors</h2></center>
  <ul style="font-size: 16px;">
    <li>Engagement with teams: Explaining projects to the participants, teaching them basic computing skills required for their projects, and helping them with the development environment setup</li>
    <li>Technical support: Helping teams / participants to solve their technical difficulties during the hackathon</li>
    <li>Project feedback: Providing feedback on how well the team is making progress on their projects so the teams can assure that they are on the right track</li>
    <li>Mobile vs embedded: </li>
  </ul>
</div>
</div>

<div align="center">
<div id="c" class="containerTab" style="display:none; background:#DB4437; border-radius: 10%; font-size: 16px;">
  <center><h2>Competition</h2></center>
  <ul style="font-size: 16px;">
  <li>Competitive vs Non-competitive events: Incentive mechanism of the hackathon. In competitive hackathons, teams compete for prizes. In non-competitive hackathons, teams work toward a common goal such as contributing code to advance existing or create new computing infrastructure.<br>
  Judging criteria: This refers to criteria used by the judges to evaluate the hackathon projects such as creativity and appeal to the market</li>
  <li>Prizes: How many awards be given</li>
  <li>Monetary vs non-monetary prizes: Should the prizes be monetary or non-monetary such as computing power</li>
  <li>Jury vs popular vote: The voting system by which the winner(s) is decided for the hackathon. In jury system, the winner is elected only when the majority of judges have voted for them. In popular vote, the team which received a majority vote from the event attendees and pre-specified social channels is elected as the winner</li>
  </ul>
</div>
</div>

<script>
function openTab(tabName) {
  var i, x;
  x = document.getElementsByClassName("containerTab");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  document.getElementById(tabName).style.display = "block";
}
</script> -->

<!-- Option 1 ends -->


<!-- Option 2 starts -->
<!-- <div align="center">
<table>
  <tr>
    <td>
    <svg width="100" height="100">
      <circle cx="50" cy="50" r="20" stroke="#4285F4" stroke-width="3" fill="#4285F4" opacity="0.8"/>
      <text x="50" y="55" style="font-size:18px; fill:white; text-anchor:middle;">01</text>
    </svg>
    </td>
    <td>
      Projects
      <ul>
        <li>Innovativeness</li>
        <li>Scope</li>
      </ul>
    </td>
  </tr>
<table>
</div> -->

<div align="center">
<svg height="200" width="700">
  <g>
      <circle cx="50" cy="50" r="20" stroke="#4285F4" stroke-width="3" fill="#4285F4" opacity="0.8"/>
      <text x="50" y="55" style="font-size:18px; fill:white; text-anchor:middle; font-family:sans-serif;">01</text>
      <text x="120" y="50" style="font-size:16px; text-anchor:left; font-family:sans-serif;">Projects</text>
      <circle cx="95" cy="65" r="2px"/>
      <text x="155" y="70" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Innovativeness</text>
      <circle cx="95" cy="85" r="2px"/>
      <text x="130" y="90" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Scope</text>
      <circle cx="95" cy="105" r="2px"/>
      <text x="175" y="110" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Technical complexity</text>
      <circle cx="95" cy="125" r="2px"/>
      <text x="170" y="130" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Content complexity</text>
      <circle cx="95" cy="145" r="2px"/>
      <text x="150" y="150" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Sustainability</text>
  </g>
  <g>
      <circle cx="400" cy="50" r="20" stroke="#3b99a7" stroke-width="3" fill="#3b99a7" opacity="0.8"/>
      <text x="400" y="55" style="font-size:18px; fill:white; text-anchor:middle; font-family:sans-serif;">02</text>
      <text x="460" y="50" style="font-size:16px; text-anchor:left; font-family:sans-serif;">Teams</text>
      <circle cx="440" cy="65" r="2px"/>
      <text x="500" y="70" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Motivation(s)</text>
      <circle cx="440" cy="85" r="2px"/>
      <text x="505" y="90" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Background(s)</text>
      <circle cx="440" cy="105" r="2px"/>
      <text x="480" y="110" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Skill(s)</text>
      <circle cx="440" cy="125" r="2px"/>
      <text x="490" y="130" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Familiarity</text>
      <circle cx="440" cy="145" r="2px"/>
      <text x="510" y="150" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Role distribution</text>
  </g>
</svg>
</div>

<div align="center">
<svg height="250" width="900">
  <g>
      <circle cx="25" cy="25" r="20" stroke="#78C257" stroke-width="3" fill="#78C257" opacity="0.8"></circle>
      <text x="25" y="30" style="font-size:18px; fill:white; text-anchor:middle; font-family:sans-serif;">03</text>
      <text x="90" y="25" style="font-size:16px; text-anchor:left; font-family:sans-serif;">Process</text>
      <circle cx="65" cy="40" r="2px"></circle>
      <text x="155" y="45" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Pre-hackathon (events)</text>
      <circle cx="65" cy="60" r="2px"></circle>
      <text x="105" y="65" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Ideation</text>
      <circle cx="65" cy="80" r="2px"></circle>
      <text x="130" y="85" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Team formation</text>
      <circle cx="65" cy="100" r="2px"></circle>
      <text x="135" y="105" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Project selection</text>
      <circle cx="65" cy="120" r="2px"></circle>
      <text x="145" y="125" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Scoping checkpoints</text>
      <circle cx="65" cy="140" r="2px"></circle>
      <text x="135" y="145" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Duration / Breaks</text>
      <circle cx="65" cy="160" r="2px"></circle>
      <text x="160" y="165" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Post-hackathon follow-up</text>
  </g>
  <g>
      <circle cx="300" cy="25" r="20" stroke="#F4B400" stroke-width="3" fill="#F4B400" opacity="0.8"></circle>
      <text x="300" y="30" style="font-size:18px; fill:white; text-anchor:middle; font-family:sans-serif;">04</text>
      <text x="365" y="25" style="font-size:16px; text-anchor:left; font-family:sans-serif;">Mentors</text>
      <circle cx="340" cy="40" r="2px"></circle>
      <text x="430" y="45" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Engagement with teams</text>
      <circle cx="340" cy="60" r="2px"></circle>
      <text x="410" y="65" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Technical support</text>
      <circle cx="340" cy="80" r="2px"></circle>
      <text x="410" y="85" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Project feedback</text>
      <circle cx="340" cy="100" r="2px"></circle>
      <text x="420" y="105" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Mobile vs Embedded</text>
  </g>
  <g>
    <circle cx="600" cy="25" r="20" stroke="#DB4437" stroke-width="3" fill="#DB4437" opacity="0.8"></circle>
    <text x="600" y="30" style="font-size:18px; fill:white; text-anchor:middle; font-family:sans-serif;">05</text>
    <text x="680" y="25" style="font-size:16px; text-anchor:left; font-family:sans-serif;">Competition</text>
    <circle cx="640" cy="40" r="2px"></circle>
    <text x="770" y="45" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Competitive vs Non-competitive events</text>
    <circle cx="640" cy="60" r="2px"></circle>
    <text x="700" y="65" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Judging criteria</text>
    <circle cx="640" cy="80" r="2px"></circle>
    <text x="680" y="85" style="font-size:14px; text-anchor:left; font-family:sans-serif;"># Prizes</text>
    <circle cx="640" cy="100" r="2px"></circle>
    <text x="740" y="105" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Monetary vs Non-monetary</text>
    <circle cx="640" cy="120" r="2px"></circle>
    <text x="720" y="125" style="font-size:14px; text-anchor:left; font-family:sans-serif;">Jury vs Popular vote</text>
  </g>
</svg>
</div>
<!-- Option 2 ends -->
<!-- <p id="desc"></p>
<script>
</script> -->

<!-- Don't remove this table! -->
<!-- <table>
<tr style="border-bottom: thin dotted grey;">
  <th style="font-size:1.2em; width:30%"><strong>Aspects</strong></th>
  <th style="font-size:1.2em; width:70%"><strong>Description</strong></th>
</tr>

<tr>
  <td style="colspan:2; font-size:1.2em;"><strong>Projects</strong></td>
</tr>

<tr>
  <td style="width:30%"><strong>Innovativeness</strong></td>
  <td style="width:70%">This refers the degree to which the project solves a real-world problem either creating new or reusing existing code.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Scope</strong></td>
  <td style="width:70%">This refers to the degree to which the goals, tasks, and deliverables of the project are archivable within the specified time limit.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Technical complexity</strong></td>
  <td style="width:70%">This refers to the degree to which the implemented system has the design or implementation that is difficult to understand and verify.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Content complexity</strong></td>
  <td style="width:70%">This refers to the degree to which the requirements of the project are precise and complete.</td>
</tr>

<tr style="border-bottom: thin dotted grey;">
  <td style="width:30%"><strong>Sustainability</strong></td>
  <td style="width:70%">This refers to the degree to which the implemented system or code will be available to use and continue to be maintained even after the hackathon.</td>
</tr>

<tr>
  <td style="colspan:2; font-size:1.2em;"><strong>Teams</strong></td>
</tr>

<tr>
  <td style="width:30%"><strong>Motivation(s)</strong></td>
  <td style="width:70%">This refers to what the participants want to get out of their
  hackathon participation such as career, learning, get the needed work done, and meet new people.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Background(s)</strong></td>
  <td style="width:70%">This refers to the participants' education and experience before the hackathon.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Skills</strong></td>
  <td style="width:70%">This refers to the degree to which participants are proficient in coding and designing.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Familiarity</strong></td>
  <td style="width:70%">This refers to the degree to which the team members have worked together before.</td>
</tr>

<tr style="border-bottom: thin dotted grey;">
  <td style="width:30%"><strong>Role distribution</strong></td>
  <td style="width:70%">This refers to how roles or tasks are distributed among team members, e.g., by interest, available skills, preparation, and mentorship.</td>
</tr>

<tr>
  <td style="colspan:2; font-size:1.2em;"><strong>Process</strong></td>
</tr>

<tr>
  <td style="width:30%"><strong>Pre-hackathon events</strong></td>
  <td style="width:70%">This refers to the agenda of activities that take place before the hackathons as individually or a team. These activities include ideation, construction of project vision, common plan and shared understanding, and the dissemination feedback and information.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Ideation</strong></td>
  <td style="width:70%">This refers to the teams generating, developing, and combining ideas to form the projects. This can be done before or at the event.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Team formation</strong></td>
  <td style="width:70%">This refers to forming teams to work together in the hackathon. Team formation can be done before or at the event. In most hackathons, teams are formed around the projects.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Project selection</strong></td>
  <td style="width:70%">This refers to teams picking out projects to work on during the hackathon. This can be done in concert with team formation and before or at the event.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Checkpoints and Scoping</strong></td>
  <td style="width:70%">This refers to reporting the progress of the project and re-evaluating the project scope.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Duration / Breaks</strong></td>
  <td style="width:70%">This refers to mini-events such as games during the hackathon. The purpose is for participants to have fun or mingle with fellow participants while taking a break from their hackathon projects.</td>
</tr>

<tr style="border-bottom: thin dotted grey;">
  <td style="width:30%"><strong>Post-hackathon follow-up</strong></td>
  <td style="width:70%">This refers to agenda of activities that help the continuation of hackathon projects.</td>
</tr>

<tr>
  <td style="colspan:2; font-size:1.2em;"><strong>Mentors</strong></td>
</tr>

<tr>
  <td style="width:30%"><strong>Engagement with teams</strong></td>
  <td style="width:70%">This refers to explaining projects to the participants, teaching them basic computing skills required for their projects, and helping them with the development environment setup.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Technical support</strong></td>
  <td style="width:70%">This refers to helping participants to solve their technical difficulties during the hackathon.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Project feedback</strong></td>
  <td style="width:70%">This refers to mentors providing feedback on how well the team is making progress on their projects so the teams can assure that they are on the right track.</td>
</tr>

<tr style="border-bottom: thin dotted grey;">
  <td style="width:30%"><strong>Mobile vs embedded</strong></td>
  <td style="width:70%"></td>
</tr>

<tr>
  <td style="colspan:2; font-size:1.2em;"><strong>Competition</strong></td>
</tr>

<tr>
  <td style="width:30%"><strong>Competitive vs Non-competitive events</strong></td>
  <td style="width:70%">This refers to the incentive mechanism of the hackathon. In competitive hackathons, teams compete for prizes. In non-competitive hackathons, teams work toward a common goal such as contributing code to advance existing or create new computing infrastructure.</td>
</tr>

<tr>
  <td style="width:30%"><strong>Judging criteria</strong></td>
  <td style="width:70%">This refers to criteria used by the judges to evaluate the hackathon projects such as creativity and appeal to the market.</td>
</tr>

<tr>
  <td style="width:30%"><strong># Prizes</strong></td>
  <td style="width:70%"></td>
</tr>

<tr>
  <td style="width:30%"><strong>Monetary vs non-monetary prizes</strong></td>
  <td style="width:70%">This refers to an award(s) given to the winner(s) of the event. The prizes could be monetary or non-monetary such as computing power.</td>
</tr>

<tr style="border-bottom: thin dotted grey;">
  <td style="width:30%"><strong>Jury vs popular vote</strong></td>
  <td style="width:70%">This refers to the voting system by which the winner(s) is decided for the hackathon. In jury system, the winner is elected only when the majority of judges have voted for them. In popular vote, the team which received a majority vote from the event attendees and pre-specified social channels is elected as the winner.</td>
</tr>
</table> -->

# Test Plan // OCAS Application Form

## Objective

Our objective is to identify points of friction and potential barriers to completion in the web form beginning at <https://www.ontariocolleges.ca/en>.

### Scope

We will be collecting data from observing and recording sessions with on-site users. These users will be drawn from our available pool of post-graduate students. We will be testing the English language version of the form in the latest version of Chrome, on Windows desktop computers, along with a control group using a recent Android<sup><a target="_self" href="#footnote1">1</a></sup> handheld device. We will provide data from a control group using keyboard-only navigation. 

We <em>may</em> provide an automated accessibility report<sup><a target="_self" href="#footnote2">2</a></sup>. 

## Methods

15 participants will be divided into 3 groups - mobile, desktop with keyboard and mouse, and desktop with keyboard only. 

For the two desktop groups, data will be collected via screen capture software and eye-tracking hardware/software. 

For all groups, tasks will be evaluated via a PURE rubric. 

### Metrics

1. Task evaluation via PURE rubric
2. System Usability Scale<sup><a href="#footnote8" target="_self">8</a></sup>
3. Eyetracking heatmap
4. Time-to-completion
5. Success rate
6. Error rate

### Scenario

Start by searching for (1) a program offered by Humber to apply for, and (2) a college to apply to in the [OCAS UAT site](https://www.uat.ontariocolleges.ca/en). You don't have to register right now to first ‘explore’ program options.  

<em>NOTE: The idea that you have to research for programs and _then_ log in and re-find the programs is a known issue with the system. It is not necessary to provide feedback on this.</em> 

Find a few programs you would like to apply to. You should be applying to college as if you have never applied before. You should be applying as yourself and use all your own information (see the note below for exceptions). All the data collected will be erased.

<em>NOTE: If You have a pre-existing account with a gmail address, add a +[test] sign after your username, and change your birthday.</em>

<em>NOTE: Users may not understand at this point that you need to log in. If they haven't, direct them to.</em>

You can attempt to find where you would like to apply, but when you do the system will take you to the live site (not the test environment, this is a known bug) which we need to avoid.  You will need to redirect yourself to: https://applicantlogin.uat.ontariocolleges.ca/en/Account/Register. <strong>It is very important that You always ensure You see “UAT” in your browsers url.</strong>

When you get to the payment stage you can use 4242424242424242 to make a VISA payment. This only works in the UAT environment. You can put in any name and any expiry date.

Once payment is made you will need to log in to the UAT environment at https://applicantlogin.uat.ontariocolleges.ca/ as a ‘different’ user. Give the username HumberJune<code>${1-25}</code>@test.ocas.ca and use the following password: <code>Test123!A</code> 

<em>NOTE: The reason that account was created was because the UAT system can’t automatically generate offers. Once a student has applied and paid you need to log out and go back to the “uat” login page and log in using your assigned HumberTest account.</em>

### Tasks

TBD<sup><a target="_self" href="#footnote4">5</a></sup>

After completing a task at the mid-point of the form<sup><a target="_self" href="#footnote6">6</a></sup>, they will be asked to close their browser session for at least 20 seconds. Following this, the test moderator will have them begin again at the start page, and ask them to resume their application.

### Roles

Each group will have five (5) participants and at least three (3) test administrators. Of the administrators, one will be designated as the moderator. The moderator will liase with the participant, be available to guide them, and address any of their questions or technical issues. The remaining two (2) or more administrators will track the participant's progress through the scenario, rating the participant's ease-of-use for each identified task on the PURE ranking scale.

### Participants

Individual participants have yet to be identified as of this writing (28/05/18). Once they are selected<sup><a target="_self" href="#footnote4">4</a></sup>, their demographic information will be recorded here.

Participants are post-graduate certificate students. Efforts have been been made to find a diverse group, including participants from various cultural and socio-economic backgrounds, varying levels of English fluency, and people of different genders. 

### Equipment 

In a mobile lab, outfitted with fully enclosed cubicles for users and mirrored displays for observers. Computers are Windows<sup><a target="_self" href="#footnote7">7</a></sup> machines running Chrome<sup><a target="_self" href="#footnote7">7</a></sup> as the browser client.

Screen capture software used is Morae<sup><a target="_self" href="#footnote7">7</a></sup>, and eye-tracking hardware/software is Tobii<sup><a target="_self" href="#footnote7">7</a></sup>. 

### Location

The mobile usability lab is located on the Humber College North Campus, except when it mysteriously disappears.

### Schedule

Sessions will occur Wednesdays from 1:30-4:10, and Thursdays from 11:40-2:30, May 30th-June 20th, 2018.

## TODO

<ol>
	<li id="footnote1">Is this what we're doing?</li>
	<li id="footnote2">Will we?</li>
	<li id="footnote3">Add this as an appendix when available</li>
	<li id="footnote4">Participants and their information</li>
	<li id="footnote5">Determine tasks</li>
	<li id="footnote6">Determine save point</li>
	<li id="footnote7">Determine version</li>
	<li id="footnote8">_Which_ SUS?</li>
</ol>
---
title: Example Form
description: Example form I am building based on working in a nursery.
date: 2023-03-12
tags: Example form
---
<h1 class="title">Child Food Allergy Form</h1>
		<fieldset class="field1">
	<form data-netlify="true" name="contact" method="post">
	<label class="sr-only">First Name</label>
	<input type="text" id="first-name" name="first-name" required/>
	<br>
    <label class="sr-only">Surname</label>
	<input type="text" name="surname-name" required/>
	<br>
    <label for="email" label class="sr-only"> Email: </label>
	<input id="email" name="email" type="email" required/>
	<br>
    <label class="sr-only">Your Child's Name</label>
    <input type="text" name="childs-name" required/>
	</fieldset>
	<br>
	<fieldset class="field2">
	<h2 for="days-attended" class="sr-only">Please select the days your child attends nursery</h2>
	<label for="Monday"><input id="Monday" type="checkbox" name="Monday"/> Monday</label>
	<br>
	<label for="Tuesday"><input id="Tuesday" type="checkbox" name="Tuesday"/> Tuesday</label>
	<br>
	<label for="Wednesday"><input id="Wednesday" type="checkbox" name="Wednesday"/> Wednesday</label>
	<br>
	<label for="Thursday"><input id="Thursday" type="checkbox" name="Thursday"/> Thursday</label>
	<br>
	<label for="Friday"><input id="Friday" type="checkbox" name="Friday"/> Friday</label>
	</fieldset>
	<br>
	<fieldset class="field2">
	<h2 for="allergies" class="sr-only">Please select the allergins that affect you child from the list below</h2>
	<br>
	<label for="dairy"><input id="dairy" type="checkbox" name="dairy"/> Dairy</label>
	<br>
	<label for="eggs"><input id="eggs" type="checkbox" name="eggs"/> Eggs</label>
	<br>
	<label for="Nuts"><input id="Nuts" type="checkbox" name="Nuts"/> Nuts</label>
	<br>
	<label for="shellfish"><input id="shellfish" type="checkbox" name="shellfish"/> Shellfish</label>
	</fieldset>
	<br>
	<input class="butt" type="submit"/>
	</form>
{{ content | safe }}

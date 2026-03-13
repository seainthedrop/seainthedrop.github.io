---
permalink: /contact/
title: "Contact"
layout: single
author_profile: true
---
  
<form 
	action="" 
	method="POST" 
> 
	<label name="Full Name">Full Name</label> 
	<input type="text" name="Full Name" placeholder="Full Name" required="true" maxlength="100"/>

	<label name="Email">Email</label> 
	<input type="email" name="Email" placeholder="Email" required="true" maxlength="100"/>

	<label name="Message">Message</label> 
	<input type="text" name="Message" placeholder="Message (240 char max)" required="true" maxlength="240"/>

	<!-- override the redirect URL -->
	<input type="hidden" name="_gs_override_redirect_url"
	value="https://www.seainthedrop.com/thankyou/"/>
			 
	<input type="submit" value="Submit" /> 
</form>

---
permalink: /contact/
title: "Contact"
layout: single
author_profile: true
---
  
<form 
	action="https://gdsht.app/s/4249da1b2c2f47f0b4f5ec872a82b0e0" 
	method="POST" 
> 
	<label name="Full Name">Full Name</label> 
	<input type="text" name="Full Name" placeholder="Full Name" required="true" maxlength="100"/>

	<label name="Email">Email</label> 
	<input type="email" name="Email" placeholder="Email" required="true" maxlength="100"/>

	<label name="Message">Message</label> 
	<input type="text" name="Message" placeholder="Brief Message" required="true" maxlength="200"/>

	<!-- override the redirect URL -->
	<input type="hidden" name="_gs_override_redirect_url"
	value="https://www.seainthedrop.com/thankyou/"/>
			 
	<input type="submit" value="Submit" /> 
</form>

Hi {{username}},

Thank you for reporting this to us. In order for CSRF to be a valid issue it must affect some important action such as deleting one's account. The CSRF that you have reported to us does not affect anything important, therefore we do not believe that this requires an immediate fix.

One good way of finding valid CSRF vulnerabilities is to create a map of the various functionality and then checking the actions that could have a significant impact on the user.

When constructing the proof of concept always make sure the code is clear and well formatted. Something along these lines allows the team to easily verify the impact of the issue:

```
<form action="http://example.com/settings" method="POST">
   
   <!-- Victim's username -->
   <input type="hidden" name="username" value="example"/>

   <!-- Victim's password -->
   <input type="hidden" name="password" value="password1234"/>
	
   <!-- Click this button to perform the action -->   
   <input type="submit" value="Click me"/>

</form>
```

Then when designing a real-world example, either hide the form (`style="display:none;"`) and make it auto submit, or design it so that it resembles a component from the target's page.

Good luck and keep up the good work!

{{triager}}
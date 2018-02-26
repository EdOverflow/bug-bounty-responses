# Ability to create external links
```
Thank you for reporting a potential issue to us. Currently, we do not plan on changing this behaviour. The ability to create external links is a fundamental part of the web and users are educated to wary of what they click on while browsing.

Keep up the good work and we look forward to more reports from you in the future!
```

# Brute-force attack
```
Thank you very much for your report. We generally do not accept these type of reports. We are aware that other bug bounty programs might interpret this issue differently, but we have accepted the low risk that brute-force attacks pose.

On a side note, we highly recommend you take a look at _["Web Hacking 101"](https://leanpub.com/web-hacking-101)_ by Peter Yaworski and _["Breaking into Information Security: Learning the Ropes 101"](https://leanpub.com/ltr101-breaking-into-infosec)_ by Andy Gill to get a better idea of the type of issues that we are looking for.

Keep up the good work and we look forward to more reports from you in the future!
```

# Clickjacking on static website
```
Thank you for reporting this to us. The page in question is static, therefore clickjacking does not pose any risk. Clickjacking becomes an issue whenever the page is dynamic and enable a user/attacker to perform sensitive actions such as deleting one's account.

One good way of finding valid clickjacking vulnerabilities is to create a map of the various functionality and then checking the actions that could have a significant impact on the user.

Keep up the good work and we look forward to more reports from you in the future!
```

# Content injection
```
Thank you very much for your report. We generally do not accept content injection reports. The severity of this issue is so low that it does not warrant an immediate fix. We are aware that other bug bounty programs might interpret this issue differently, but we have accepted the low risk that content injection poses.

On a side note, we highly recommend you take a look at _["Web Hacking 101"](https://leanpub.com/web-hacking-101)_ by Peter Yaworski and _["Breaking into Information Security: Learning the Ropes 101"](https://leanpub.com/ltr101-breaking-into-infosec)_ by Andy Gill to get a better idea of the type of issues that we are looking for.

Keep up the good work and we look forward to more reports from you in the future!
```

# Cross-site tracing
```
In order for Cross-Site Tracing (XST) to really be a significant issue you would need to find an endpoint vulnerable to Cross-site Scripting (XSS). If you do find XSS, please notify us, and we will accept this report.

Keep up the good work and we look forward to seeing what you find in the future!
```

# CSP uses `unsafe-inline`
```
Thank you for submitting a report. The fact that our CSP includes `unsafe-inline` is not an issue in itself. In order for you to demonstrate the actual impact of this value, I highly recommend you look for an XSS vulnerability. Try to trigger `alert(document.domain)`. We will accept this report if you can find a way of actually exploiting this potential issue with XSS.

Keep up the good work and we look forward to seeing what you find in the future!
```

# CSRF with minimal security implications
```
Thank you for reporting this to us. In order for CSRF to be a valid issue it must affect some important action such as deleting one's account. The CSRF that you have reported to us does not affect anything important, therefore we do not believe that this requires an immediate fix.

One good way of finding valid CSRF vulnerabilities is to create a map of the various functionality and then checking the actions that could have a significant impact on the user.

When constructing the proof of concept always make sure the code is clear and well formatted. Something along these lines allows the team to easily verify the impact of the issue:

~~~html
<form action="http://example.com/settings" method="POST">
   
   <!-- Victim's username -->
   <input type="hidden" name="username" value="example"/>

   <!-- Victim's password -->
   <input type="hidden" name="password" value="password1234"/>
	
   <!-- Click this button to perform the action -->   
   <input type="submit" value="Click me"/>

</form>
~~~

Then when designing a real-world example, either hide the form (`style="display:none;"`) and make it auto submit, or design it so that it resembles a component from the target's page.

Good luck and keep up the good work!
```

# CSV injection
```
Thank you for the report. We do not believe that this issue has a sufficient impact on our users. In our view, this is an issue that products such as Excel should take care of. We are aware that other bug bounty programs might interpret this issue differently, but we have accepted the low risk that CSV injection poses.

Keep up the good work and we look forward to more reports from you in the future!
```

# Disclosure of `robots.txt` file
```
Thank you for reporting this to us. We are aware that in some cases robots.txt files have been known to disclose sensitive information. In our case we have determined that our robots.txt file does not contain any information that poses a potential security risk. That being said, keep up the good work and we look forward to more reports from you in the future!
```

# Email spoofing
```
Thank you for notifying use about this potential issue. We have accepted the risk that this issue poses and do not believe that it warrants an immediate fix.

Keep up the good work and we look forward to more reports from you in the future!
```

# Error message
```
We have determined that the error message does not contain information that poses a potential security risk. We really appreciate you taking the time to report something to us and we highly recommend to always verify the contents of an error message to ensure that it really is a security issue. If you are not very familiar with the error message or the technology being used, a quick Google search can usually help.

Keep up the good work and we look forward to more reports from you in the future!
```

# IDN homograph attack
```
While this is a classis phishing technique, we do not consider IDN homograph attacks to be a significant threat and do not plan on addressing this concern at the moment.

On a side note, we highly recommend you take a look at _["Web Hacking 101"](https://leanpub.com/web-hacking-101)_ by Peter Yaworski and _["Breaking into Information Security: Learning the Ropes 101"](https://leanpub.com/ltr101-breaking-into-infosec)_ by Andy Gill to get a better idea of the type of issues that we are looking for.

We look forward to more reports from you in the future!
```

# JavaScript error
```
We appreciate the fact that you took the time to report this to us. The JavaScript error does not disclose any sensitive information, therefore we do not plan on fixing this anytime soon. Always make sure that when you believe you have encountered some form of information disclosure to double-check that the information is in fact sensitive. If you are not very familiar with the error message or the technology being used, a quick Google search can usually help.

Keep up the good work and we look forward to more reports from you in the future!
```

# Leaking non-sensitive information on search engine results
```
The result does not appear to disclose any sensitive information that could potentially affect us or our customers. That being said, we really appreciate you taking the time to report something to us and we highly recommend to always verify the contents of what you find to ensure that it really is a security issue.

Keep up the good work and we look forward to more reports from you in the future!
```

# Missing security headers
```
The missing header in question does not pose a significant risk, therefore we do not plan on addressing this issue at the moment.

On a side note, we highly recommend you take a look at _["Web Hacking 101"](https://leanpub.com/web-hacking-101)_ by Peter Yaworski and _["Breaking into Information Security: Learning the Ropes 101"](https://leanpub.com/ltr101-breaking-into-infosec)_ by Andy Gill to get a better idea of the type of issues that we are looking for.

Keep up the good work and we look forward to more reports from you in the future!
```

# No notification on event
```
We have determined that this event does not require any notifications and that the risk of having no notification is not significant enough to warrant an immediate fix.

On a side note, we highly recommend you take a look at _["Web Hacking 101"](https://leanpub.com/web-hacking-101)_ by Peter Yaworski and _["Breaking into Information Security: Learning the Ropes 101"](https://leanpub.com/ltr101-breaking-into-infosec)_ by Andy Gill to get a better idea of the type of issues that we are looking for.

Happy hacking and make sure to report back if you find anything interesting.
```

# Non-sensitive file disclosure
```
The file that you listed above does not appear to disclose any sensitive information that could potentially affect us or our customers. That being said, we really appreciate you taking the time to report something to us and we highly recommend to always verify the contents of a file to ensure that it really is a security issue.

On a side note, we highly recommend you take a look at _["Web Hacking 101"](https://leanpub.com/web-hacking-101)_ by Peter Yaworski and _["Breaking into Information Security: Learning the Ropes 101"](https://leanpub.com/ltr101-breaking-into-infosec)_ by Andy Gill to get a better idea of the type of issues that we are looking for.

Keep up the good work and we look forward to more reports from you in the future!
```

# No proof of concept
```
Thank you very much for your report. Would it be possible to provide us with a detailed proof of concept (preferably code) that demonstrates the issue? Unfortunately, without a proof of concept it is very difficult for us to determine what the actual issue is.
```

# No rate limiting
```
Thank you for notifying us about this potential issue. We have accepted the risk that this issue poses and do not believe that it warrants an immediate fix.

On a side note, we highly recommend you take a look at _["Web Hacking 101"](https://leanpub.com/web-hacking-101)_ by Peter Yaworski and _["Breaking into Information Security: Learning the Ropes 101"](https://leanpub.com/ltr101-breaking-into-infosec)_ by Andy Gill to get a better idea of the type of issues that we are looking for.

Keep up the good work and we look forward to more reports from you in the future!
```

# Open redirect using `Host` header
```
Thank you for reporting this to us. Open redirects in the `Host` header are not exploitable therefore currently we do not see a reason to change this behaviour. That being, said if you do find a way to really exploit this in a way that could affect us and/or our users, please do report back to us.

Keep up the good work and we look forward to more reports from you in the future!
```

# Outdated library
```
Thank you very much for your report. Would it be possible to provide us a proof of concept (preferably code) that exploits the issue(s) found in this library? We are struggling to determine the severity of this issue and a proof of concept would be a big help.
```

# Reverse tabnabbing
```
Thank you for notifying use about this potential issue. We have accepted the risk that this issue poses, since the attack you described does not affect most modern browsers. Therefore, we do not plan on changing this behaviour at the moment.

Keep up the good work and we look forward to more reports from you in the future!
```

# Server version disclosure
```
Thank you very much for your report. We do not plan on changing this behaviour since we are perfectly happy with disclosing details about what web server we are running.

Keep up the good work and we look forward to more reports from you in the future!
```

# Specific HTTP method enabled
```
We would like to thank you for reporting this potential issue to us. Based on our assessment of your finding, we believe that the severity of this issue does not warrant an immediate fix.

On a side note, we highly recommend you take a look at _["Web Hacking 101"](https://leanpub.com/web-hacking-101)_ by Peter Yaworski and _["Breaking into Information Security: Learning the Ropes 101"](https://leanpub.com/ltr101-breaking-into-infosec)_ by Andy Gill to get a better idea of the type of issues that we are looking for.

Keep up the good work and we look forward to more reports from you in the future!
```

# SPF misconfiguration
```
Thank you for notifying us about this potential issue. We have accepted the risk that the SPF misconfiguration poses and do not believe that it warrants an immediate fix.

Keep up the good work and we look forward to more reports from you in the future!
```

# Sub-domain takeover false positive
```
Thank you for the report. Unfortunately, this appears to be a false positive. We are currently unable to find a way of claiming this sub-domain. You have our permission to attempt to take over the sub-domain. To verify the issue, simply upload the following proof of concept: https://github.com/EdOverflow/bugbountyguide/blob/master/files/sub-domain_takeover.html. If you are able to find a way, please report back and we will accept your report.

Have fun!
```

# Target does not belong to bug bounty program
```
It appears that you have found a potential issue on an endpoint that does not belong to us. We highly recommend trying to get in touch with {{vendor}}'s security team about your finding. Their security policy can be found here: {{security_page}}.
```

# Weak password policy
```
Thank you for notifying us about this potential issue. We have accepted the risk that this issue poses and do not believe that it warrants an immediate fix.

On a side note, we highly recommend you take a look at _["Web Hacking 101"](https://leanpub.com/web-hacking-101)_ by Peter Yaworski and _["Breaking into Information Security: Learning the Ropes 101"](https://leanpub.com/ltr101-breaking-into-infosec)_ by Andy Gill to get a better idea of the type of issues that we are looking for.

Keep up the good work and we look forward to more reports from you in the
future!
```

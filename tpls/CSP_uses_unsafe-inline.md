Hi {{username}},

Thank you for submitting a report. The fact that our CSP includes `unsafe-inline` is not an issue in itself. In order for you to demonstrate the actual impact of this value, I highly recommend you look for an XSS vulnerability. Try to trigger `alert(document.domain)`. We will accept this report if you can find a way of actually exploiting this potential issue with XSS.

Keep up the good work and we look forward to seeing what you find in the future!

{{triager}}
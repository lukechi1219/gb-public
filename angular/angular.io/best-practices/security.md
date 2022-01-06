---
description: .
---

# security

.

This topic describes Angular's built-in protections against **common web-application vulnerabilities** and attacks such as cross-site scripting attacks. <mark style="color:yellow;">It doesn't cover application-level security</mark>, such as <mark style="color:green;">authentication and authorization</mark>.

For more information about the attacks and mitigations described below, see [OWASP Guide Project](https://www.owasp.org/index.php/Category:OWASP\_Guide\_Project).

You can run the [live example](https://angular.io/generated/live-examples/security/stackblitz.html)/[download example](https://angular.io/generated/zips/security/security.zip) in Stackblitz and download the code from there.



For more information about how Google handles security issues, see [Google's security philosophy](https://www.google.com/about/appsecurity/).



#### BEST PRACTICES

* **Keep current with the latest Angular library releases.** We regularly update the Angular libraries, and these updates might fix security defects discovered in previous versions. Check the Angular [changelog](https://github.com/angular/angular/blob/master/CHANGELOG.md) for security-related updates.
* **Avoid Angular APIs marked in the documentation as “**_**Security Risk**_**.”** For more information, see the [Trusting safe values](https://angular.io/guide/security#bypass-security-apis) section of this page.

.

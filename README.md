# Cross-Frame-Scripting

## Cross-Frame-Scripting
### Abstract
Failure to restrict inclusion of an application within an iframe can lead to cross-site request forgery or phishing attacks.
### Explanation
Cross-frame scripting vulnerabilities occur when an application:

1. Allows itself to be included inside an iframe.
2. Fails to specify framing policy via the X-Frame-Options header.
3. Uses poor protection, such as JavaScript-based frame busting logic.

Cross-frame scripting vulnerabilities often form the basis of clickjacking exploits that attackers may use to conduct cross-site request Forgery or phishing attacks.

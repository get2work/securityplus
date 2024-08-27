# Cross-Site Scripting (XSS)

Web security vulnerability where malicious scripts are injected into web pages viewed by other users 

Steps of a Cross-Site Scripting attack:
1. Attacker identifies an input validation vulnerability within a trusted website
2. Attacker crafts a URL to perform code injection against the trusted website
3. The trusted site returns a page containing the malicious code injected
4. Malicious code runs in the client's browser with permission level as the trusted site

Breaks the browser's security and trust model

Anytime you see a url or something with <script> or any kind of javascript its going to be a cross-site scripting attack

if you see Document.cookie or document.write its a [[Document Object Model (DOM) XSS]]

# Non-Persistent XSS

This type of attack only occurs when it's launched and happens once

# Persistent XSS

Allows an attacker to insert code into the backend database used by that trusted website

# Document Object Model (DOM) XSS

Exploits the client's web browser using client-side scripts to modify the content and layout of the web page

# Session Management

Enables web applications to uniquely identify a user across several different actions and requests

# Cookie

Text file used to store information about a user when they visit a website

# Non-Persistent Cookie

Known as a session cookie, which resides in memory and is used for a very short period of time

# Persistent Cookie

Stored in the browser cache until they are deleted by a user or until they expire

# Session Hijacking

Type of spoofing attack where the attacker disconnects a host and then replaces it with his or her own machine by spoofing the original host IP

# Session Prediction

Type of spoofing attack where the attacker attempts to predict the session token in order to hijack the session

# Cross-Site Request Forgery (XSRF)

Malicious script is used to exploit a session started on another site within the same web browser

- To prevemt user-specific tokens in all form submissions
- Add randomnessa nd prompt for additional information
- Require users to enter their current password when changing their password



---
summary: Set 'Log Error' to 'Yes' for 'AllExceptions' in OutSystems 11 (O11) to improve error logging.
locale: en-us
guid: daf2fc35-917d-446f-b1a8-3f821f59dda8
app_type: traditional web apps, mobile apps, reactive web apps
platform-version: o11
figma:
tags: error handling, exception logging, best practices, debugging, application monitoring
audience:
  - full stack developers
  - frontend developers
  - mobile developers
  - architects
outsystems-tools:
  - service studio
coverage-type:
  - unblock
---

# Audit Suggestion Warning

Message
:   `'Log Error' should be set to 'Yes' for 'AllExceptions" error handler at screen flow level`

Cause
:   You have an Error Handler, in a screen flow, to catch general exceptions and the Log Error property is set to No.

Recommendation
:   You should change the Log Error property to Yes because, since the Error Handler is catching all exceptions. It is advisable that detailed information about that exception is logged by OutSystems. This might allow you to discover the reason for the exception.

---
title: Dev
weight: 22
pre: "<b>*. </b>"
chapter: true
---

### Dev for Forms

# Basics

Discover what this Hugo theme is all about and the core-concepts behind it.


{{< form name="contact" action="https://api.zupyak.com/users/session">}}
  {{< form-input id="firstname" type="text" placeholder="John" label="First Name:" required="true" >}}
  {{< form-input id="lastname" type="text" placeholder="Doe" label="Last Name:" >}}
  {{< form-input id="reply_email" type="email" placeholder="john.doe@email.com" label="Reply-To Email:" required="true" >}}
  {{< mult-input label="Gender:" name="gender" required="true" type="select" >}}
    {{< form-option label="Male" value="male" >}}
    {{< form-option label="Female" value="female" >}}
  {{< /mult-input >}}
  {{< form-input id="contact_description" type="textarea" label="Explain:" required="true" >}}
{{< /form >}}

<div id="retval"></div>
+++
title = "New form"
weight = 1
+++

In **Hugo**, pages are the core of your site. Once it is configured, pages are definitely the added value to your documentation site.

## Folders

Organize your site like [any other Hugo project](https://gohugo.io/content/organization/). Typically, you will have a *content* folder with all your pages.


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
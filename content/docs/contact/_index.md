---
weight: 1
title: "Contact"
bookComments: False
bookToC: False
stylesheet: "css/contact_form.css"
---

# Contact
Feel free to contact me at [demonstrandomblog@gmail.com](mailto:demonstrandomblog@gmail.com) or on [Twitter](https://twitter.com/DemonstRandom). You can also [subscribe]({{< relref "/docs/subscribe" >}}) to receive monthly updates. You can also use the form below.

{{< rawhtml >}}
<form class="wj-contact" action="https://formspree.io/mdogarke" method="POST">
  <div class "form-row">
    <input type="text" name="name" placeholder="Name">
  </div>
  <div class "form-row">
    <input type="text" name="email" placeholder="Email Address">
  </div>
  <div class "form-row">
    <input type="text" name="org" placeholder="Website/Organization">
  </div>
  <div class "form-row">
    <textarea type="text" name="content" rows="10" placeholder="Message"></textarea>
  </div>
    <input type="hidden" name="_next" value="<REDIRECTION LINK> ">
    <input type="hidden" name="_subject" value="New Contact Form Submission">
    <input type="text" name="_gotcha" style="display:none">
    <input type="submit" value="Submit">
</form>
{{< /rawhtml >}}

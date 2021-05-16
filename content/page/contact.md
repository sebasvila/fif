---
title: "Contact me"
date: 2021-05-16T16:33:39+02:00
categories:
- category
- subcategory
comments:       false
showMeta:       false
showActions:    false
#thumbnailImage: //example.com/image.jpg
---

I don't have comments on this site as they're difficult to manage and
take up too much time. I'd rather concentrate on producing content
than managing comments.

Instead of leaving a comment, feel free to contact me instead. I will
be happy to hear from you!

<form name="contact" style="margin-top:2em" action="/thank-you/" method="POST" data-netlify="true">
    <input type="hidden" name="form-name" value="contact" />
    <div style="margin: 1em">
        <label class="post" for="Name">Your name</label>
            <input style="width:85%" id="contact-form-name" name="Name" type="text" placeholder="Name" required="" autocomplete="off">
    </div>
    <div style="margin: 1em">
        <label class="post" for="Email">Your email</label>
            <input style="width:85%" id="contact-form-email" name="Email" type="email" placeholder="Email Address" required="" autocomplete="off">
    </div>
    <div style="margin: 1em">
        <label class="post" for="Subject">What's about?</label>
            <input style="width:85%" id="contact-form-subject" name="Subject" type="text" placeholder="Subject" required="" autocomplete="off">
    </div>
    <div style="margin: 1em">
        <label class="post" for="">Tell me</label>
        <textarea style="width:85%; padding: 1ex; border-width: 1px;
    border-radius: 6px; resize: none" id="contact-form-message" name="Message" placeholder="What's up?" rows="8"></textarea>
    </div>
    <div style="margin: 1em">
        <button type="submit" class="" value="Submit" id="Form-submit">Submit</button>
    </div>
</form>

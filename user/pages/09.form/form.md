---
title: Contact
routable: true
cache_enable: true
visible: true
form:
    fields:
        name:
            type: text
            label: Name
            validate:
                required: true
                message: 'Please enter your name!'
        email:
            type: text
            label: Email
            validate:
                type: email
                required: true
                message: 'Please enter your email address!'
        subject:
            type: text
            label: Subject
            validate:
                required: true
                message: 'Please enter a subject for your message!'
        message:
            type: textarea
            label: Message
            validate:
                required: true
                min: 10
                message: 'Email message needs to be more than 10 characters long!'
    buttons:
        submit:
            type: submit
            value: 'Send Email'
    process:
        message: 'Thank you from contacting us!'
        display: /form/thankyou
---

# Contact Form

  * Required field

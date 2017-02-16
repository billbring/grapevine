---
title: Contact
form:
    name: Contact Form
    fields:
        -
            name: name
            label: Name
            placeholder: 'Enter your name'
            autofocus: 'on'
            autocomplete: 'on'
            type: text
            validate:
                required: true
        -
            name: email
            label: Email
            placeholder: 'Enter your email address'
            type: email
            validate:
                required: true
        -
            name: message
            label: Message
            placeholder: 'Enter your message'
            type: textarea
            validate:
                required: true
    buttons:
        -
            type: submit
            value: Send

    process:
        -
            save:
                fileprefix: 'contact - '
                dateformat: Y.m.d-H.i.s-u
                extension: txt
                body: '{% include ''forms/data.txt.twig'' %}'
        -
            message: 'Thank you for getting in touch!'
        -
            display: /form/thankyou
---

# Contact

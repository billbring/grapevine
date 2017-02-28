---
title: Contact
form:
    name: 'Contact Form'
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
            name: organisation
            label: 'Organisation Name'
            placeholder: 'Enter your organisation''s name'
            type: text
            validate:
                required: false
        -
            name: telephone
            label: Telephone
            placeholder: 'Enter your telephone number'
            type: text
            validate:
                required: false
        -
            name: email
            label: Email
            placeholder: 'Enter your email address'
            type: email
            validate:
                required: true
        -
            name: message
            label: Enquiry
            placeholder: 'Enter your enquiry'
            type: textarea
            validate:
                required: true
    buttons:
        -
            type: submit
            classes: 'button-small button'
            value: Send
    process:
        -
            email:
                subject: 'Grapevine Online Contact Form - {{ form.value.name|e }}'
                body: '{% include ''forms/data.html.twig'' %}'
                reply_to: '{{ form.value.email }}'
        -
            save:
                fileprefix: 'contact - '
                dateformat: Y.m.d-H.i.s-u
                extension: txt
                body: '{% include ''forms/data.txt.twig'' %}'
        -
            message: 'Thank you for getting in touch!'
        -
            display: /contact/thankyou
---


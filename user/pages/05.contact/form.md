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
        - email:
            subject: "Grapevine Online Contact Form - {{ form.value.name|e }}"
            body: "{% include 'forms/data.html.twig' %}"
            reply_to: "{{ form.value.email }}"
        - save:
            fileprefix: 'contact - '
            dateformat: Y.m.d-H.i.s-u
            extension: txt
            body: '{% include ''forms/data.txt.twig'' %}'
        - message: 'Thank you for getting in touch!'
        - display: /contact/thankyou
---

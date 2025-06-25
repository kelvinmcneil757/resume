# Resume

This repository contains the static files for Kelvin McNeil Jr.'s resume website.

## Contact Form

The contact form in `index.html` submits data via [FormSubmit](https://formsubmit.co/).
It is configured to send submissions to **kmcneil757@gmail.com** using the following
form tag:

```html
<form action="https://formsubmit.co/d277f87322bdf22fdbdfefc1f943e934" method="POST">
```

Each input element includes a `name` attribute so the submitted values are passed
along. On first use, FormSubmit will send a confirmation email to
`kmcneil757@gmail.com`. Follow the link in that message to activate future submissions.

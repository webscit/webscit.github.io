# WebScIT website

The website is built using [Hugo](https://gohugo.io/) with the theme [TailBliss](https://github.com/nusserstudios/tailbliss) licensed under Apache 2.0.

## Developing

### Install

`npm install`

### Watch mode

`npm run start`

> *npm run start* will run two commands parallel:  
> `npx tailwindcss -i ./assets/css/main.css -o ./assets/css/style.css --watch`

Has paginated Categories and Tags. Markdown files will automatically convert images put into `/assets` folder to .webp images. 

### Generate the site

`npm run build`

## Image shortcodes for webp as well.

{{< imgc src="img-name.jpg" alt="Place alt text here." >}}

## Form

To use the form, visit [FormSubmit.Co](https://formsubmit.co/). Locate the contact form in "content/contact.md", and update the form action with the email address you want on this line: *action="https://formsubmit.co/your@email.com" method="POST"*

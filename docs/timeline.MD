## Workflow for short-term implementation
Our goal is to make a **standardized** documentation template and route for all the web applications developed and maintain by WADS team. This template should be:
  - Easy to implement
  - Easy to read
  - Easy to maintain

## Customization
Thanks to the open-source nature of docsify, there are multiple ways to make it our own upon implementation!
1. We locally modify the stylesheets and remove CDN dependencies
2. We use [docsify-themeable](https://jhildenbiddle.github.io/docsify-themeable/#/), an open-source styling editor for docsify.

PROS OF APPROACH 2:
- Easy customization through CSS variables and pre-made styles
- Is Docsify's go-to recommended add-on for this task
- Allows for custom styling on top of existing themes

CONS OF APPROACH 2:
- Relies on a bunch of CDNs, which while well maintained (jsDelivr), could become a point of failure in the long term.
  
### Within a Year (NOW - July 1st 2024)
  - Build the docsify-powered template
  - Collect all existing documentation and begin migration to new template
  - Use route convention (app_url.com/docs should lead to documentation page)
  - Utilize Github's access management and in-browser editing(press . on Github repo page opens up Github's in-browser editor) to streamline hosting, editing and maintaining of the /docs route.
  
### Long-term implementation
#### Inline editing
  - Having a rich text editor to format text into bullets and other elements
##### Example
  - [Trix](https://trix-editor.org/)
    A rich text editor that provide support for embedded attachments, and outputs terse and consistent HTML

#### Removing the burden of formatting from the user's shoulders
  - Developing components that allow users to click and place pre-made stylings for documentation elements
##### Example
  - [Medium](medium.com/me/about)


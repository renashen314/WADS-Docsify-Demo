## Our Goal
**We want to identify and codify patterns for how we document our web applications and provide that documentation for our users.**
- Adopt a consistent url pattern that is easy to communicate and reliably guides our users to the documentation for a given application.
- Develop a template for the documentation that is standards compliant, easy to use, and easy to maintain.
- Create a communication plan for communicating the new documentation patterns to LSATS support staff and our end users.

## Workflow for short-term implementation
- We intend to polish and deploy a template and leverage Docsify's and Github's features to ensure easy editability and maintainability of the app documentation.

## Customization
Thanks to the open-source nature of docsify, there are multiple ways to make it our own upon implementation!
1. We locally modify the stylesheets and remove CDN dependencies
2. We use [docsify-themeable](https://jhildenbiddle.github.io/docsify-themeable/#/), an open-source styling editor for docsify.

### Potential Pros of using themeable:
- Easy customization through CSS variables and pre-made styles
- Is Docsify's go-to recommended add-on for this task
- Allows for custom styling on top of existing themes

### Potential Cons of using themeable:
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


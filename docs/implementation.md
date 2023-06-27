### URL convention
  - Having a /docs and /docs/edit path to view and edit the docs as needed
  - Having a /docs/[ROLE] and /docs/[ROLE]/edit to maintain user-level and stakeholder specific documentation

### Implementation with Rails
  - create a /docs route in route.rb
  get "docs"
  - copy and modify index.html file from the Docsify starter pack into .erb format

### Implementation with .NET
#### [docsify-this.net](https://docsify-this.net/#/) 
A hosted Web app that uses Docsify to display remote Markdown files as standalone web pages (which are also perfect for embedding into other systems, such as an LMS). All you need is a publicly accessible Markdown file and provide that URL. @hibbittsdesign.

#### [docsify-dotnet-core](https://github.com/bharatdwarkani/docsify-dotnet-core) 
This project demonstrates how we can add docisfy in a ASP.NET Core 3.0 application and serve documentation site.

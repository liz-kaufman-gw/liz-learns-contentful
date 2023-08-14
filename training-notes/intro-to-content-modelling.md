# Intro to Content Modelling

Content = data (what info is being displayed)
Context = interface where you display content (how it's displayed/consumed)

"Structured content is content that is planned, developed, and connected outside an interface so that it's ready for any interface. It allows you to define the skeleton of your content before you create it. Breaking content into the smallest pieces possible (within reason) so that it is free to go anywhere, anytime."
~ Mike Atherton and Carrie Hane, *Designing Connected Content*

Well structured content models have discrete content types that are made of small "chunks" of data that can be reused (with clear relationships). This makes content reusable, faster and cheaper to use, and more adaptable.

## Vocabulary

- Content model - overall architecture of content (collection of content types)
- Content type - structure or container for piece of content (made of fields)
- Field (aka attribute) - property or characteristic for piece of content (can be any data type, including a reference to another content type)
- Entry - piece of content based on content type (instance of that content type)
- Reference - link between two content types via a field (creates a relationship between content types - can be one-to-one or one-to-many)
- Asset - media file uploaded to Contentful (content types can have fields for media which let authors link to assets)

Analogy: OOP - content types are classes, and entries are objects made from those classes

You can create a diagram of a content model using [ContentModel.io](https://contentmodel.io/).

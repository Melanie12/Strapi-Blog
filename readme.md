# Strapi-Blog

## Requirements
### Single type
[ ] Footer
[ ] Navigation
[X] BlogPage


### Collection types
[X] Articles
[X] Categories
[X] Pages 

## Ressources

## Log
25/08/2021
creation of this project
find inspiration in the foodadvisor demo
Between my admin and the foodadvisor admin there are differences:
- I don't always have the "enable localization" field in my components
- When picking a component, I have to choose an icon, but not in the foodadvisor admin.

27/08/2021
Create of Page (collection types) and Blogpage (single types).
_Question for JS:_ 
_- In Gitpod, for foodadvisor, I don't manage to see the front of the demo._
_- In the component header, I don't understand why the foodadvisor admin has "primary", "secondary", "muted" values_
_-Why the slug is an UID in Articles but a text for pages?_

**Note**
The enumeration component creates a dropdown field

**Note for later**
Relation
The Relation field allows to establish a relation with another content-type, that must be a collection type.

There are 6 different types of relations:

 One way: Content-type A has one Content-type B
 One-to-one: Content-type A has and belong to one Content-type B
 One-to-many: Content-type A belongs to many Content-type B
 Many-to-one: Content-type B has many Content-type A
 Many-to-many: Content-type A has and belongs to many Content-type B
 Many way: Content-type A has many Content-type B

 Logging off 21:38, to check for next time:
 - do I need a blocks cta in blogPage?
 - Do I add a block relatedArticles in Articles?
 - Do I need a blog hero in page?

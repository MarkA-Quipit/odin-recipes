# Odin Recipes

A small multi-page recipe site built with plain HTML for The Odin Project's Foundations course.

**Live site:** [Github Live](https://marka-quipit.github.io/odin-recipes/)
**Assignment:** [Recipes](https://www.theodinproject.com/lessons/foundations-recipes)

## What's in it

- An index page with an unordered list of links to each recipe
- Three recipe pages, all using the same layout:
  - Recipe name as the `h1`
  - Image of the finished dish
  - Description section
  - Ingredients as an unordered list
  - Steps as an ordered list
- A "Home" link on each recipe page that goes back to the index

Recipes:
- Chicken Adobo
- One-Pot Teriyaki Chicken Casserole
- Sausage, Peppers, Onions, and Potato Bake

## Project structure

```
odin-recipes/
├── index.html
└── recipes/
    ├── chicken-adobo.html
    ├── one-pot-teriyaki-chicken-casserole.html
    └── sausage-peppers-onions-and-potato-bake.html
```

## What I practiced

- HTML boilerplate and document structure
- Headings, paragraphs, images
- Unordered and ordered lists
- Relative links between pages (`recipes/...` and `../index.html`)
- Keeping a consistent layout across multiple pages
- Committing one iteration at a time with descriptive messages

## Scope

HTML only. No CSS or JavaScript on purpose, per the assignment.

## What was hard

I did not find anything hard in this project as I have previous experience.

## My thoughts on this project

I've spent a while going through tutorials for JavaScript, Node.js, Laravel, React and others. Even though I've built mid to big projects, impostor syndrome had me questioning whether I actually learned anything from them. After months without a project and not being able to decide on one, I decided to go back to the fundamentals.

Tutorials often felt like I was just following along. I believe "all grandiose buildings fall if the foundations are lacking," so I'm strengthening mine. I know AI matters today and can speed up a lot, but the person behind it still has to decide what's right and know enough to back that choice. Critical thinking comes first.

I picked The Odin Project to learn properly, shore up my fundamentals, and build projects of my own without leaning on others or on AI.

## Progress notes

| Iteration | Done |
|---|---|
| 1. Initial structure | Boilerplate and `h1` |
| 2. Recipe page | `recipes/` directory, first recipe file, links to and from index |
| 3. Recipe page content | Image, description, ingredients, steps |
| 4. More recipes | Two more recipes, same layout, links in a `ul` on index |

## Notes

The HTML and commits are my own work. The README structure was drafted with the help of Claude from my commit messages, and the "My thoughts" section is my own writing with claude acting as grammar cleaner. I also plan to update the readme file of main to my current progress/project, if you would like to see my progress, you can check the branches to see my previous iterations.
# Recipes

In this project we will collect our most bloved recipes.

## How to add a new recipe

1. Navigate to the root directory of your website folder within a terminal
2. Type `hugo new --kind recipe-bundle recipes/name-of-your-new-recipe-here`, replacing `name-of-your-new-recipe-here` with the name of your recipe

- Note that the default template (archetype in Hugo vernacular) will replace the hypens in the provided name with spaces as the title and capitalize the first letter of each word. For example, if I were to enter the command `hugo new --kind recipe-bundle recipes/hot-dog`, I would find a new folder at `content/recipes/hot-dog`, and the title within the `index.md` file in that folder would be `Hot Dog`.
- Don't forget to set `draft` to `false` in order to publish your recipe

## Further information

- <https://gohugo.io/documentation/>
- <https://github.com/seanlane/gochowdown>

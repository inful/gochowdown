---
layout: recipe
date: {{ .Date }}
draft: true    
title:  "{{ replace .Name "-" " " | humanize | title }}" # The title of your awesome recipe
image: awesome-recipe-image.jpg # Name of image in recipe bundle
imagecredit: https://placekitten.com/600/800 # URL to image source page, website, or creator
YouTubeID:  # The F2SYDXV1W1w part of https://www.youtube.com/watch?v=F2SYDXV1W1w
authorName: # Name of the recipe/article author
authorURL: # URL of their home website
sourceName: # Name of the source website
sourceURL: # Actual URL of the recipe itself
category: # The type of meal or course your recipe is about. For example: "dinner", "entree", or "dessert".
cuisine: # The region associated with your recipe. For example, "French", Mediterranean", or "American".
tags: # You don't have to have 3, feel free to have 10, 1, or none
  - tag1
  - tag2
  - tag3 
yield: 8
prepTime: 15
cookTime: 45

ingredients:
- ingredient: box of something
  value: 16 
  type: oz 

directions:
- Preheat oven to 350˚F/180˚C.
- In a large pot or dutch oven, cook macaroni according to package directions, salting the water with 2 teaspoons of salt. Drain and return to the warm pot.
- Add butter to warm macaroni and mix until melted. Season with the remaining salt and pepper.
- Add 1 cup of cheddar, mozzarella, provolone, Gouda, and feta cheese. Mix well.
- Add eggs and evaporated milk, mix until fully incorporated.
- Transfer to a 9x13-inch baking dish and top with the remaining cheddar cheese.
- Bake in a preheated oven for 40–45 minutes, until the top has nicely browned.
---

---
toc: true
toc_label: "Table of Contents"
toc_icon: "book"
permalink: /
---
Hi, I'm Jesse. Welcome to my portfolio website. Here, you'll find all my favorite projects I've developed over the years in reverse chronological order. Each project was developed independently. 

## [fog](https://github.com/Y-o-p/fog): Volume Ray Casting
_Oct 2023 to Jan 2024_

**fog** is a Volume Ray Casting framework built with C++ and OpenGL. This was done for my honors capstone, a final project for my honors diploma at UAH. I compared results between CPU and GPU implementations and put them on a poster for UAH's Research Horizons Day.

[Click Here](/poster/) to see my Research Horizons Day poster. 
{: .notice--success}

{% include figure image_path="imgs/PerlinCube.gif" alt="Perlin Noise Cube" caption="A " %}

## [RSNBB](https://github.com/Y-o-p/recipes-should-not-be-blogs): Recipe Scraper
_Jun 2023_

**recipes-should-not-be-blogs** (RSNBB) is a tool built with Rust that simplifies recipes. When supplied with a URL to a recipe, it will convert all the HTML to plain text using [ToolsYEP](https://toolsyep.com/en/webpage-to-plain-text/), parse the plain text with the [ChatGPT API](https://openai.com/product), gather nutritional information using the [NutritionIX API](https://www.nutritionix.com/business/api), and format it all into a markdown document. Below is an example of its use.

### Input

[AllRecipes Banana Bread](https://www.allrecipes.com/recipe/20144/banana-banana-bread/)

### Output

| INGREDIENT | CALORIES | PROTEIN | CARBS | FAT |
| - | - | - | - | - |
| 2 cups all purpose flour | 910 | 25.83 | 190.78 | 2.45 |
| 1 teaspoon baking soda | 0 | 0 | 0 | 0 |
| 0.25 teaspoon salt | 0 | 0 | 0 | 0 |
| 0.75 cup brown sugar | 520.13 | 0.16 | 134.26 | 0 |
| 0.5 cup butter | 813.8 | 0.96 | 0.07 | 92.06 |
| 2 large eggs | 143 | 12.56 | 0.72 | 9.51 |
| 2.33 cups bananas | 388.82 | 4.76 | 99.78 | 1.44 |

| NUTRIENT | AMOUNT |
| - | - |
| CALORIES | 2775.75 |
| PROTEIN | 44.269997 |
| CARBS | 425.61 |
| FAT | 105.46 |

1. Preheat the oven to 350 degrees F (175 degrees C). Lightly grease a 9x5-inch loaf pan.
2. Combine flour, baking soda, and salt in a large bowl.
3. Beat brown sugar and butter with an electric mixer in a separate large bowl until smooth. Stir in eggs and mashed bananas until well blended.
4. Stir banana mixture into flour mixture until just combined.
5. Pour batter into the prepared loaf pan.
6. Bake in the preheated oven until a toothpick inserted into the center comes out clean, about 60 minutes.
7. Let bread cool in pan for 10 minutes, then turn out onto a wire rack to cool completely.

## [hottify](https://github.com/Y-o-p/hottify): Global Spotify Hotkeys
_Jun 2022_

**hottify** is an application built with Python that runs in the background to provide global hotkeys for Spotify. No matter what application you're in, you're able to pause, play, skip, etc from a keyboard that doesn't have media keys. This was my first project outside of my work to use an API.

## [ArchaicGE](https://github.com/Y-o-p/ArchaicGE): 3D Console Graphics
_May 2018 (Revisited May 2020)_

**ArchaicGE** is a raster graphics framework built with C# that displays 3D objects in the console where different characters correspond to different light values. At this point, I had some experience with OpenGL but I wanted to learn more about the raster graphics pipeline. I took it upon myself to learn basic linear algebra, Bresenham's line algorithm, rasterization, z-buffering, and C# all in one project.

{% include figure image_path="imgs/Suzanne.png" alt="Suzanne" caption="The Blender monkey, Suzanne, rendered by ArchaicGE." %}

{% include figure image_path="imgs/dragon.png" alt="Dragon" caption="A dragon rendered by ArchaicGE." %}

{% include video id="m0qT37L4gcY" provider="youtube" %}

## [The Rest](https://github.com/Y-o-p)

More can be found on my GitHub.
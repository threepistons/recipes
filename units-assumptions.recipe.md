# Units and assumptions

## Assumptions

### Equipment

You have the following equipment:

- a refrigerator
- a stove
- an oven, gas or electric
- a set of sharp knives and a chopping board
- table knives, forks, and dessert spoons that you are happy to cook with
- wooden or equivalent large spoons, the type used for stirring pots
- scales that measure in grams
- measuring jugs graded in millilitres
- a set of those little scoops that measure volume in fractions of teaspoons and tablespoons
- kitchen scissors
- colander
- kitchen paper
- can opener
- steel skewer to test that things are cooked properly

Anything not on that list will be listed in the equipment section of the recipe.

## Units

- I write using metric masses (g) and volumes (ml) for the most part.
- Very small volumes will be given as *spoons*:
  - tsp: 5ml teaspoon
  - tbsp: 15ml tablespoon
- Oven settings are given in both [British gas marks](https://en.wikipedia.org/wiki/Gas_Mark) and &deg;C temperatures in newer recipes; [older ones only have the gas marks and will be updated](https://github.com/threepistons/recipes/issues/2) when I next cook them. The temperature is read from a thermometer hanging from a shelf in my gas oven, YMMV especially if you have a fan-assisted oven.

## Pseudo-units

#### count
`count` represents countable items. Countable items need a placeholder pseudo-unit to satisfy Kookbook's parser.

#### juiced_fruit

`juiced_fruit` represents the volume of juice obtained by the ad hoc juicing of one typical specimen of a fruit. For example, `1/2 juiced_fruit lemon juice` would often be stated as "juice of half a lemon" in a non-Kookbook recipe. I decided not to use `1/2 count lemon, juiced` because the ingredients list should reflect that I want the juice, not the lemon itself, which allows the possibility that juices can come in a bottle. Conversion of `juiced_fruit` into an appropriate volume of bottled juice is discussed at [Tips and gotchas > Lemon and lime juices](tips-gotchas.recipe.md#lemon-and-lime-juices).

# Final Changes

* Restructured CSS of individual projects to apply to custom web component
  * Prior to custom components each "card" had its own CSS rules, so I instead consolidated the rules to target one class making the style sheet cleaner and shorter
* Added dynamic addition of skill tags to individual projects upon fetching from JSON
  * Outside the HW scope, I wanted skills to reflect from my projects so I made that dynamically add from the fetched JSON in comparison to hardcoding.
* Made bug fixes of CSS rules not utilzing colored variables
  * To standardize css styling across the sheets, I made sure that most colors were variable which also makes switching themes easier.
* Reformatted colors that utilized hsl and rgba from previous homeworks to be solid hex color
  * Because the previous homeworks required different color representations, I default the colors back to hex to make theme switching and variables easier to utilize.
* Adjusted responsiveness of cards to reflect screen changes better
  * Made cards bigger to look less skinny and made responsiveness transition better to make scaling less erratic.

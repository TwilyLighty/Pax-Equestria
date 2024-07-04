# Content Localization

## Vision

- Events
    - Make sure most of the events are about the **charaters**.
    - A **dialogue** is a perfect way to introduce a friendship problem.

## Formatting

- Character lines with pre-scripted colors:
  - `". . . #twilight "I used to wonder what Friendship could be!"#! . . ."`
  - See [../../../gui/twilight_textformatting.gui](../../../gui/twilight_textformatting.gui) for the list of pre-scripted formats.
- Character lines with in-line colors:
  - `". . . #line #color:{0.76,0.77,0.83} "I just don't know what went wrong!"#!#! . . ."`
  - The color is in the RGB format
  - Check other online sources to decide a suitable color for each character

## Notable JEs

### The Grand Tomorrow (`je_grand_tomorrow`)

- Represents: Politics, Constitution
- Implementations:
    - Laws: Distribution of Power, Free Speech
- Branch Journal Entries:
    - [`je_grand_tomorrow_magic`](#je_grand_tomorrow_magic)
    - [`je_grand_tomorrow_honesty`](#je_grand_tomorrow_honesty)
    - [`je_grand_tomorrow_kindness`](#je_grand_tomorrow_kindness)
    - [`je_grand_tomorrow_laughter`](#je_grand_tomorrow_laughter)
    - [`je_grand_tomorrow_loyalty`](#je_grand_tomorrow_loyalty)
    - [`je_grand_tomorrow_generosity`](#je_grand_tomorrow_generosity)

#### Magic - The Spark of Knowledge (`je_grand_tomorrow_magic`)

- Represents: Government, Bureaucracy, Technology

#### Honesty - Honest Work (`je_grand_tomorrow_honesty`)

- Represents: Population, Taxation, Rural Development

#### Kindness - A Fair and Gentle Hoof (`je_grand_tomorrow_kindness`)

- Represents: Society, Equality, Welfare
- Implementations: Society Laws

#### Laughter - Better Together (`je_grand_tomorrow_laughter`)

- Represents: Diplomacy
- Implementations: Diplomatic Pacts, Relationships, Peacekeeping

#### Loyalty - Defending Our Friends (`je_grand_tomorrow_loyalty`)

- Represents: Military
- Implementations: Army Size, Military Laws\

#### Generosity - The Needs of our Ponies (`je_grand_tomorrow_generosity`)

- Represents: Economy, Industry, Urban Development
- Implementations: Building Levels

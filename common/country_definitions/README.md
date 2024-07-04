# common/country_definitions

# Tags

## Precondition

- Every tag should be based on its country's *default* name
    - "Equestrian Griffain" (X) -> "Griffain" (O)
- Country types should be ignore
    - "Crystal ~~Empire~~" -> "Crystal"
- Duplicate resolution:
  a) last letter instead of the first letter,
  b) priority is based on phonological order.
    - Assuming there are nations of "Alpha" and "Alpaca",
    - Alpaca is phonologically ahead of Alpha, therefore,
    - "ALPaca": `ALP`
    - "ALphA": `ALA`

## Criteria

- A tag of a country with one-word name should consist of
  the **first letter** and the **next two consonsants** of the name.
    - "EQueStria" -> `EQS`
    - "YaKYakistan" -> `YKY`
    - "GRiFfain" -> `GRF`
    - "Crystal ~~Empire~~" -> "CRYstal" -> `CRY`
- A tag of a country with two-word name should consist of
  a) the **first letter** and the **next consonant** of the **first word** and
  b) the **first letter** of the **last word**.
    - "SaDdle Arabia" -> `SDA`
- A tag of a country with a name of three or more words should consist of
  the **first letter** of **the first three word** each.
    - "Holy Roman Empire": `HRE`
    - "Alpha Beta Gamma delta": `ABG`
    <!-- No good example for now -->

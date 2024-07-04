# common/history/pops

## Important

- **Always set a religion for each pop group**
- `set_initial_tribal_qualifications`
    - When the game starts, some pops may be assigned tribe-restricted jobs they should not qualify for.
    - Use `set_initial_tribal_qualifications = yes` in the Population files to remove them.
    - Then manually create the right jobs in this file to ensure that the buildings can employ them.

## Syntax

```perl
# Minimal
create_pop = {
    culture = pony
    religion = magic_of_friendship
    size = 1000
}
```
```perl
# Pop type specified
create_pop = {
    culture = pony
    religion = magic_of_friendship
    pop_type = laborer
    size = 1000
}
```
```perl
# Culture split
create_pop = {
    cultures = {
        pony = 0.5
        griffon = 0.5
    }
    religion = magic_of_friendship
    size = 1000
}
```
```perl
# Religion split
create_pop = {
    culture = pony
    split_religion = {
        pony = {
            magic_of_friendship = 0.5
            materialism = 0.5
        }
    }
    size = 1000
}
```
```perl
# Culture and religion split combined
create_pop = {
    cultures = {
        pony = 0.5
        griffon = 0.5
    }
    split_religion = {
        pony = {
            magic_of_friendship = 0.5
            materialism = 0.5
        }
    }
    split_religion = {
        griffon = {
            magic_of_friendship = 0.5
            materialism = 0.5
        }
    }
    size = 1000
}
```
```perl
# Literacy
create_pop = {
    culture = pony
    religion = magic_of_friendship
    literacy_rate = 0.2
    size = 1000
}
```
```perl
# Note that the ratio is wa/total
# Overrides the value chosen according to pop type and country modifiers
create_pop = {
    culture = pony
    religion = magic_of_friendship
    working_adult_ratio = 0.1
    size = 1000
}
```

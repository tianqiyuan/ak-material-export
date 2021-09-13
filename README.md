# Arknights Material Export

A grimy Jupyter notebook for exporting operator farming plans to [Penguin-stats planner](https://penguin-stats.io/planner), with more planners to come.
The initial implementation is incomplete, and only supports elite promotions + skill mastery costs.

## Dependencies
`bidict`

## Usage

Populate `to_farm.txt` in the repo root with your operators' farming plan. Rules are as follows:
1. One operator per line
2. Each line is a comma-separated list starting with the operator's name (case-sensitive), followed by objectives to farm. Valid objectives include the following:
  - **elite promotions**,  with `e1` and `e2` being valid values
  - **skill mastery**, formatted in a convenient shorthand for skill X mastery Y
    - `s1m1`, `s1m2`, `s1m3`, .... `s3m3` are all valid values depending on the operator's rarity.

### Example
For a concrete example, let's say I want to farm Exusiai from E1 skill level 7 to E2, plus skill 3 mastery 3. Then, the input would look as follows:

`Exusiai,e2,s3m1,s3m2,s3m3`


## Credits

- Item data from [Kengxxiao/ArknightsGameData](https://github.com/Kengxxiao/ArknightsGameData)
- Operator data from [iansjk/arknights-tools](https://github.com/iansjk/arknights-tools)
- Hypergrpyh/Yostar for the game itself

Arknights is ©Hypergryph/Studio Montagne/Yostar. This project is unaffiliated with Arknights' creators/distributors.


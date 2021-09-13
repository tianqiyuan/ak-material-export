# Arknights Material Export

A grimy Jupyter notebook for exporting your operator farming plans to [Penguin-stats planner](https://penguin-stats.io/planner), with more planners to come.
The initial implementation is incomplete, and only supports elite promotions + skill mastery costs.

## Usage

Populate `to_farm.txt` in the repo root with your operators' farming plan. Rules are as follows:
1. One operator per line
2. Each line is a comma-separated list starting with the operator's name (case-sensitive), followed by objectives to farm.
    1. Valid objectives include the following:
      - **elite promotions**,  with `e1` and `e2` being valid values
      - **skill mastery**, formatted in a convenient shorthand for skill X mastery Y
        1. `s1m1`, `s1m2`,

## Credits

- Item data from [Kengxxiao/ArknightsGameData](https://github.com/Kengxxiao/ArknightsGameData)
- Operator data from [iansjk/arknights-tools](https://github.com/iansjk/arknights-tools)
- Hypergrpyh/Yostar for the game itself

Arknights is ©Hypergryph/Studio Montagne/Yostar. This project is unaffiliated with Arknights' creators/distributors.


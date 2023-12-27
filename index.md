# The index
I am an index

![Image of dwarf gourami](https://a-z-animals.com/media/2023/05/shutterstock-2300175123-huge-licensed-scaled.jpg)

## Fish Code
```python
from dataclasses import dataclass

@dataclass
class Fish:
    name: str
    tank: int

def find_fish(fishes, name, tank) -> Fish:
    for fish in fishes:
        if fish.name == name and fish.tank == tank:
            return fish

fishes = [Fish(name="Dwarf Gourami", tank=1), Fish(name="Dwarf Gourami", tank=2)]
print(find_fish(fishes, "Dwarf Gourami", 1))
```
## Fish Tasks
- [ ] Make a list of all my fish and tanks
- [ ] Add pictures of all fish

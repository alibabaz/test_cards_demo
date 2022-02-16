# Test Cards Demo
> How to play cards!


This file will become your README and also the index of your documentation.

## Install

`pip install test_cards_demo`

## How to use

Our main classes are for a single card and a deck of cards, let's see them in action below:

```python
from test_cards_demo.card import Card
from test_cards_demo.deck import Deck
d = Deck()
print(f'Number of playing cards in the deck: {len(d.cards)}')
```

    Number of playing cards in the deck: 52


```python
print(d.pop_card())
```

    King of Spades


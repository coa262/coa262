```javascript
// coa262.mjs

import { yellow } from 'chalk'

const welcoming = {
  name: "Hi there",
  emoji: "👋"
}

console.log(
  yellow(welcoming.name),
  welcoming.emoji
)

// npm install chalk
```

now from the language of pythons :snake:

```python
# coa262.py

from rich.console import Console
console = Console()

welcoming = {
  "name": "Hi there",
  "emoji": "👋"
}

console.print(
  f"{welcoming['name']} {welcoming['emoji']}",
  style="yellow"
)

# pip install rich
```

I thought it would be rich if I wrote this :shipit:

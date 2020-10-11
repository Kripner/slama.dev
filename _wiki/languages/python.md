---
---

{% match ### Data structures %}

{% match #### Heap %}
- requires `heapq`

| Action | Code                                |
| ---    | ---                                 |
| create | `heapify(queue)`, `queue` is a list |
| add    | `heappush(queue, element)`          |
| pop    | `heappop(queue, element)`           |

{% match ### Printing %}
- `print(stuff)`
	- `end=something` changes the end of line (default is `\n`)
	- `flush=True` flushes the print buffer to immediately input to terminal
# deno.py
```python
from Deno, promise_await import denopy

deno = Deno()

text = promise_await(deno.global.Deno.readTextFile('./text.txt')) # Call Deno API

router = deno.import('https://deno.land/x/hono@v3.6.0-rc.2/router/reg-exp-router/index.ts').RegExpRouter()
router.add('GET', '/', 0)
router.match('GET', '/')
```

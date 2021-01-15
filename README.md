#Reality

Get you platform:

```py
import Reality

print(Reality.platform())
```

See if a proccess is running:

```py
import Reality as r

if r.__running__("terminal"):
  print("Terminal is running!")
else:
  print("Terminal is not running.")
```

Get timestamp:

```py
import Reality as r

print(str(r.timestamp()))
```

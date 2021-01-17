#RealitySix

Get you platform:

```py
import RealitySix

print(RealitySix.platform())
```

See if a proccess is running:

```py
import RealitySix as r

if r.running("terminal"):
  print("Terminal is running!")
else:
  print("Terminal is not running.")
```

Get timestamp:

```py
import RealitySix as r

print(str(r.timestamp()))
```

[Documentation](https://reality-six-docs.herokuapp.com/Docs/index.html)

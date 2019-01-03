# Gap loader

Import hook for GAP files in SAGE math.
This package only works in SAGE math, not plain python.
To use it, simply import it and then import any gap file as if it where python.

```
import gap_loader
import some_gap_file

some_gap_file.some_function()
```

## Known problems

 - gap-loader finds the defined variables by seeing what variables are new after running the gap code. This means that variables that where already defined will not be found again. 

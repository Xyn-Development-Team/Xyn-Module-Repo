# Xyn Module Repository
The official Xyn module repo!

## Manual install
### Packaged module (Modules with their own folders)
  - Put their folder into `YourXynFolder/modules`
### Legacy module (Modules just containing a .py file)
  - Put the file into `YourXynFolder/modules`

Add an entry to your `settings.py` file, let's use the `fun` module as an example!
Keep in mind setting it's value to `False` disables the module.

```python
modules = {
    "sumothermodule":True,
    "fun":True
  }
```

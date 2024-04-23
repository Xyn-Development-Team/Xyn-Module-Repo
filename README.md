# (WIP) Xyn Module Repository
The official Xyn module repo!

## Install
- Run `python main.py --install modulename` on your Xyn folder.

*(Replace "modulename" with the name of your module's folder/.py file)*

## Manual install
### Packaged module (Modules with their own folders)
  - Put their folder into `YourXynFolder/modules`
### Legacy module (Modules just containing a .py file)
  - Put the file into `YourXynFolder/modules`

Then run `python main.py --generate-modulelist` to update the list of modules in your ``settings.py``

#

Alternatively you can manually add an entry to your `settings.py` file, let's use the `fun` module as an example!
Keep in mind setting it's value to `False` disables the module.

```python
modules = {
    "sumothermodule":False,  # no fun allowed
    "fun":True
  }
```

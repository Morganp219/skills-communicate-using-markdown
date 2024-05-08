# Hello World!
### From Northwest Tech!
![Image of nature](https://images.pexels.com/photos/3225517/pexels-photo-3225517.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1)
```python 
try:
    from Objects import *
    logging.debug("Gradebook Objects have loaded successfully")
except:
    logging.critical("Missing Objects.py, Shutting down application!")
    print("Missing Objects.py, Shutting down application!")
    sys.exit()
try:
    from Utilities import *
    logging.debug("Utilities have loaded successfully")
except:
    logging.critical("Missing Utilities.py, Shutting down application!")
    print("Missing Utilities.py, Shutting down application!")
    sys.exit()

```
- [ ] Turn on GitHub Pages
- [ ] Outline my portfolio
- [ ] Introduce myself to the world

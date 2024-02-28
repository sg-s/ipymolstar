# ipymolstar

![image](https://github.com/Jhsmit/ipymolstar/assets/7881506/589a94d5-2647-4977-90aa-c886c10cacb9)

Try it in jupyter lab on [JupyterLite](https://github.com/Jhsmit/ipymolstar-demo)

## Installation


```sh
pip install ipymolstar
```


## Use

```python
from ipymolstar import PDBeMolstar
view = PDBeMolstar(molecule_id='1qyn', theme='light', hide_water=True)
view
```

See the example notebook for more advanced usage. 

### Development


Windows:

```bash
set ANYWIDGET_HMR=1
jupyter lab
```

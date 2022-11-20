<h1> python xss prevent module - xsstop.py</h1>

This module filters requests coming from clients.



<h3>Recommendations</h3>

please use `python 3.x.x` 



<h3>Download</h3>

```
pip3 install xsstop
```



<h3>How to use</h3>

```python
import xsstop

variable = "anyscript"
prevent( variable )
```


<h3>why use?</h3>

Filters xss attacks from clients in web programs.
Also, even if you use a language other than python, you can pass the value to the xsstop.py module and use it.
```
php - shell_exec
node.js - Pythonshell.run
```
Use functions like above to pass values to python code where xsstop is imported


<h3>caution</h3>
1. If you use xsstop in a program that uses jinja, turn off jinja's autoescape.<br>
2. xsstop.py only provides primary filtering please configure CSP, httpsonly etc.<br>
3. The above contents are subject to change at any time through updates.

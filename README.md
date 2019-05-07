# My-jupytertheme

クラウド上などでも普段使っているようなJupyter Notebookのテーマで作業ができるようにするためのリポジトリ

## How To Use

セル上で以下のコードを実行するだけ．

```python
from IPython.display import display, HTML
css = !wget https://raw.githubusercontent.com/goat1010/My-jupytertheme/master/custom.css -q -O -
css = "\n".join(css)
display(HTML('<style type="text/css">%s</style>' % css))
```

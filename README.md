# Learning Plotly

## Imports

```python
import pandas as pd
import numpy as np
import plotly.graph_objects as go
import plotly.express as px
import chart_studio.plotly as py
import seaborn as sns
import cufflinks as cf
%matplotlib inline
from plotly.offline import download_plotlyjs, init_notebook_mode, plot, iplot
init_notebook_mode(connected=True)
cf.go_offline()
```

## Basics

```python
arr_1 = np.random.randn(50,4)
df_1 = pd.DataFrame(arr_1, columns=['A', 'B', 'C', 'D'])
df_1.head()
df_1.iplot()
```

![](static/newplot.png)

```python
df_stocks = px.data.stocks()
px.line(df_stocks, x='date', y='GOOG', labels={'x': 'Date', 'y': 'Price'})
```

![](static/line2.png)

## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```


## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```

## 

```python

```



## Credits

- [blog | about git - 1](https://www.cloudbees.com/blog/git-detached-head)
- [blog | about git - 2](https://www.varonis.com/blog/git-branching/)
- [youtube | tutorial](https://www.youtube.com/watch?v=GGL6U0k8WYA&ab_channel=DerekBanas)
- []()
- []()
- []()

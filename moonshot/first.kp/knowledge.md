---
title: Python in the Quantum World
authors:
- Rick Bahague
tags:
- Python
- Physics
- Scientific Computing
created_at: 2016-09-22 00:00:00
updated_at: 2018-05-29 16:26:58.993525
tldr: Jupyter-Notebook for the Python in Physics during the PythonPH Meetup
path: thoughtleadership/python-quantum-world
---
```python
import plotly.offline as pyo
import plotly.graph_objs as go
import pandas as pd
```
# let's plot


```python
pyo.init_notebook_mode(connected=True)
data = [go.Scatter(x=[1,2,3], y=[8,9,9], mode="marker")]
layout = go.Layout(title="test")
fig=go.Figure(data=data, layout=layout)
pyo.iplot(fig)
```


<script>requirejs.config({paths: { 'plotly': ['https://cdn.plot.ly/plotly-latest.min']},});if(!window.Plotly) {{require(['plotly'],function(plotly) {window.Plotly=plotly;});}}</script>




<div id="9e7d7645-5b40-468a-a0bc-8c78b3710872" style="height: 525px; width: 100%;" class="plotly-graph-div"></div><script type="text/javascript">require(["plotly"], function(Plotly) { window.PLOTLYENV=window.PLOTLYENV || {};window.PLOTLYENV.BASE_URL="https://plot.ly";Plotly.newPlot("9e7d7645-5b40-468a-a0bc-8c78b3710872", [{"type": "scatter", "x": [1, 2, 3], "y": [8, 9, 9], "mode": "marker"}], {"title": "test"}, {"showLink": true, "linkText": "Export to plot.ly"})});</script>

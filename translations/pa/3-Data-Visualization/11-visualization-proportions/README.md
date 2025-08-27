<!--
CO_OP_TRANSLATOR_METADATA:
{
  "original_hash": "af6a12015c6e250e500b570a9fa42593",
  "translation_date": "2025-08-27T18:43:46+00:00",
  "source_file": "3-Data-Visualization/11-visualization-proportions/README.md",
  "language_code": "pa"
}
-->
# ਅਨੁਪਾਤਾਂ ਦੀ ਦ੍ਰਿਸ਼ਟੀਕਰਨ

|![ [(@sketchthedocs)](https://sketchthedocs.dev) ਦੁਆਰਾ ਬਣਾਈ ਗਈ ਸਕੈਚਨੋਟ ](../../sketchnotes/11-Visualizing-Proportions.png)|
|:---:|
|ਅਨੁਪਾਤਾਂ ਦੀ ਦ੍ਰਿਸ਼ਟੀਕਰਨ - _[@nitya](https://twitter.com/nitya) ਦੁਆਰਾ ਬਣਾਈ ਗਈ ਸਕੈਚਨੋਟ_ |

ਇਸ ਪਾਠ ਵਿੱਚ, ਤੁਸੀਂ ਕੁਝ ਵੱਖਰੇ ਪ੍ਰਕ੍ਰਿਤੀ-ਕੇਂਦ੍ਰਿਤ ਡੇਟਾਸੈੱਟ ਦੀ ਵਰਤੋਂ ਕਰਕੇ ਅਨੁਪਾਤਾਂ ਨੂੰ ਦ੍ਰਿਸ਼ਟੀਕਰਤ ਕਰੋਗੇ, ਜਿਵੇਂ ਕਿ ਮਸ਼ਰੂਮਾਂ ਬਾਰੇ ਡੇਟਾਸੈੱਟ ਵਿੱਚ ਕਿੰਨੇ ਵੱਖ-ਵੱਖ ਕਿਸਮਾਂ ਦੇ ਫੰਗਸ ਹਨ। ਆਓ ਇਸ ਰੁਚਿਕਰ ਫੰਗਸ ਨੂੰ Audubon ਤੋਂ ਪ੍ਰਾਪਤ ਡੇਟਾਸੈੱਟ ਦੀ ਵਰਤੋਂ ਕਰਕੇ ਖੋਜੀਏ, ਜੋ Agaricus ਅਤੇ Lepiota ਪਰਿਵਾਰਾਂ ਦੇ 23 ਪ੍ਰਜਾਤੀਆਂ ਦੇ ਗਿਲਡ ਮਸ਼ਰੂਮਾਂ ਬਾਰੇ ਵੇਰਵੇ ਦਿੰਦਾ ਹੈ। ਤੁਸੀਂ ਹੇਠਾਂ ਦਿੱਤੇ ਦ੍ਰਿਸ਼ਟੀਕਰਨਾਂ ਨਾਲ ਪ੍ਰਯੋਗ ਕਰੋਗੇ:

- ਪਾਈ ਚਾਰਟ 🥧
- ਡੋਨਟ ਚਾਰਟ 🍩
- ਵਾਫਲ ਚਾਰਟ 🧇

> 💡 ਮਾਈਕਰੋਸਾਫਟ ਰਿਸਰਚ ਦੁਆਰਾ ਇੱਕ ਬਹੁਤ ਹੀ ਦਿਲਚਸਪ ਪ੍ਰੋਜੈਕਟ [Charticulator](https://charticulator.com) ਇੱਕ ਮੁਫ਼ਤ ਡ੍ਰੈਗ ਅਤੇ ਡ੍ਰਾਪ ਇੰਟਰਫੇਸ ਪੇਸ਼ ਕਰਦਾ ਹੈ ਜੋ ਡੇਟਾ ਦ੍ਰਿਸ਼ਟੀਕਰਨ ਲਈ ਹੈ। ਆਪਣੇ ਟਿਊਟੋਰਿਅਲਾਂ ਵਿੱਚ, ਉਹ ਇਸ ਮਸ਼ਰੂਮ ਡੇਟਾਸੈੱਟ ਦੀ ਵੀ ਵਰਤੋਂ ਕਰਦੇ ਹਨ! ਇਸ ਲਈ ਤੁਸੀਂ ਡੇਟਾ ਦੀ ਖੋਜ ਕਰ ਸਕਦੇ ਹੋ ਅਤੇ ਲਾਇਬ੍ਰੇਰੀ ਨੂੰ ਇੱਕੋ ਸਮੇਂ ਸਿੱਖ ਸਕਦੇ ਹੋ: [Charticulator ਟਿਊਟੋਰਿਅਲ](https://charticulator.com/tutorials/tutorial4.html)।

## [ਪ੍ਰੀ-ਪਾਠ ਕਵਿਜ਼](https://purple-hill-04aebfb03.1.azurestaticapps.net/quiz/20)

## ਆਪਣੇ ਮਸ਼ਰੂਮਾਂ ਨੂੰ ਜਾਣੋ 🍄

ਮਸ਼ਰੂਮ ਬਹੁਤ ਦਿਲਚਸਪ ਹੁੰਦੇ ਹਨ। ਆਓ ਇੱਕ ਡੇਟਾਸੈੱਟ ਨੂੰ ਆਯਾਤ ਕਰਕੇ ਉਨ੍ਹਾਂ ਦਾ ਅਧਿਐਨ ਕਰੀਏ:

```python
import pandas as pd
import matplotlib.pyplot as plt
mushrooms = pd.read_csv('../../data/mushrooms.csv')
mushrooms.head()
```
ਇੱਕ ਟੇਬਲ ਪ੍ਰਿੰਟ ਕੀਤੀ ਜਾਂਦੀ ਹੈ ਜਿਸ ਵਿੱਚ ਵਿਸ਼ਲੇਸ਼ਣ ਲਈ ਕੁਝ ਸ਼ਾਨਦਾਰ ਡੇਟਾ ਹੁੰਦਾ ਹੈ:

| class     | cap-shape | cap-surface | cap-color | bruises | odor    | gill-attachment | gill-spacing | gill-size | gill-color | stalk-shape | stalk-root | stalk-surface-above-ring | stalk-surface-below-ring | stalk-color-above-ring | stalk-color-below-ring | veil-type | veil-color | ring-number | ring-type | spore-print-color | population | habitat |
| --------- | --------- | ----------- | --------- | ------- | ------- | --------------- | ------------ | --------- | ---------- | ----------- | ---------- | ------------------------ | ------------------------ | ---------------------- | ---------------------- | --------- | ---------- | ----------- | --------- | ----------------- | ---------- | ------- |
| Poisonous | Convex    | Smooth      | Brown     | Bruises | Pungent | Free            | Close        | Narrow    | Black      | Enlarging   | Equal      | Smooth                   | Smooth                   | White                  | White                  | Partial   | White      | One         | Pendant   | Black             | Scattered  | Urban   |
| Edible    | Convex    | Smooth      | Yellow    | Bruises | Almond  | Free            | Close        | Broad     | Black      | Enlarging   | Club       | Smooth                   | Smooth                   | White                  | White                  | Partial   | White      | One         | Pendant   | Brown             | Numerous   | Grasses |
| Edible    | Bell      | Smooth      | White     | Bruises | Anise   | Free            | Close        | Broad     | Brown      | Enlarging   | Club       | Smooth                   | Smooth                   | White                  | White                  | Partial   | White      | One         | Pendant   | Brown             | Numerous   | Meadows |
| Poisonous | Convex    | Scaly       | White     | Bruises | Pungent | Free            | Close        | Narrow    | Brown      | Enlarging   | Equal      | Smooth                   | Smooth                   | White                  | White                  | Partial   | White      | One         | Pendant   | Black             | Scattered  | Urban   |

ਤੁਰੰਤ ਹੀ, ਤੁਸੀਂ ਨੋਟ ਕਰਦੇ ਹੋ ਕਿ ਸਾਰਾ ਡੇਟਾ ਟੈਕਸਟ ਦੇ ਰੂਪ ਵਿੱਚ ਹੈ। ਤੁਸੀਂ ਇਸ ਡੇਟਾ ਨੂੰ ਚਾਰਟ ਵਿੱਚ ਵਰਤਣ ਯੋਗ ਬਣਾਉਣ ਲਈ ਇਸ ਨੂੰ ਰੂਪਾਂਤਰਿਤ ਕਰਨਾ ਪਵੇਗਾ। ਅਸਲ ਵਿੱਚ, ਜ਼ਿਆਦਾਤਰ ਡੇਟਾ ਇੱਕ ਆਬਜੈਕਟ ਦੇ ਰੂਪ ਵਿੱਚ ਦਰਸਾਇਆ ਗਿਆ ਹੈ:

```python
print(mushrooms.select_dtypes(["object"]).columns)
```

ਆਉਟਪੁੱਟ ਹੈ:

```output
Index(['class', 'cap-shape', 'cap-surface', 'cap-color', 'bruises', 'odor',
       'gill-attachment', 'gill-spacing', 'gill-size', 'gill-color',
       'stalk-shape', 'stalk-root', 'stalk-surface-above-ring',
       'stalk-surface-below-ring', 'stalk-color-above-ring',
       'stalk-color-below-ring', 'veil-type', 'veil-color', 'ring-number',
       'ring-type', 'spore-print-color', 'population', 'habitat'],
      dtype='object')
```
ਇਸ ਡੇਟਾ ਨੂੰ ਲਓ ਅਤੇ 'class' ਕਾਲਮ ਨੂੰ ਇੱਕ ਸ਼੍ਰੇਣੀ ਵਿੱਚ ਰੂਪਾਂਤਰਿਤ ਕਰੋ:

```python
cols = mushrooms.select_dtypes(["object"]).columns
mushrooms[cols] = mushrooms[cols].astype('category')
```

```python
edibleclass=mushrooms.groupby(['class']).count()
edibleclass
```

ਹੁਣ, ਜੇ ਤੁਸੀਂ ਮਸ਼ਰੂਮਾਂ ਦਾ ਡੇਟਾ ਪ੍ਰਿੰਟ ਕਰਦੇ ਹੋ, ਤਾਂ ਤੁਸੀਂ ਦੇਖ ਸਕਦੇ ਹੋ ਕਿ ਇਸ ਨੂੰ ਜਹਿਰੀਲੇ/ਖਾਣਯੋਗ ਸ਼੍ਰੇਣੀ ਦੇ ਅਨੁਸਾਰ ਸ਼੍ਰੇਣੀਆਂ ਵਿੱਚ ਸਮੂਹਬੱਧ ਕੀਤਾ ਗਿਆ ਹੈ:

|           | cap-shape | cap-surface | cap-color | bruises | odor | gill-attachment | gill-spacing | gill-size | gill-color | stalk-shape | ... | stalk-surface-below-ring | stalk-color-above-ring | stalk-color-below-ring | veil-type | veil-color | ring-number | ring-type | spore-print-color | population | habitat |
| --------- | --------- | ----------- | --------- | ------- | ---- | --------------- | ------------ | --------- | ---------- | ----------- | --- | ------------------------ | ---------------------- | ---------------------- | --------- | ---------- | ----------- | --------- | ----------------- | ---------- | ------- |
| class     |           |             |           |         |      |                 |              |           |            |             |     |                          |                        |                        |           |            |             |           |                   |            |         |
| Edible    | 4208      | 4208        | 4208      | 4208    | 4208 | 4208            | 4208         | 4208      | 4208       | 4208        | ... | 4208                     | 4208                   | 4208                   | 4208      | 4208       | 4208        | 4208      | 4208              | 4208       | 4208    |
| Poisonous | 3916      | 3916        | 3916      | 3916    | 3916 | 3916            | 3916         | 3916      | 3916       | 3916        | ... | 3916                     | 3916                   | 3916                   | 3916      | 3916       | 3916        | 3916      | 3916              | 3916       | 3916    |

ਜੇ ਤੁਸੀਂ ਇਸ ਟੇਬਲ ਵਿੱਚ ਪੇਸ਼ ਕੀਤੇ ਕ੍ਰਮ ਨੂੰ ਫਾਲੋ ਕਰਦੇ ਹੋ ਤਾਂ ਤੁਸੀਂ ਆਪਣੀ ਸ਼੍ਰੇਣੀ ਲੇਬਲ ਬਣਾਉਣ ਲਈ ਪਾਈ ਚਾਰਟ ਤਿਆਰ ਕਰ ਸਕਦੇ ਹੋ:

## ਪਾਈ!

```python
labels=['Edible','Poisonous']
plt.pie(edibleclass['population'],labels=labels,autopct='%.1f %%')
plt.title('Edible?')
plt.show()
```
ਵੋਇਲਾ, ਇੱਕ ਪਾਈ ਚਾਰਟ ਜੋ ਇਸ ਡੇਟਾ ਨੂੰ ਮਸ਼ਰੂਮਾਂ ਦੀਆਂ ਦੋ ਸ਼੍ਰੇਣੀਆਂ ਦੇ ਅਨੁਪਾਤਾਂ ਦੇ ਅਨੁਸਾਰ ਦਰਸਾਉਂਦਾ ਹੈ। ਲੇਬਲਾਂ ਦੇ ਕ੍ਰਮ ਨੂੰ ਸਹੀ ਪ੍ਰਾਪਤ ਕਰਨਾ ਬਹੁਤ ਮਹੱਤਵਪੂਰਨ ਹੈ, ਖਾਸ ਕਰਕੇ ਇੱਥੇ, ਇਸ ਲਈ ਯਕੀਨੀ ਬਣਾਓ ਕਿ ਲੇਬਲ ਐਰੇ ਬਣਾਉਣ ਦੇ ਕ੍ਰਮ ਦੀ ਪੁਸ਼ਟੀ ਕਰੋ!

![pie chart](../../../../translated_images/pie1-wb.e201f2fcc335413143ce37650fb7f5f0bb21358e7823a327ed8644dfb84be9db.pa.png)

## ਡੋਨਟ!

ਪਾਈ ਚਾਰਟ ਦਾ ਇੱਕ ਕੁਝ ਹੋਰ ਦ੍ਰਿਸ਼ਟੀਕਰਣ ਰੂਪ ਡੋਨਟ ਚਾਰਟ ਹੈ, ਜੋ ਪਾਈ ਚਾਰਟ ਹੈ ਜਿਸਦੇ ਵਿਚਕਾਰ ਇੱਕ ਛੇਦ ਹੁੰਦਾ ਹੈ। ਆਓ ਆਪਣੇ ਡੇਟਾ ਨੂੰ ਇਸ ਤਰੀਕੇ ਨਾਲ ਵੇਖੀਏ।

ਮਸ਼ਰੂਮਾਂ ਦੇ ਵੱਖ-ਵੱਖ ਆਵਾਸਾਂ ਨੂੰ ਵੇਖੋ:

```python
habitat=mushrooms.groupby(['habitat']).count()
habitat
```
ਇੱਥੇ, ਤੁਸੀਂ ਆਪਣੇ ਡੇਟਾ ਨੂੰ ਆਵਾਸ ਦੇ ਅਨੁਸਾਰ ਸਮੂਹਬੱਧ ਕਰ ਰਹੇ ਹੋ। ਇੱਥੇ 7 ਆਵਾਸ ਦਿੱਤੇ ਗਏ ਹਨ, ਇਸ ਲਈ ਆਪਣੇ ਡੋਨਟ ਚਾਰਟ ਲਈ ਉਨ੍ਹਾਂ ਨੂੰ ਲੇਬਲਾਂ ਵਜੋਂ ਵਰਤੋ:

```python
labels=['Grasses','Leaves','Meadows','Paths','Urban','Waste','Wood']

plt.pie(habitat['class'], labels=labels,
        autopct='%1.1f%%', pctdistance=0.85)
  
center_circle = plt.Circle((0, 0), 0.40, fc='white')
fig = plt.gcf()

fig.gca().add_artist(center_circle)
  
plt.title('Mushroom Habitats')
  
plt.show()
```

![donut chart](../../../../translated_images/donut-wb.be3c12a22712302b5d10c40014d5389d4a1ae4412fe1655b3cf4af57b64f799a.pa.png)

ਇਹ ਕੋਡ ਇੱਕ ਚਾਰਟ ਅਤੇ ਇੱਕ ਕੇਂਦਰੀ ਸਰਕਲ ਖਿੱਚਦਾ ਹੈ, ਫਿਰ ਉਸ ਕੇਂਦਰੀ ਸਰਕਲ ਨੂੰ ਚਾਰਟ ਵਿੱਚ ਸ਼ਾਮਲ ਕਰਦਾ ਹੈ। ਕੇਂਦਰੀ ਸਰਕਲ ਦੀ ਚੌੜਾਈ ਨੂੰ `0.40` ਨੂੰ ਕਿਸੇ ਹੋਰ ਮੁੱਲ ਵਿੱਚ ਬਦਲ ਕੇ ਸੰਪਾਦਿਤ ਕਰੋ।

ਡੋਨਟ ਚਾਰਟਾਂ ਨੂੰ ਕਈ ਤਰੀਕਿਆਂ ਨਾਲ ਸੰਪਾਦਿਤ ਕੀਤਾ ਜਾ ਸਕਦਾ ਹੈ ਤਾਂ ਜੋ ਲੇਬਲਾਂ ਨੂੰ ਵਧੀਆ ਪੜ੍ਹਨਯੋਗ ਬਣਾਇਆ ਜਾ ਸਕੇ। ਇਸ ਬਾਰੇ ਹੋਰ ਜਾਣਕਾਰੀ ਲਈ [ਡੌਕਸ](https://matplotlib.org/stable/gallery/pie_and_polar_charts/pie_and_donut_labels.html?highlight=donut) ਵਿੱਚ ਪੜ੍ਹੋ।

ਹੁਣ ਜਦੋਂ ਤੁਸੀਂ ਆਪਣੇ ਡੇਟਾ ਨੂੰ ਸਮੂਹਬੱਧ ਕਰਨਾ ਅਤੇ ਇਸਨੂੰ ਪਾਈ ਜਾਂ ਡੋਨਟ ਵਜੋਂ ਦਰਸਾਉਣਾ ਸਿੱਖ ਲਿਆ ਹੈ, ਤਾਂ ਤੁਸੀਂ ਹੋਰ ਕਿਸਮਾਂ ਦੇ ਚਾਰਟਾਂ ਦੀ ਖੋਜ ਕਰ ਸਕਦੇ ਹੋ। ਇੱਕ ਵਾਫਲ ਚਾਰਟ ਦੀ ਕੋਸ਼ਿਸ਼ ਕਰੋ, ਜੋ ਮਾਤਰਾ ਦੀ ਖੋਜ ਕਰਨ ਦਾ ਇੱਕ ਵੱਖਰਾ ਤਰੀਕਾ ਹੈ।

## ਵਾਫਲ!

'ਵਾਫਲ' ਕਿਸਮ ਦਾ ਚਾਰਟ ਮਾਤਰਾ ਨੂੰ 2D ਐਰੇ ਦੇ ਵਰਗਾਂ ਵਜੋਂ ਦ੍ਰਿਸ਼ਟੀਕਰਤ ਕਰਨ ਦਾ ਇੱਕ ਵੱਖਰਾ ਤਰੀਕਾ ਹੈ। ਇਸ ਡੇਟਾਸੈੱਟ ਵਿੱਚ ਮਸ਼ਰੂਮ ਕੈਪ ਦੇ ਰੰਗਾਂ ਦੀਆਂ ਵੱਖ-ਵੱਖ ਮਾਤਰਾਵਾਂ ਨੂੰ ਦ੍ਰਿਸ਼ਟੀਕਰਤ ਕਰਨ ਦੀ ਕੋਸ਼ਿਸ਼ ਕਰੋ। ਇਸ ਲਈ, ਤੁਹਾਨੂੰ [PyWaffle](https://pypi.org/project/pywaffle/) ਨਾਮਕ ਇੱਕ ਸਹਾਇਕ ਲਾਇਬ੍ਰੇਰੀ ਨੂੰ ਇੰਸਟਾਲ ਕਰਨ ਦੀ ਜ਼ਰੂਰਤ ਹੈ ਅਤੇ Matplotlib ਦੀ ਵਰਤੋਂ ਕਰਨੀ ਪਵੇਗੀ:

```python
pip install pywaffle
```

ਆਪਣੇ ਡੇਟਾ ਦੇ ਇੱਕ ਖੰਡ ਨੂੰ ਸਮੂਹਬੱਧ ਕਰਨ ਲਈ ਚੁਣੋ:

```python
capcolor=mushrooms.groupby(['cap-color']).count()
capcolor
```

ਲੇਬਲ ਬਣਾਕੇ ਅਤੇ ਫਿਰ ਆਪਣੇ ਡੇਟਾ ਨੂੰ ਸਮੂਹਬੱਧ ਕਰਕੇ ਇੱਕ ਵਾਫਲ ਚਾਰਟ ਬਣਾਓ:

```python
import pandas as pd
import matplotlib.pyplot as plt
from pywaffle import Waffle
  
data ={'color': ['brown', 'buff', 'cinnamon', 'green', 'pink', 'purple', 'red', 'white', 'yellow'],
    'amount': capcolor['class']
     }
  
df = pd.DataFrame(data)
  
fig = plt.figure(
    FigureClass = Waffle,
    rows = 100,
    values = df.amount,
    labels = list(df.color),
    figsize = (30,30),
    colors=["brown", "tan", "maroon", "green", "pink", "purple", "red", "whitesmoke", "yellow"],
)
```

ਵਾਫਲ ਚਾਰਟ ਦੀ ਵਰਤੋਂ ਕਰਕੇ, ਤੁਸੀਂ ਇਸ ਮਸ਼ਰੂਮ ਡੇਟਾਸੈੱਟ ਦੇ ਕੈਪ ਰੰਗਾਂ ਦੇ ਅਨੁਪਾਤਾਂ ਨੂੰ ਸਪਸ਼ਟ ਤੌਰ 'ਤੇ ਵੇਖ ਸਕਦੇ ਹੋ। ਦਿਲਚਸਪ ਗੱਲ ਇਹ ਹੈ ਕਿ ਬਹੁਤ ਸਾਰੇ ਹਰੇ ਕੈਪ ਵਾਲੇ ਮਸ਼ਰੂਮ ਹਨ!

![waffle chart](../../../../translated_images/waffle.5455dbae4ccf17d53bb40ff0a657ecef7b8aa967e27a19cc96325bd81598f65e.pa.png)

✅ Pywaffle ਚਾਰਟਾਂ ਵਿੱਚ ਆਈਕਨ ਦਾ ਸਮਰਥਨ ਕਰਦਾ ਹੈ ਜੋ [Font Awesome](https://fontawesome.com/) ਵਿੱਚ ਉਪਲਬਧ ਕਿਸੇ ਵੀ ਆਈਕਨ ਦੀ ਵਰਤੋਂ ਕਰਦਾ ਹੈ। ਵਰਗਾਂ ਦੀ ਬਜਾਏ ਆਈਕਨ ਦੀ ਵਰਤੋਂ ਕਰਕੇ ਇੱਕ ਹੋਰ ਦਿਲਚਸਪ ਵਾਫਲ ਚਾਰਟ ਬਣਾਉਣ ਲਈ ਕੁਝ ਪ੍ਰਯੋਗ ਕਰੋ।

ਇਸ ਪਾਠ ਵਿੱਚ, ਤੁਸੀਂ ਅਨੁਪਾਤਾਂ ਨੂੰ ਦ੍ਰਿਸ਼ਟੀਕਰਤ ਕਰਨ ਦੇ ਤਿੰਨ ਤਰੀਕੇ ਸਿੱਖੇ। ਪਹਿਲਾਂ, ਤੁਹਾਨੂੰ ਆਪਣੇ ਡੇਟਾ ਨੂੰ ਸ਼੍ਰੇਣੀਆਂ ਵਿੱਚ ਸਮੂਹਬੱਧ ਕਰਨ ਦੀ ਜ਼ਰੂਰਤ ਹੈ ਅਤੇ ਫਿਰ ਇਹ ਫੈਸਲਾ ਕਰਨ ਦੀ ਜ਼ਰੂਰਤ ਹੈ ਕਿ ਡੇਟਾ ਨੂੰ ਦਰਸਾਉਣ ਦਾ ਸਭ ਤੋਂ ਵਧੀਆ ਤਰੀਕਾ ਕਿਹੜਾ ਹੈ - ਪਾਈ, ਡੋਨਟ, ਜਾਂ ਵਾਫਲ। ਸਾਰੇ ਸੁਆਦਿਸ਼ਟ ਹਨ ਅਤੇ ਉਪਭੋਗਤਾ ਨੂੰ ਡੇਟਾਸੈੱਟ ਦਾ ਤੁਰੰਤ ਸਨੈਪਸ਼ਾਟ ਪ੍ਰਦਾਨ ਕਰਦੇ ਹਨ।

## 🚀 ਚੁਣੌਤੀ

ਇਹ ਸੁਆਦਿਸ਼ਟ ਚਾਰਟਾਂ ਨੂੰ [Charticulator](https://charticulator.com) ਵਿੱਚ ਦੁਬਾਰਾ ਬਣਾਉਣ ਦੀ ਕੋਸ਼ਿਸ਼ ਕਰੋ।
## [ਪੋਸਟ-ਪਾਠ ਕਵਿਜ਼](https://purple-hill-04aebfb03.1.azurestaticapps.net/quiz/21)

## ਸਮੀਖਿਆ ਅਤੇ ਸਵੈ ਅਧਿਐਨ

ਕਈ ਵਾਰ ਇਹ ਸਪਸ਼ਟ ਨਹੀਂ ਹੁੰਦਾ ਕਿ ਪਾਈ, ਡੋਨਟ, ਜਾਂ ਵਾਫਲ ਚਾਰਟ ਕਦੋਂ ਵਰਤਣਾ ਹੈ। ਇਸ ਵਿਸ਼ੇ 'ਤੇ ਪੜ੍ਹਨ ਲਈ ਕੁਝ ਲੇਖ ਇੱਥੇ ਹਨ:

https://www.beautiful.ai/blog/battle-of-the-charts-pie-chart-vs-donut-chart

https://medium.com/@hypsypops/pie-chart-vs-donut-chart-showdown-in-the-ring-5d24fd86a9ce

https://www.mit.edu/~mbarker/formula1/f1help/11-ch-c6.htm

https://medium.datadriveninvestor.com/data-visualization-done-the-right-way-with-tableau-waffle-chart-fdf2a19be402

ਹੋਰ ਜਾਣਕਾਰੀ ਪ੍ਰਾਪਤ ਕਰਨ ਲਈ ਕੁਝ ਖੋਜ ਕਰੋ ਅਤੇ ਇਸ ਫੈਸਲੇ 'ਤੇ ਹੋਰ ਪੜ੍ਹਾਈ ਕਰੋ।

## ਅਸਾਈਨਮੈਂਟ

[Excel ਵਿੱਚ ਇਸਨੂੰ ਅਜ਼ਮਾਓ](assignment.md)

---

**ਅਸਵੀਕਤੀ**:  
ਇਹ ਦਸਤਾਵੇਜ਼ AI ਅਨੁਵਾਦ ਸੇਵਾ [Co-op Translator](https://github.com/Azure/co-op-translator) ਦੀ ਵਰਤੋਂ ਕਰਕੇ ਅਨੁਵਾਦ ਕੀਤਾ ਗਿਆ ਹੈ। ਜਦੋਂ ਕਿ ਅਸੀਂ ਸਹੀ ਹੋਣ ਦੀ ਕੋਸ਼ਿਸ਼ ਕਰਦੇ ਹਾਂ, ਕਿਰਪਾ ਕਰਕੇ ਧਿਆਨ ਦਿਓ ਕਿ ਸਵੈਚਾਲਿਤ ਅਨੁਵਾਦਾਂ ਵਿੱਚ ਗਲਤੀਆਂ ਜਾਂ ਅਸੁਚੱਜੇਪਣ ਹੋ ਸਕਦੇ ਹਨ। ਮੂਲ ਦਸਤਾਵੇਜ਼ ਨੂੰ ਇਸਦੀ ਮੂਲ ਭਾਸ਼ਾ ਵਿੱਚ ਅਧਿਕਾਰਤ ਸਰੋਤ ਮੰਨਿਆ ਜਾਣਾ ਚਾਹੀਦਾ ਹੈ। ਮਹੱਤਵਪੂਰਨ ਜਾਣਕਾਰੀ ਲਈ, ਪੇਸ਼ੇਵਰ ਮਨੁੱਖੀ ਅਨੁਵਾਦ ਦੀ ਸਿਫਾਰਸ਼ ਕੀਤੀ ਜਾਂਦੀ ਹੈ। ਇਸ ਅਨੁਵਾਦ ਦੀ ਵਰਤੋਂ ਤੋਂ ਪੈਦਾ ਹੋਣ ਵਾਲੇ ਕਿਸੇ ਵੀ ਗਲਤਫਹਿਮੀ ਜਾਂ ਗਲਤ ਵਿਆਖਿਆ ਲਈ ਅਸੀਂ ਜ਼ਿੰਮੇਵਾਰ ਨਹੀਂ ਹਾਂ।
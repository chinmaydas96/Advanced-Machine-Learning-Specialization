### Frequency Encoding


```Python
encoding = titanic.groupby('embarked').size()
encoding = freq_encoding / len(titanic)
titanic['enc'] = titanic['embarked'].map(encoding)
```

# Standardisation

* Min-Max - Keep the same distribution

* Standard - Normal distribution


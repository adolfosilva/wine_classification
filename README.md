# Wine Prediction Challenge

- The goal is to predict if a given wine is White or Red wine.
- The goal is to predict the quality of the wine.

Dataset: http://www3.dsi.uminho.pt/pcortez/wine/

## Results:

### Wine type challenge:

Using an ExtraTreesClassifier:

- Weighted F1-score: 0.99676;
- Balanced Accuracy: 0.99484;
- Matthews Correlation Coefficient: 0.99129;

### Wine quality challenge:

Using a Stacked classifier (ExtraTrees + KNN +LR):

- Weighted F1-score: 0.9906;
- Balanced Accuracy: 0.98092;
- Matthews Correlation Coefficient: 0.98878;

## Running:

```
$ jupyter lab notebooks
```

## License

Distributed under the MIT license. See [LICENSE](./LICENSE) for details.

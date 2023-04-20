# parameter-optimisation-ucs654

**Dataset Used:** [Accelerometer readings](https://archive.ics.uci.edu/ml/datasets/Accelerometer)

**Conclusion:**  As the dataset is very large, the SVM model is not able to fit well and so the max accuracy is 0.380.

| Number of Instances:  | 153000 |
|-----------------------|--------|
| Number of Attributes: | 5      |

---

### Results:
 
 | Sample # | Best Accuracy | kernel | c   | gamma | degree |
|----------|--------------------------|---------|-----|-------|-----|
| 1        | 0.3309368191721133       | rbf    | 0.1 | 0.01  | 1 |
| 2        | 0.34809368191721135       | poly    | 3 | 1 | 2 | 
| 3        | 0.3340958605664488      | poly    | 0.1 | 0.01  | 2 |
| 4        | 0.33126361655773423       | rbf    | 3 | 1  | 1 |
| 5        | 0.3397058823529412       | poly    | 1 | 0.01  | 2 |
| 6        | 0.3449891067538126       | poly    | 1 | 0.01  | 2 |
| 7        | 0.3803376906318083       | poly    | 1 | 0.01  | 2 |
| 8        | 0.3332788671023965       | poly    | 3 | 1  | 2 |
| 9        | 0.33736383442265794     | rbf    | 3 | 0.1  | 1 |
| 10       | 0.33344226579520697 | rbf    | 3 | 0.1  | 1 |


### Convergence graph for the above result:

<img width="477" alt="image" src="https://user-images.githubusercontent.com/84312981/233470257-12f2bfac-16e7-4edf-8397-d9bd11b50b67.png">

### Nandini Mehta
### Roll No-102067009

# parameter-optimisation-ucs654

**Dataset Used:** [Accelerometer readings](https://archive.ics.uci.edu/ml/datasets/Accelerometer)

**Conclusion:**  As the dataset is very large, the SVM model is not able to fit well and so the max accuracy is 0.421. Thus the convergence graph is coming out to be a straight line.

| Number of Instances:  | 153000 |
|-----------------------|--------|
| Number of Attributes: | 5      |

---

### Results:
 
 | Sample # | Best Accuracy | kernel | c   | gamma | degree |
|----------|--------------------------|---------|-----|-------|-----|
| 1        | 0.32494553376906316       | poly    | 0.5 | 0.01  | 2 |
| 2        | 0.34776688453159044       | poly    | 1 | 0.01  | 2 | 
| 3        | 0.33137254901960783      | rbf    | 3 | 1  | 2 |
| 4        | 0.33137254901960783       | rbf    | 3 | 1  | 1 |
| 5        | 0.3329520697167756       | poly    | 0.1 | 0.001  | 2 |
| 6        | 0.3446078431372549       | poly    | 0.5 | 0.01  | 2 |
| 7        | 0.34733115468409587       | poly    | 0.5 | 0.01  | 2 |
| 8        | 0.3547385620915033       | poly    | 1 | 0.01  | 2 |
| 9        | 0.4216230936819172     | poly    | 1 | 0.01  | 2 |
| 10       | 0.33082788671023966 | poly    | 0.5 | 0.01  | 2 |


### Convergence graph for the above result:

<img width="542" alt="image" src="https://user-images.githubusercontent.com/84312981/233302545-84f4da90-f7bd-407a-b033-5068b9437934.png">



### Nandini Mehta
### Roll No-102067009

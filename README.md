# Parameter-Optimization-of-SVM
## Sampling Assignment

**Dataset Used:** [
Chess (King-Rook vs. King) Data Set](https://archive.ics.uci.edu/ml/datasets/Chess+%28King-Rook+vs.+King%29)

| Number of Instances:  | 28056 |
|-----------------------|-------|
| Number of Attributes: | 6     |

## Attribute Information:

1. White King file (column)<br>
2. White King rank (row)<br>
3. White Rook file<br>
4. White Rook rank<br>
5. Black King file<br>
6. Black King rank<br>
7. optimal depth-of-win for White in 0 to 16 moves, otherwise drawn {draw, zero, one, two, ..., sixteen}.<br>

## Tasks Performed
1. Download the dataset
2. Pre-process the dataset
3. Create ten samples 
4. Split the samples in  70 : 30 for training and testing
5. Optimise SVM using randomisation for every sample and report best accuracy and best parameters
6. For the best sample plot the convergence graph


## Results

The best parameters of SVC for the given dataset are:
- Kernel : rbf
- C : 8.437685 
- Gamma : 0.470508    

The above parameter gave a maximum accuracy of 96.44.

### Convergence graph  : 


![download](https://user-images.githubusercontent.com/71830227/233195149-685670b9-3ed7-46f6-b853-0421a11dbe7b.png)<br>



## Submission by :
**Name** : Harshit Sharma
<br>
**Roll No** : 102003653


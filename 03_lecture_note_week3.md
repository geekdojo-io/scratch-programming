### Review of the homework for Week 2(Compressing a string)
Nice job for solving the homework. This homework was a tough one. So, please don't be discouraged if you didn't finish on time.

##### Example

![Homework example](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11121906/scratch_week2_homework.png)

### Array:
An array is a ordered collection of data. For example, an array can be used for storing the scores of players for a video game.

Let's say you are writing a program that needs to show the following information of Pacman, a classic video game:
- Average score of players
- Best score
- Worst score

#### Average temperature
```
GetAverage(Scores)
  index = 1
  sum = 0
  Loop until index = length of Scores
    change sum by Array[index]
    change index by 1
  average = sum / length of Scores
  Say "Average is " + average
```

#### Best (Maximum) score
```
GetMaximum(Scores)
  index = 1
  result = Scores[index]
  Loop until index = length of Scores
    index = index + 1
    current_score = Scores[index]
    if result < current_score
      result = current_score
  Say "Best score is " + result

```

#### Worst (Minimum) score
```
GetMinimum(Scores)
  index = 1
  result = Scores[index]
  Loop until index = length of Scores
    index = index + 1
    current_score = Scores[index]
    if result > current_score
      result = current_score
  Say "Worse score is " + result

```

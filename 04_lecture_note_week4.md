### Review of the homework for Week 2 (Loop through items)
Nice job for solving the homework. This homework was an easy one.

##### Example

![Homework example](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11122533/scratch_week3_homework.png)

### Practice

#### Find a minimum from an array
Example:
```
arr = [7, 2, 1, 5, 3]
min = arr[1]
for pos = 1 to len(arr)
  if min > arr[pos]
    min = arr[pos]
say min
```
![Minimum](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11122607/scratch_min.png)

* * *
#### Find a maximum from an array
Example:
```
arr = [7, 2, 1, 5, 3]
max = arr[1]
for pos = 1 to len(arr)
  if max < arr[pos]
    max = arr[pos]
say max
```
![Maximum](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11122629/scratch_max.png)

* * *
#### Return an absolute number
Ask a number, and always return an absolute number.
```
if num < 0
  num = -1 * num
say num  
```
![Absolute](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11122702/scratch_abs.png)

* * *
#### Swap two numbers
Use a temporary variable!
```
a = 2
b = 3

t = a
a = b
b = t
```
![Absolute](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11122733/scratch_swap.png)
* * *
#### Reverse an array
Use swap!
```
arr = [7, 2, 1, 5, 1]
for pos = 1 to len(arr)/2
  swap arr[pos] with arr[len(arr) - pos + 1]
```
![Absolute](https://d37rfi63g2olb3.cloudfront.net/wp-content/uploads/2018/02/11122800/scratch_reverse_array.png)

# group_6_ass_2_2024
# 1.1 Tuple
## 1. To access the first element, I used "[1]" and to access element 0 of the first element, I used "[0]"
tuple1 = ("Orange", [10, 20, 30], (5, 15, 25))
print(tuple1[1][0])

10

## 2. To access the last item, I used [2] for selecting location
tuple1 = ("Orange", [10, 20, 30], (5, 15, 25))
print(tuple1[2])

(5, 15, 25)

## 3. We change the word "Orange" replacing it with "pink grapefruit". In this case, it is posisble to replace the elements of the tuple1, because we are just renaming the composition of the first item of the tuple1 and keeping the rest items.

tuple1 = ("Orange", [10, 20, 30], (5, 15, 25))
tuple1 = ("pink grapefruit", [10, 20, 30], (5, 15, 25))
print(tuple1)

('pink grapefruit', [10, 20, 30], (5, 15, 25))

## 4. We apply the "Len" function to calculate the number of items
len(tuple1)
3

## 5. We use "map" to apply the sum list function to each sublist in tuple2
tuple2 = ([7, 8], [9, 1], [10, 7])
X = sum(map(sum, tuple2))
print(X)

42

## 6. We use "map" to apply the sum list function to each sublist in tuple3 but first, we need to find the half values of tuple2 
tuple3 = ([3.5, 4], [4.5, 0.5], [5, 3.5])
y= sum(map(sum , tuple3))
print(y)

21

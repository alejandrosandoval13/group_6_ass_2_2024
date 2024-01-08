# group_6_ass_2_2024
## 1.1 Tuple
tuple1 = ("Orange", [10, 20, 30], (5, 15, 25))
print(tuple1[1][0])
10

tuple1 = ("Orange", [10, 20, 30], (5, 15, 25))
print(tuple1[2])
(5, 15, 25)

tuple1 = ("Orange", [10, 20, 30], (5, 15, 25))
tuple1 = ("pink grapefruit", [10, 20, 30], (5, 15, 25))
print(tuple1)
('pink grapefruit', [10, 20, 30], (5, 15, 25))

len(tuple1)
3

tuple2 = ([7, 8], [9, 1], [10, 7])
X = sum(map(sum, tuple2))
print(X)
42

tuple3 = ([3.5, 4], [4.5, 0.5], [5, 3.5])
y= sum(map(sum , tuple3))
print(y)
21.0

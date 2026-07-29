# Part1
snack_box1 = {'chips', 'juice', 'cookies', 'chips', 'apple'}
snack_box2 = {'juice', 'sandwich', 'cookies', 'sandwich'}
print("Snack Box1 : ", snack_box1)
print("Snack Box2 : ", snack_box2)


# Part2:Add
snack_box2.add("banana")
print("Snack Box2 After Adding banana: ",snack_box2)


# Part3:Common
common_snack = snack_box1.intersection(snack_box2)
print("Snacks in  both boxes: ",common_snack)


# Part4:Create an array
import array as arr
snack_counts = arr.array('i', [4,6,3,5])
print("Snack counts array: ",snack_counts)


# Part5
snack_counts.insert(0, 2)
snack_counts.append(7)
print("Snack counts after adding items: ",snack_counts)


# Part6
count_of_5 = snack_counts.count(5)
print("Number of times 5 appears: ", count_of_5)


# Part7:Reverse
snack_counts.reverse()
print("Reversed Snack counts array: ", snack_counts)


# Part8
print("==== SCHOOL SNACK COUNTER ====")
print("Snack Box1: ", snack_box1)
print("Snack Box2: ", snack_box2)
print("Shared Snacks: ", common_snack)
print("Snack Counts: ", snack_counts)
print("===================================")

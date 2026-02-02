# -EXERCISE-USING-LIST-AND-THEIR-BUILT-IN-FUNCTIONS
nums = [10, 20, 30, 40, 50]
print("Original:", nums)

nums.append(60)
nums.insert(1, 15)
nums.remove(30)
nums.pop()

print("Modified:", nums)

nums.sort()
print("Sorted:", nums)

nums.reverse()
print("Reversed:", nums)

print("Length:", len(nums))
print("Max:", max(nums))
print("Min:", min(nums))
print("Sum:", sum(nums))

new_list = nums.copy()
print("Copied List:", new_list)
nums.clear()
print("Cleared List:", nums)

output:
Original: [10, 20, 30, 40, 50]
Modified: [10, 15, 20, 40, 50]
Sorted: [10, 15, 20, 40, 50]
Reversed: [50, 40, 20, 15, 10]
Length: 5
Max: 50
Min: 10
Sum: 135
Copied List: [50, 40, 20, 15, 10]
Cleared List: []


4. EXERCISE BY IMPLEMENTING 

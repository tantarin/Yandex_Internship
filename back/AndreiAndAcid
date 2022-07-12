n = int(input())
nums = [int(n) for n in input().split()]
count = 0
for i in range (len(nums)-1):
    d = nums[i]
    next_d = nums[i+1]
    if next_d > d:
        diff = next_d - d
        count += diff
    elif next_d < d:
        count = -1
        break
print(count)

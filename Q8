def minimize_score(nums, k):
    nums.sort()
    n = len(nums)

    min_value = nums[0]
    max_value = nums[-1]

    for i in range(n - 1):
        min_value = min(min_value, nums[i + 1] - k)
        max_value = max(max_value, nums[i] + k)

    return max_value - min_value

# Test example
nums = [1]
k = 0
print(minimize_score(nums, k))  # Output: 0

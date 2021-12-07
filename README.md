# turing

def find_max(nums):
    max_num = float("-inf")

    for num in nums:
        if num > max_num:
            max_num = num
    return max_num

nums = (3,4,5,6,9,12)

print(find_max(nums))

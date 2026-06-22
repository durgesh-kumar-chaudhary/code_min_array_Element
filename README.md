# code_min_array_Element

def find_smallest(nums):# python code for min of array element
    small=nums[0]
    for i in range(1,len(nums)-1):
        if nums[i]<small:
            small=nums[i]
    return small
print(find_smallest([5,9,3,6,7,2,0,-1,8,-9]))

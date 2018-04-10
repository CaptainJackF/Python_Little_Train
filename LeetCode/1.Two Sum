# -- coding:utf-8 --
'''
	1. Two Sum
	Given an array of integers, return indices of the two numbers such that they add up to a specific target.
	You may assume that each input would have exactly one solution, and you may not use the same element twice.
'''

class Solution:
	def twoSum( self, nums, target):
		dic = {}	## 创建一个空字典, 用于储存 target - value, 以及 index.
		result = {}	## 用于储存可行的结果.
		i = 1
		for index, value in enumerate( nums):
			if value in dic:
				result[ str( "Plan" + str(i))] = [ dic[value], index]
				i += 1
			dic[ target - value] = index
		return( result)


if __name__ == "__main__":
    nums = [2, 7, 11, 15]
    target = 9
    print( Solution().twoSum(nums, target))
    nums = [3, 2, 4]
    target = 6
    print( Solution().twoSum(nums, target))
    nums = [1, 2, 3, 4, 5, 6]
    target = 5
    print( Solution().twoSum(nums, target))

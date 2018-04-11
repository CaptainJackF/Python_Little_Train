# -- coding:utf-8 --
'''
	11. Roman to Integer
	给定一个罗马数字，将其转换成整数。
	返回的结果要求在 1 到 3999 的范围内。
'''

Convert = { 'M': 1000, 'D': 500, 'C': 100, 'L': 50, 'X': 10, 'V': 5, 'I': 1}

X = "XLCIX"

class Solution:
    def romanToInt( self, s):
    	output = 0
    	for i in range( 0, len( s)):
    		if ( i == ( len( s) - 1) or Convert[ s[i]] >= Convert[ s[ i+1]]) :
    			output += Convert[ s[i]]
    		elif s[ i] not in ['I', 'X', 'C']:
    			output += Convert[ s[i]]
    		else:
    			output = output - Convert[ s[i]]
    	return( output)


if __name__ == "__main__":
    s = "XLCIX"
    print( Solution().romanToInt( s))

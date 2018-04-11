# -- coding:utf-8 --
'''
	7. Reverse Integer
	给定一个范围为 32 位 int 的整数，将其颠倒。
'''

class Solution:
	def reverse( self, x):
	    """
	    :type x: int
	    :rtype: int
	    """
	    if x < 0:
	    	x = x*-1
	    	return( int( "-" + str( x)[::-1]))
	    else:
	    	return( int( str( x)[::-1]))


if __name__ == "__main__":
    x = 123
    print( Solution().reverse( x))
    x = -123
    print( Solution().reverse( x))
    x = 1534236469
    print( Solution().reverse( x))

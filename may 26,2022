class Solution:
    def hammingWeight(self, n: int) -> int:

        """
        :type n: int
        :rtype: int
        """
        count = 0
        for i in range(32):
            count += (n >> i) & 1
        return count

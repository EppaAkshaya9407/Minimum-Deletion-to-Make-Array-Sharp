# Minimum-Deletion-to-Make-Array-Sharp
class Solution:
    def minDeletions(self, nums: list[int]) -> int:
        d=0
        n=len(nums)
        for i in range(n-1):
            if nums[i]==nums[i+1]:
                d+=1
        return d

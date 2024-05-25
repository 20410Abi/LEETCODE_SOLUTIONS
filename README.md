# LEETCODE_SOLUTIONS
HI, My name is Abinash Rath and I will be posting my Leetcode solutions .

#Two Sum

class Solution {
    public int[] twoSum(int[] nums, int target) {
        int n = nums.length;
        for (int i = 0; i < n - 1; i++) {
            for (int j = i + 1; j < n; j++) {
                if (nums[i] + nums[j] == target) {
                    return new int[]{i, j};
                }
            }
        }
        
        return new int[]{};
    }
}

git add file1.java file2.java

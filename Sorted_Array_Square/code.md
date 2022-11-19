```java
class Solution {
    public int[] sortedSquares(int[] nums) {
        for(int i=0; i<nums.length; i++)
        {
            nums[i]=nums[i]*nums[i];//calculating squares of each element
        }
        Arrays.sort(nums);//sorting the array
        return(nums);
    }
}
```

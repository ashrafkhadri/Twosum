class Solution{
public int[] two Sum(int[] nums,int target) {
for(int i=0;i<nums.length;i++)
{
 for (int j=i+1;j<nums.lenght;j++)
 {
 if(nums[i]+nums[j]==target)
 {
  arr[0]=i;
  arr[1]=j;
  break;
  }
  }
  }
  return arr;


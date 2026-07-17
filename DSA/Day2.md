#Move Zeroes to end.
class Solution {

    public void moveZeroes(int[] nums) {

        int j = 0;

        for (int i = 0; i < nums.length; i++) {

            if (nums[i] != 0) {

                int temp = nums[i];
                nums[i] = nums[j];
                nums[j] = temp;

                j++;
            }
        }
    }

    public static void main(String[] args) {

        int[] nums = {0, 1, 0, 3, 12};

        Solution obj = new Solution();

        obj.moveZeroes(nums);

        for (int num : nums) {
            System.out.print(num + " ");
        }
    }
}
#Check if Array is Sorted.
class Solution {
    public static boolean IsSorted(int arr[]) {
        for(int i = 0; i < arr.length - 1; i++) {
            if(arr[i] > arr[i + 1]) {
                return false;
            }
        }
        return true;
    }

    public static void main(String args[]) {
        int[] arr = {1, 2, 4, 4};
        System.out.println(IsSorted(arr));
    }
}


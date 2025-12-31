###学习二分查找
public class s3 {
    // 二分查找
    public int search(int[] a, int key){
        int low = 0;
        int high = a.length - 1;
        if(a[low]>key||a[high]<key){
            return -1;
        }
        while (low <= high ){
            int mid = (low + high) / 2;
            if(a[mid]==key);
            return mid;
            if(a[mid]<key){
                low = mid + 1;
            }else{
                high = mid - 1;
            }
            return -1;
        }
    }
    }


###学习移除数组元素
 //移除数值元素
    public static void remove(int [] num,int ver) {

        int fast=0;
        int slow=0;
        if(fast<=num.length-1){
            if(num[ fast]== ver){
                fast++;
            }else{
                num[slow]=num[fast];
                slow++;
                fast++;
            }
        }


    }

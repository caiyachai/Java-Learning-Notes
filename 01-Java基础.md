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

# style
软件工程
1.帮助开发人员编写代码，提升质量、减少bug。提升反馈速度，减少重复工作，提高开发效率。保证你最后的代码修改不会破坏之前代码的功能。


2.​


/*
 * 冒泡排序
 */
public class BubbleSort {
　　
 
   public void BubbleSort(int[] arr){
 
　　　　for(int i=0;i<arr.length-1;i++){//外层循环控制排序趟数
　　　　　　for(int j=0;j<arr.length-1-i;j++){//内层循环控制每一趟排序多少次
　　　　　　　　if(arr[j]>arr[j+1]){
　　　　　　　　　　int temp=arr[j];
　　　　　　　　　　arr[j]=arr[j+1];
　　　　　　　　　　arr[j+1]=temp;
　　　　　　　　}
　　　　　　}
　　
        //输出
 
        System.out.println("排序后数组元素为:");
        for(int num : arr){
 
           System.out.print( num + "  " );
 
           }
       }　　
 
 
}

        3.测试用例
                  语句覆盖 :  1.arr = {4,3,2,1}

                  判定覆盖 :  1.arr = {1,2,3,4};  2. arr = {4,3,2,1}

                  条件覆盖 :  1.arr = {1,2,3,4};  2. arr = {4,3,2,1}

                  路径覆盖 :  1.arr = {1,2,3,4};  2. arr = {4,3,2,1}

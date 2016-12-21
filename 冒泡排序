# Data
Java
冒泡排序

package Data;

import java.util.Random;

public class Bubble {
	public static void main(String[] args) {
		int[] arr = new int[20];
		Random r  = new Random();
		for (int i = 0; i < arr.length; i++) {
			 int j = r.nextInt(100);
			 arr[i] = j;
		}
		for (int i = 0; i < arr.length; i++) {
			for (int j = 0; j < arr.length-1-i; j++) {
				if(arr[j]<arr[j+1]){
					int temp = arr[j];
					arr[j] = arr[j+1];
					arr[j+1] = temp;
				}
			}
		}
		for (int i : arr) {
			System.out.print(i+" ");
		}
	}
}

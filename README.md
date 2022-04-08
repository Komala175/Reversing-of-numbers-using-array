# Reversing-of-numbers-using-array



  public class Reversing{
	public static void main(String[] args) {
		int[]  arr=new int[] {4,3,2,1};
		System.out.println("Enter the original number:");
		for(int  i=0;i<arr.length;i++) {
			System.out.println(arr[i]+"");
		}
		System.out.println();
		System.out.println("Reversed number");
		for(int i=arr.length-1;i>=0;i--) {
			System.out.println(arr[i]+"");
		}

	}


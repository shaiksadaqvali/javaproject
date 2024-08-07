class Test  
{
	public static void main(String[] args) 
	{
		int[] arr1 ={1,6,9,4,2};
		int[] arr2 ={8,2,7,3,6};
		
		int[] resArr=new int[arr1.length];
		
		for(int i=0;i<arr1.length && i<arr2.length;i++)
		{
			resArr[i]=arr1[i]+arr2[i];
		}
		
		//display the elements 
		for(int i:resArr)
		{
			System.out.print(i+" ");
		}

	}
}

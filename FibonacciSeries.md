package learning;

public class FibonacciSeries {
	// initialize 3 int variables (Tip: range = 8, firstNum = 0, secNum = 1, sum in the series)

			// Print first number
			
			// Iterate from 1 to the range
			
			// add first and second number assign to sum

			// Assign second number to the first number

			// Assign sum to the second number
			
			// print sum


	public static void main(String[] args) {
		int range=8,firstNum=0,secNum=1,sum;
		System.out.println(firstNum);
		System.out.println(secNum);
		for (int i=0;i<=range;i++) {   //i=3 ; 3<=8
			sum= firstNum+secNum;            //sum 2+3=5
			firstNum=secNum;                 //firstNum=3
			secNum=sum;                      // sec =5
			System.out.println(sum);    // 1 
		}
	  
		    
	
}
}

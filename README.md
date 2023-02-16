# calculate-power-of-n-numbers-using-recurision
output:-2^5=32,2^3=8




package recursion;

public class calculatePower {

	public static int power(int x,int y) {
		if(y==0) {
			return 1;
		}
		
			return (x*power(x,y-1));
		
	}
	public static void main(String[]args) {
		int x,y;
		
		System.out.print(power(2,5));
		
	}
			
}  
                  output:-
                  32

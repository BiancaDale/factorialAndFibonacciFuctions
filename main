import java.util.Random;

public class factorialAndFibonacciFuctions {

static int fibonacci(int N) {
	if(N == 0 || N == 1) {
		// Base case
		return 1;
		
	} else {
		return fibonacci(N-1) + fibonacci(N-2);
	}			
				
			}
static int factorial(int N) {
	if(N == 0 || N == 1) {
		return 1;
	} else {
		return N*factorial(N-1);
	}
}


// generates random numbers between 0 and 10 and passes the random number to the factorial and fibonacci methods
public static void main(String[] args) {
	//int min = 0;
	//int max = 9;
	//int N = (int) ((Math.random()*((max-min)+1))+min);
	Random random = new Random();
	int N = random.nextInt(10);	
	System.out.println("The factorial function applied to the value " + N + " is " + factorial(N));
	System.out.println("The fibonacci function applied to the value " + (N+1) + " is " + fibonacci(N));
}
}

GCD
===

Greatest Common Divisors
//
//GCD Function 

int GCD(int a, int b) //integer values a and b 
{
  while(1)
	{
		a=(a%b); // first a mod b, if a equals zero then b
		if(a==0)
			return b;

		b=(b%a); // second b mod a, if b equals zero then a
		if(b==0)
			return a; 
	}
	
}

# minimum3-



//This public method is used to invoke the static method UserInput()
	
	public class ExFinal {

	public static void main(String[] args) {

		Ex_Q1 A1=new Ex_Q1();
		A1.UserInput();
	}

	
}
////////////////////////////////////////////////


    public static void UserInput()
	{
		Scanner input=new Scanner(System.in);
		System.out.print("Please Enter Number1");
		float num1=input.nextFloat();
		
		System.out.print("Please Enter Number2");
		float num2=input.nextFloat();
		
		System.out.print("Please Enter Number3");
		float num3=input.nextFloat();
	
		minimum3(num1, num2, num3);
	
			}


	
	public static void minimum3(float num1, float num2, float num3)
	{
	
	
		float Minoftwo=Math.min(num1, num2);
		float finalresult= Math.min(Minoftwo, num3);
		
		
		System.out.print("Minimum value: " + finalresult);
		
	}

package assignments;

public class Questions {

	public static void main(String[] args) {
		// Question 1
		int a = 10;
		int b = 20;
		int t=0;
		System.out.println("Question 1");
		System.out.println("Befpre Swapping:");
		System.out.println("a is " + a  + ",b is " + b+ "\n");
		
		t=a;
		b=a;
		a=b;
		System.out.println("After Swapping:");
		System.out.println("a is " + a + ",b is " + b+ "\n");
		
		// Question 2
		a=a+b;
		b=a-b;
		a=a-b;
		System.out.println("Question 2");
		System.out.println("After Swapping:");
		System.out.println("a is " + a + ",b is " + b+ "\n");
		
		// Question 3
		a=10;
		b=20;
		int c=30;
		t=0;
		System.out.println("Before Swapping:");
		System.out.println("a is " + a  + ",b is " + b  + ",c is " +c+ "\n");
		
		t=a;
		a=b;
		b=c;
		c=t;
		System.out.println("Question 3");
		System.out.println("After Swapping:");
		System.out.println("a is " + a + ",b is " + b + ",c is " +c+ "\n");
		
		//Question 4
		a=10;
		b=20;
		c=30;
		System.out.println("Question 4");
		System.out.println("Before Swapping:");
		System.out.println("a is " + a + ",b is " + b  + ",c is " +c+ "\n");
		
		a=a+b+c;
		b=a-b;
		c=b-c;
		b=b-c;
		a=a-b-c;
		System.out.println("After Swapping:");
		System.out.println("a is " + a  + ",b is " + b + ",c is " +c+ "\n");
		
		//Question 5
		a=10;
		b=20;
		c=30;
		int d=40;
		t=0;
		System.out.println("Question 5");
		System.out.println("Before Swapping:");
		System.out.println("a is " + a  + ",b is " + b  + ",c is " +c+  ",d is " +d+ "\n");
		
		t=a;
		a=b;
		b=c;
		c=d;
		d=t;
		System.out.println("After Swapping:");
		System.out.println("a is " + a + ",b is " + b  + ",c is " +c+ ",d is " +d+ "\n");

		// Question 6
		a=10;
		b=20;
		c=30;
		d=40;
		System.out.println("Question 6");
		System.out.println("Before Swapping:");
		System.out.println("a is " + a +  ",b is " + b  + ",c is " +c+ ",d is " +d+ "\n");
	
		a=a+b;
		b=a-b;
		a=a-b;
		c=c+d;
		d=c-d;
		c=c-d;
		System.out.println("After Swapping:");
		System.out.println("a is " + a + ",b is " + b  +  ",c is " +c+ ",d is " +d+ "\n");

		//Question 7
		double PlanPrice=699;
		double Gst=0.18*PlanPrice;
		System.out.println("Question 7");
		System.out.println("Final Price after GST is " + (PlanPrice+Gst) + "\n");
		
		//Question 8
		
		double price=399.0;
		double dis=0.2;
		int n=2;
		double fin = price*n;
		System.out.println("Question 8");
		System.out.println("Final Price after discount is "+(fin-(fin*dis)) +"\n");
		
		//Question 9
		int salary = 85000;
		double tax= 0.2;
		System.out.println("Question 9");
		System.out.println("The tax to be paid is "+(salary*tax)+"\n");
		
		//Question 10
		int amount=500000;
		int time=5;
		double roi=6.8;
		double InterestAmount = (amount*time*roi)/100;
		System.out.println("Question 10");
		System.out.println("The interest amount to be paid is "+InterestAmount);
		System.out.println("Final amount to be paid off by Sarah is  "+(amount+InterestAmount)+"\n");
		
		//Question 11
		salary= 85000;
		double ta=0.15;
		double da=0.20;
		double hra=0.18;
		double pf=0.20;
		tax=0.25;		
		double taa=salary*ta;
		double daa=salary*da;
		double hraa=salary*hra;
		double pfa=salary*pf;
		double taxa=salary*tax;
		double ga=salary+taa+daa+hraa;
		System.out.println("Question 11");
		System.out.println("Gross Amount of Hina is "+ga+"\n");
		System.out.println("Net Amount of Hina is "+(ga-pfa-taxa)+"\n");
		
				
	}

}

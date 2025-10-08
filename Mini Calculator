# C-study
using System;
					
public class Program
{
	public static void Main()
	{
		Console.WriteLine("Haoqi's Mini Calcutator V2");
		num1:
		Console.WriteLine("Enter in First number: ");
		double n1;
		if(double.TryParse(Console.ReadLine(), out n1))
			Console.WriteLine("Your first number is "+ n1);
		else
		{
			Console.WriteLine("INVALID INPUT!");
		    goto num1;
		}
		
		num2:
		Console.WriteLine("Enter in Second number: ");
		double n2;
		if(double.TryParse(Console.ReadLine(), out n2))
			Console.WriteLine("Your first number is "+ n2);
		else
		{
			Console.WriteLine("INVALID INPUT!");
		    goto num2;
		}
		ope:
	   Console.WriteLine("Enter in Operation");
		char op;
		if(char.TryParse(Console.ReadLine(), out op))
		   {
			Console.WriteLine("Theoperation is: "+op);
		   }
		else
		{Console.WriteLine("INVALID INPUT!");
		 goto ope;
		}
		double result;
		
		switch(op){
				case '*':
				result = n1*n2;
				Console.WriteLine(n1+"*"+n2+"="+ result);
				break;
				
			    case '^':
				result = Math.Pow(n1,n2);
				Console.WriteLine(n1+"^"+n2+"="+result);
				break;
				
			    case '+':
				result=n1+n2;
				Console.WriteLine(n1+"+"+n2+"="+result);
				break;
				
			    case '-':
				result=n1-n2;
				Console.WriteLine(n1+"-"+n2+"="+result);
				break;
				
				case '/':
				result=n1/n2;
				Console.WriteLine(n1+"/"+n2+"="+result);
				break;
				
		        default:
				Console.WriteLine("please enter acceptable operation");
				goto ope;
								  
		}
		Console.WriteLine("Enter any to restart");
		Console.ReadLine();
		Console.Clear();
		Main();
	}
}

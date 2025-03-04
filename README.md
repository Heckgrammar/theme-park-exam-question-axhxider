public class Program
{
	public static void Main()
	{
		Console.WriteLine("how many poeple are in your group"); //asks for the  number of people visiting the theme park
		int people = Convert.ToInt32(Console.ReadLine());
		
		int finalCharge = people * 15;	//charge is £15pp therefore people*15 = cost of whole data set
		
		if (people >= 6 )
		
		{
			finalCharge= finalCharge - 5;		// if total is greater than £90 offer a £5 discount
		}
		
		
		Console.WriteLine(finalCharge);	//displays final charge
	}
}

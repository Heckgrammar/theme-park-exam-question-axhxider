public class Program
{
	public static void Main()
	{
		Console.WriteLine("how many poeple are in your group"); //asks the  number of people visiting
		int people = Convert.ToInt32(Console.ReadLine());
		
		int finalCharge = people * 15;	//charge is £15pp therefire people*15 = cost of whole data set
		
		if (people >= 6 )
		
		{
			finalCharge= finalCharge - 5;		// if total is greater than £90 offer a £5 discount
		}
		
		
		Console.WriteLine(finalCharge);	//displays final charge
	}
}

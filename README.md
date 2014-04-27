Random-Number---LAB--1-WEEK-10
==============================

LAB#1-  WEEK 10


// BY REINA OLARTE  CMS 112
//  LAB#1 WEEK 10 


public class RandomNumber 
{
	int computerNumber;
	int LowNumber;
	int HighNumber;
	public int RandomNumber(int low)
	{
		LowNumber = low;
		return LowNumber;
	}
	public int RandNumber(int high)
	{
		HighNumber = high;
		return HighNumber;
	}
	public int GetANumber()
	{
		computerNumber = (LowNumber + (int)(Math.random() * HighNumber));
		return computerNumber;
	}
	public int GetANumber(int low, int High)
	{
		computerNumber = (low + (int)(Math.random() *High));
		return computerNumber;
	}
	public int GetANumber(int High)
	{		
		computerNumber = 0 + (int)(Math.random() *High);
		return computerNumber;
	}
	public int setLowNumber(int low)
	{
		LowNumber = low;
		return LowNumber;
	}
	public int setHighNumber(int high)
	{
		HighNumber = high;
		return HighNumber;
	}
	
	}


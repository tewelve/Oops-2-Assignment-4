# Oops-2-Assignment-4

import java.util.Arrays;
import java.util.Collections;
import java.util.List;

public class Reverse
{
	public static void main(String args[])
	{
		String[]strDays=new String[]
				{"Sunday","Monday"};
		List<String>list=Arrays.asList(strDays);
		Collections.reverse(list);
		strDays=(String[]) list.toArray();
		System.out.println("String  reversed");
		for(int i=0;i<strDays.length;i++)
		{
			System.out.println(strDays[i]);
		}
	}

}

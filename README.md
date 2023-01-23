# codetest
public class Main // sum un while ile tapilmas;
{
	public static void main(String[] args) {
	int a=0;
	int sum=0;
	while(a<5)
	{
	    sum=sum+a;
	    a++;
	}
	System.out.println(sum); 
	}
}


public class Main // for ile sum un ile tapilmas;
{
	public static void main(String[] args) {
	int sum =0;
	for(int i=0;i<5;i++)
	{
	   sum=sum+i;
	}
	System.out.println(sum); 
	}
}


import java.util.Scanner;
public class Main // sum un ortalamasini tapmaq arrayle
{
	public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    System.out.println("Arrayin olcusunu daxil edin");
	int a = sc.nextInt();
	int[]arr=new int[a];
	for(int i=0; i<arr.length;i++)
	{
	    arr[i]=sc.nextInt();
	}
	int sum=0;
	for(int j=0;j<arr.length;j++)
	{
	   sum=sum+arr[j];
	}
	
	System.out.println(sum); 
	}
}

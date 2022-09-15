# Find-Factorial-using-Recursion
public class Recursion {
    public static int Fact(int n)
    {

     if(n==0)
     return 1;
     int ans=Fact(n-1);
     int factorial=n*ans;
   //  System.out.println(factorial);
     return factorial;
    
    }
    public static void main(String[] args)
    {
    int n=9;
   int res= Fact(n);
System.out.println(res);
    }
    
}

import java.util.Scanner ;
public class Program
{
    public static void main(String[] args){

 
    System.out.println("enter interval");
    Scanner in=new Scanner(System.in);
    int c,i;
    int a=in.nextInt();
    int b=in.nextInt();
    while (a<b)
    {
      c=0;
      for(i=2;i<a;i++)
      {
        if(a%i==0)
        {
          c=1;
          break;
        }
      }
      if(c==0)
      {
        System.out.println(a);
        
      }
      a++;
    }
    
   }
 }

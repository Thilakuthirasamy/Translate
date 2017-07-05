import java.util.*;
public class Translate
{
    public static void main(String []args)
    {
        Scanner s=new Scanner(System.in);
        int num=s.nextInt();
        int num2=0,count[],i=0,n,j=0;
        count=new int[100];
        if(num>0)
        num2++;
        while(num>9)
        {
            n=(num%100);
            if((n<27) &&(n!=0))
            {
                num2++;
                count[i]=n;
                i++;
            }
            num/=10;
        }
        for(i=0;i<100;i++)
        {
            for(j=i+2;j<100;j++)
            {
                if(count[j]!=0)
                num2++;
                else
                break;
            }
        }
        System.out.println(num2);
    }
}


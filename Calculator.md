import java.util.Scanner;

class Main
{
    public static void main(String args[])
    {
        char op;
        double a,b,c;
        Scanner sc=new Scanner(System.in);
        

        System.out.println("Choose an operator : +, -, * or /");
        op=sc.next().charAt(0);
        a=sc.nextDouble();
        b=sc.nextDouble();

        switch(op)
        {
            case'+':
        c=a+b;
        System.out.println(a+"+"+b+"="+c);
        break;

        case'-':
        c=a-b;
        System.out.println(a+"-"+b+"="+c);
        break;

        case'*':
        c=a*b;
        System.out.println(a+"*"+b+"="+c);
        break;

        case'/':
        c=a/b;
        System.out.println(a+"/"+b+"="+c);
        break;
        default:
        System.out.println("Invalid Oprator");
        }
        //sc.close();
    }
}

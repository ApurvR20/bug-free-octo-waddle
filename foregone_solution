import java.util.Scanner;
import java.math.BigInteger;
public class q1 {
int main()
{
    int T,i,j,l; 
    Scanner sc = new Scanner(System.in);
    StringBuffer input = new StringBuffer(); 
    T=sc.nextInt(); // No.of testcases
    for(i=1;i<=T;i++)
    {
        input.append(sc.nextLine());//Input
        l=input.length();
        StringBuffer output = new StringBuffer(l);
        for(j=0;j<l;j++)
        {
            if(input.charAt(i)=='4')
            {
                input.setCharAt(i,'3'); // switching all 4s in input to 3s
                output.setCharAt(i,'1'); 
            }   /* Putting the difference created due to switching 4s in output by these two statements */
            else { output.setCharAt(i,'0'); }
        }
        BigInteger a = new BigInteger(output.toString()); // to remove all preceeding 0s that might show up in the StringBuffer
        BigInteger b = new BigInteger(input.toString()); // aise hee
        System.out.println("Case #"+(i)+": "+ a+" "+b);
        input = null; // resetting for next text case
        output = null;
    }
    return 0;
}}

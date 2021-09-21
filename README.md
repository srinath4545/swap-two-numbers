# swap-two-numbersimport java.util.Scanner;
public class Swap {
public static void main(String[] args)
{
int x = 100, y = 200;
System.out.println(&quot;Before Swap&quot;);
System.out.println(&quot;x = &quot; + x);
System.out.println(&quot;y = &quot; + y);
int temp = x;
x = y;
y = temp;
System.out.println(&quot;After swap&quot;);
System.out.println(&quot;x = &quot; + x);
System.out.println(&quot;y = &quot; + y);
}
}

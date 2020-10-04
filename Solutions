# Practice-5

public class Solution1
{
    public static int recursion(int n)
    {
        int N=n;
        if (N==1)
        {
            return 1;
        }
        while (N!=0)
        {
         System.out.println(n);
         N=N-1;
        }
        return recursion((n-1));
    }
    public static void main(String[] args)
    {
    System.out.println(recursion(5));
    }
}


public class Solution2
{
    public static String recursion(int n)
    {
        if (n == 1)
        {
            return "1";
        }
        return recursion(n - 1) + " " + n;
    }

    public static void main(String[] args)
    {
        System.out.println(recursion(10));
    }
}

public class Solution3
{
    public static String recursion(int a, int b)
    {
        if (a > b)
        {
            if (a == b)
            {
                return Integer.toString(a);
            }
            return a + " " + recursion(a - 1, b);
        } else
            {
                if (a == b)
             {
                    return Integer.toString(a);
             }
            return a + " " + recursion(a + 1, b);
            }
    }
    public static void main(String[] args)
    {
        System.out.println(recursion(20, 15));
        System.out.println(recursion(10, 15));
    }
}

public class Solution4 {
    public static int recursion(int len, int sum, int k, int s)
    {
        if (len == k)
        {
            if (sum == s)
            {
                return 1;
            }
            else
            {
                return 0;
            }
        }
        int c = (len == 0 ? 1 : 0);
        int res = 0;
        for (int i = c; i < 10; i++)
        {
            res += recursion(len + 1, sum + i, k, s);
        }
        return res;
    }
    public static void main(String[] args)
    {
        System.out.println(recursion(0, 0, 3, 15));
    }
}

public class Solution5
{
    private static int n=0;
    public static int rec(int N)
    {
        if (N != 0)
        {
            N = N/ 10;
            n=n+1;
            return rec(N);
        }
    if (N==0)
    {
        System.out.println(n);
    }
        return 0;
    }


    public static void main(String[] args)
    {

        rec(1738);
    }
}


public class Solution6
{
    private static int recursion(int n, int var)
    {
        if (n > 1)
        {
            if (n % var != 0)
            {
                return recursion(n, var+1);
            } else if (n % var == 0)
            {
                if (var == n)
                {
                    System.out.println("YES");
                }
                else
                {
                    System.out.println("NO");
                }
                return 0;
            }
        }
        return 0;
    }
    public static void main(String[] args)
    {
        recursion(12345678,2);
    }
}


public class Solution7
{
    private static int recursion(int n, int var)
    {
        if (n > 1)
        {
            if (n % var == 0)
            {
                System.out.println(var);
                return recursion(n, var+1);
            } else if (n % var != 0 && var < n)
            {
                return recursion(n, var+1);
            } else if ( n == var)
            {
                System.out.println(n);
                return 0;
            }
        }
        return 0;
    }

    public static void main(String[] args)
    {
        recursion(7,7);
    }
}


public class Solution8
{
    private static int recursion(String str, int i, int check)
    {
        char[] timeChar = str.toCharArray();
        if ((i == timeChar.length - 1) && (check == 1))
        {
            System.out.println("YES");
            return 0;
        }
        check = 0;
        if ((timeChar.length > i) && (timeChar[i] == timeChar[timeChar.length - i - 1]))
        {
            return recursion(str, i + 1, 1);
        } else
            System.out.println("NO");
        return 0;
    }
    public static void main(String[] args)
    {
        recursion("Время",0,0);
    }
}

public class Solution9
{
    public static int recursion(int a, int b)
    {
        if (a > b + 1)
        {
            return 0;
        }
        if (a == 0 || b == 0)
        {
            return 1;
        }
        return recursion(a, b - 1) + recursion(a - 1, b - 1);
    }
    public static void main(String[] args) {
        System.out.println(recursion(5, 8));
    }
}

public class Solution10
{
    public static int recursion(int n, int i)
    {
        return (n==0) ? i : recursion( n/10, i*10 + n%10 );
    }
    public static void main(String[] args)
    {
        System.out.println(recursion(158, 0));
    }
}

import java.util.Scanner;

public class Solution11
{
    public static int recursion()
    {
        Scanner in = new Scanner(System.in);
        int n = in.nextInt();
        if (n == 1)
        {
            int m = in.nextInt();
            if (m == 1)
            {
                return recursion() + n + m;
            }
            else
            {
                int k = in.nextInt();
                if (k == 1)
                {
                    return recursion() + n + m + k;
                }
                else
                {
                    return n + m + k;
                }
            }
        } else {
            int m = in.nextInt();
            if (m == 1)
            {
                return recursion() + n + m;
            }
            else
            {
                return n + m;
            }
        }
    }
    public static void main(String[] args)
    {
        System.out.println(recursion());
    }
}


public class Solution12
{
    public static void recursion()
    {
        java.util.Scanner in = new java.util.Scanner(System.in);
        int n = in.nextInt();
        if (n > 0)
        {
            if (n % 2 == 1)
            {
                System.out.println(n);
                recursion();
            }
            else
            {
                recursion();
            }
        }
    }
    public static void main(String[] args)
    {
        recursion();
    }
}

public class Solution13
{
    public static void recursion()
    {
        java.util.Scanner in = new java.util.Scanner(System.in);
        int n = in.nextInt();
        if (n > 0)
        {
            int m = in.nextInt();
            System.out.println(n);
            if (m > 0)
            {
                recursion();
            }
        }
    }
    public static void main(String[] args)
    {
        recursion();
    }
}

public class Solution14
{
    public static int recursion(int n)
    {
        if (n < 10)
        {
            return n;
        }
        else
        {
            System.out.print(n % 10 + " ");
            return recursion(n / 10);
        }
    }
    public static void main(String[] args)
    {
        System.out.println(recursion(123));
    }
}


public class Solution15
{
    public static String recursion(int n)
    {
        if (n < 10)
        {
            return Integer.toString(n);
        }
        else
        {
            return recursion(n / 10) + " " + n % 10;
        }
    }
    public static void main(String[] args)
    {
        System.out.println(recursion(153));
    }
}

public class Solution16
{
    public static void recursion(int max, int count)
    {
        java.util.Scanner in = new java.util.Scanner(System.in);
        int n = in.nextInt();
        if (n > 0)
        {
            if (n > max)
            {
                recursion(n, 1);
            }
            else if (n == max)
            {
                recursion(max, ++count);
            }
            else
            {
                recursion(max, count);
            }
        }
        else
        {
            System.out.println(count);
        }
    }
    public static void main(String[] args)
    {
        recursion(0, 0);
    }
}

public class Solution17
{
    public static int recursion()
    {
        java.util.Scanner in = new java.util.Scanner(System.in);
        int n = in.nextInt();
        if (n == 0)
        {
            return 0;
        }
        else
        {
            return Math.max(n, recursion());
        }
    }
    public static void main(String[] args)
    {
        System.out.println(recursion());
    }
}

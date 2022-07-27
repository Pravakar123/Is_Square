import java.io.*;
import java.util.*;

public class Solution {

    public static void main(String[] args) {
        /* Enter your code here. Read input from STDIN. Print output to STDOUT. Your class should be named Solution. */
        Scanner s=new Scanner(System.in);
        int l=s.nextInt();
        int b=s.nextInt();
        int area=l*b;
        if(l==b)
            System.out.println("Square");
        else
            System.out.println("Not a Square");
    }
}

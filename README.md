# minConv
package minconversion;
import java.util.*;
public class MinConversion {
    public static void main(String[] args) {
       Scanner s=new Scanner(System.in);
       int min=s.nextInt();
       conversion(min);
    }
    public static void conversion(int m){
        int yrs=m/525600;
        int a= m%525600;
        int days = a/1440;
        System.out.println(m+" minutes consists of "+yrs+" years "+days+" days.");
    }
}

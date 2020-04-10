# pattern10
Coding block
import java.util.*;
class Main{
  public static void main(String[] args){
    Scanner sc = new Scanner(System.in);
    int n = sc.nextInt();
    int nsp = 0;
    int nst = 2*n -1;
    //row
    int row = 1;
    while(row<= n){
      // work space
    int csp = 1;
    while(csp<= nsp){
      System.out.print(" ");
      csp++;
    }
      
      //work Star
    int cst = 1;
    while(cst<= nst){
       System.out.print("*");
       cst++;
    }
       System.out.println();
       row = row +1;
       nsp = nsp + 1;
       nst = nst - 2;
    }
    
  }
}

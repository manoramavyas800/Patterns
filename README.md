# Patterns
/*  print patterns
5
   *  
  ***  
 *****  
*******   */

import java.util.Scanner;
public class Codeforces {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int k=0;
        for(int i=1;i<n;i++){
            k++;
            for(int j=1;j<=n+i;j++){
                if(j<=3+k&&j>=5-k){
                    System.out.print("*");
                }else{
                    System.out.print(" ");
                }
            }
            System.out.println();
        }
    }
}
//Second solution

import java.util.Scanner;
public class java {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        for (int i = 1; i <= n; i++) {
                for (int l = 1; l <= n - i; l++) {
                    System.out.print(" ");
                }
                for (int k = 1; k <= 2 * i - 1; k++) {
                    System.out.print("*");
                }
                System.out.println();
            }

        }
}

/*
7
*
**
***
****
***
**
*

      */

      import java.util.Scanner;
public class java {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int k = 0;
        for (int i = 1; i <= n; i++) {
            int i1 = i <= 4 ? k++ : k--;
            for (int j = 1; j <= k; j++){
                    System.out.print("*");
                }
            System.out.println();
            }
        
            }
        }

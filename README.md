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
/* print patterns
*****
*****
*****
*****
*****   */

public class Codeforces {
    public static void main(String[] args) {
        int n = 5;
        for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= n; j++) {
                System.out.print("*" );
            }
            System.out.println();
        }
       }

    }

    /*
    print patterns
*********  
 *******    
  *****      
   ***        
    *     */

    import java.util.Scanner;
public class Codeforces {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int k=0;
        for(int i=1;i<=n;i++){
            k++;
            for(int j=1;j<=2*n+i;j++){
                if(j>=k&&j<=2*n-k){
                    System.out.print("*");
                }else{
                    System.out.print(" ");
                }

            }
            System.out.println();
        }
       }

    }

/*  print pattern!!
0 
1 0 
0 1 0 
1 0 1 0 
0 1 0 1 0   */

public class Paatterns {
    public static void main(String[] args) {
       int n = 5;
        for (int i = 1; i <= n; i++) {
            for (int j = 1; j <= i; j++) {
                if((i+j)%2==0){
                    System.out.print(0+" ");
                }else{
                    System.out.print(1+" ");
                }
            }
            System.out.println();
        }
        
       }
    }
//print buterfluy problem 

import java.util.Scanner;
public class Code1 {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = 4;
        //upper half
        for (int i = 1; i <= n; i++) {

            //1 st part
            for (int j = 1; j <= i; j++) {
                System.out.print("*");
            }
            //space
            int space = 2 * (n - i);
            for (int j = 1; j <= space; j++) {
                System.out.print(" ");
            }
            //second part
            for (int j = 1; j <= i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
        for (int i = n; i >= 1; i--) {

            //1 st part
            for (int j = 1; j <= i; j++) {
                System.out.print("*");
            }
            //space
            int space = 2 * (n - i);
            for (int j = 1; j <= space; j++) {
                System.out.print(" ");
            }
            //second part
            for (int j = 1; j <= i; j++) {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}

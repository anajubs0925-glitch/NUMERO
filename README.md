import java.util.Scanner;

public class Numero {
    public static void main(String[] args) {
        Scanner sc = new 
Scanner(System.in);

        int n = sc.nextInt();

        switch (n) {
            case 1: 
                 System.out.println("Um"); 
                 break;
            case 2: 
                 System.out.println("Dois"); 
                 break;
            case 3: 
                System.out.println("Três"); 
                break;
            case 4: 
                 System.out.println("Quatro");
                 break;
            case 5: 
                 System.out.println("Cinco"); 
                 break;
        }
    }
}

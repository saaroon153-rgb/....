import java.util.Scanner;

/**
 * New year congrates generator.
 */
public class Echo {
    public static void main(String[] args) {
        String line1, line2;
        Scanner in = new Scanner(System.in);
     
        System.out.print("Type your name (English): ");
        line1 = in.nextLine();
        System.out.println("\nHappy new year to you " + line1 + " <3\nGod bless you :)");
    }    
}

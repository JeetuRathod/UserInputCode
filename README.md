import java.util.*;
public class Assign{
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter Your Age: ");
        int age = sc.nextInt();
        if(age >= 18){
            System.out.println("You are eligible for Voting!");
        }else{
            System.out.println("You Are not eligible for Voting!");
        }
    }
}

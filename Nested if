
import java.util.Scanner;

public class StudentAchievement {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter student's marks (0-100): ");
        int marks = scanner.nextInt();

        if (marks >= 0 && marks <= 100) {
            if (marks >= 80) {
                System.out.println("Level 7 - Outstanding Achievement");
            } else if (marks >= 70) {
                System.out.println("Level 6 - Meritorious Achievement");
            } else if (marks >= 60) {
                System.out.println("Level 5 - Good Achievement");
            } else if (marks >= 50) {
                System.out.println("Level 4 - Satisfactory Achievement");
            } else if (marks >= 40) {
                System.out.println("Level 3 - Fair Achievement");
            } else {
                System.out.println("Level 2 - Poor Achievement");
            }
        } else {
            System.out.println("Invalid marks. Please enter marks between 0 and 100.");
        }

        scanner.close();
    }
}



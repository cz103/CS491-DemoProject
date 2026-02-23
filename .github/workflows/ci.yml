import java.util.Scanner;

public class BMI {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Enter weight in kilograms: ");
        double weight = scanner.nextDouble();

        System.out.print("Enter height in meters: ");
        double height = scanner.nextDouble();

        scanner.close();

        if (height <= 0) {
            System.out.println("Height must be a positive number.");
            return;
        }

        double bmi = weight / (height * height);
        System.out.printf("Your BMI is %.2f%n", bmi);

        String category;
        if (bmi < 18.5) {
            category = "Underweight";
        } else if (bmi < 25) {
            category = "Normal weight";
        } else if (bmi < 30) {
            category = "Overweight";
        } else {
            category = "Obesity";
        }

        System.out.println("Category: " + category);
    }
}
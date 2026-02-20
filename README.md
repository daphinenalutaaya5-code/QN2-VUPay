# QN2-VUPay
VUPay project
import java.util.Scanner;

public class VUCourses {

    public static void main(String[] args) {

        // Variable declarations
        String moduleCode;
        String moduleName;
        int tuition;

        Scanner scanner = new Scanner(System.in);

        System.out.println("====== Welcome to VUPay ======");
        System.out.print("Enter Module Code (BSF, BIT, BCS, BCE): ");
        moduleCode = scanner.nextLine().toUpperCase();

        if (moduleCode.equals("BSF")) {

            moduleName = "BSc. Software Engineering";
            tuition = 900000;

            System.out.println("Module Code: " + moduleCode);
            System.out.println("Module Name: " + moduleName);
            System.out.println("Tuition Fee: UGX " + tuition);

        } else if (moduleCode.equals("BIT")) {

            moduleName = "BSc. Information Technology";
            tuition = 750000;

            System.out.println("Module Code: " + moduleCode);
            System.out.println("Module Name: " + moduleName);
            System.out.println("Tuition Fee: UGX " + tuition);

        } else if (moduleCode.equals("BCS")) {

            moduleName = "BSc. Computer Science";
            tuition = 800000;

            System.out.println("Module Code: " + moduleCode);
            System.out.println("Module Name: " + moduleName);
            System.out.println("Tuition Fee: UGX " + tuition);

        } else if (moduleCode.equals("BCE")) {

            moduleName = "BSc. Computer Engineering";
            tuition = 950000;

            System.out.println("Module Code: " + moduleCode);
            System.out.println("Module Name: " + moduleName);
            System.out.println("Tuition Fee: UGX " + tuition);

        } else {

            System.out.println("Wrong Module Code details");

        }

        scanner.close();
    }
}

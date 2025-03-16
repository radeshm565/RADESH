import java.util.Scanner;

abstract class Telephone {
    abstract void call();
    abstract void lift();
    abstract void disconnect();
}

class SmartTelephone extends Telephone {
    void call() {
        System.out.println("Making a call...");
    }
    void lift() {
        System.out.println("Lifting the receiver...");
    }
    void disconnect() {
        System.out.println("Call disconnected.");
    }
    
    void browseInternet() {
        System.out.println("Browsing the internet...");
    }
}

// Main Method to Run the Program
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        SmartTelephone smartPhone = new SmartTelephone();
        
        while (true) {
            System.out.println("\nChoose an action:");
            System.out.println("1. Make a call");
            System.out.println("2. Lift receiver");
            System.out.println("3. Disconnect call");
            System.out.println("4. Browse Internet");
            System.out.println("5. Exit");
            System.out.print("Enter your choice: ");
            
            int choice = scanner.nextInt();
            
            switch (choice) {
                case 1:
                    smartPhone.call();
                    break;
                case 2:
                    smartPhone.lift();
                    break;
                case 3:
                    smartPhone.disconnect();
                    break;
                case 4:
                    smartPhone.browseInternet();
                    break;
                case 5:
                    System.out.println("Exiting...");
                    scanner.close();
                    return;
                default:
                    System.out.println("Invalid choice. Please try again.");
            }
        }
    }
}

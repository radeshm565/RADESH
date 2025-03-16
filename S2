import java.util.Scanner;

class Person {
    String name;
    int age;
    String phone;
    String address;

    Person(String name, int age, String phone, String address) {
        this.name = name;
        this.age = age;
        this.phone = phone;
        this.address = address;
    }
    
    void printDetails() {
        System.out.println("Name: " + name + ", Age: " + age + ", Phone: " + phone + ", Address: " + address);
    }
}

class Student extends Person {
    String course;

    Student(String name, int age, String phone, String address, String course) {
        super(name, age, phone, address);
        this.course = course;
    }

    void printCourse() {
        System.out.println("Course: " + course);
    }
}

class Teacher extends Person {
    String subject;

    Teacher(String name, int age, String phone, String address, String subject) {
        super(name, age, phone, address);
        this.subject = subject;
    }
    
    void printSubject() {
        System.out.println("Subject: " + subject);
    }
}

// Main Method to Run the Program
public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        // Input for Student
        System.out.print("Enter student name: ");
        String studentName = scanner.nextLine();
        System.out.print("Enter student age: ");
        int studentAge = scanner.nextInt();
        scanner.nextLine(); // Consume newline
        System.out.print("Enter student phone: ");
        String studentPhone = scanner.nextLine();
        System.out.print("Enter student address: ");
        String studentAddress = scanner.nextLine();
        System.out.print("Enter student course: ");
        String studentCourse = scanner.nextLine();
        
        Student student = new Student(studentName, studentAge, studentPhone, studentAddress, studentCourse);
        student.printDetails();
        student.printCourse();
        
        System.out.print("Enter teacher name: ");
        String teacherName = scanner.nextLine();
        System.out.print("Enter teacher age: ");
        int teacherAge = scanner.nextInt();
        scanner.nextLine(); // Consume newline
        System.out.print("Enter teacher phone: ");
        String teacherPhone = scanner.nextLine();
        System.out.print("Enter teacher address: ");
        String teacherAddress = scanner.nextLine();
        System.out.print("Enter teacher subject: ");
        String teacherSubject = scanner.nextLine();
        
        Teacher teacher = new Teacher(teacherName, teacherAge, teacherPhone, teacherAddress, teacherSubject);
        teacher.printDetails();
        teacher.printSubject();
        
        scanner.close();
    }
}

# Student-details

package classobject;
import java.util.Scanner;

public class Student{
    static class studentdet{
        String name;
        int rollno;
        int age;
        String course;
        public void studentDetails(){
            Scanner scanner=new Scanner(System.in);
            System.out.print("Enter the name:");
            name=scanner.nextLine();
            System.out.print("Enter roll number:");
            rollno=scanner.nextInt();
            System.out.print("Enter age:");
            age=scanner.nextInt();
            System.out.print("Enter course:");
            course=scanner.nextLine();
        }

        public void displaydetails(){
            System.out.println("STUDENT DETAILS");
            System.out.println("Name:"+name);
            System.out.println("Roll number:"+rollno);
            System.out.println("Age:"+age);
            System.out.println("Course:"+course);
        }
    }
    public static void main(String[] args){
        Student.studentdet details=new Student.studentdet();
        details.studentDetails();
        details.displaydetails();
    }
}



Output-

Enter the name:Madhumitha
Enter roll number:52
Enter age:18
Enter course:STUDENT DETAILS
Name:Madhumitha
Roll number:52
Age:18
Course:

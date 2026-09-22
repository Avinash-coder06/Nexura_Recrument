# Nexura_Recrument




       
        
        
        
        
        
        import java.util.Scanner;
        public class Nexura_Recrument {
    static void main() {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter your first subject marks out of 100 ");
        int a =  sc.nextInt();
        System.out.println();
        System.out.print("Enter your second subject marks out of 100 ");
        int b =  sc.nextInt();
        System.out.println();
        System.out.print("Enter your third subject marks out of 100 ");
        int c =  sc.nextInt();
        System.out.println();
        System.out.print("Enter your fourth subject marks out of 100 ");
        int d =  sc.nextInt();
        System.out.println();
        System.out.print("Enter your fifth subject marks out of 100 ");
        int e =  sc.nextInt();
        System.out.println();int total = a+b+c+d+e;
        System.out.println("Total is "+total);
        double percent = total/5;
        System.out.println("Percent is "+percent+"%");
        String grade = "_";
        if(percent >=90)grade = "A+";
        else if(percent >=80 && percent<90)grade = "A";
        else if(percent >=70 && percent<80)grade = "B";
        else if(percent >=60 && percent<70)grade = "C";
        else if(percent >=50 && percent<60)grade = "D";
        else if(percent >=33 && percent<50)grade = "E";
        else grade = "F";
        System.out.println("your grade is "+grade);
        if(percent >= 33) System.out.println("Pass");
        else System.out.println("Fail");
    }
    }












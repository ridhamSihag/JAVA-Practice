# JAVA-Practice
Solving questions daily
<br>
qsn 1
<br>
public class practice {
    public static void main(String[] args) {
        for(int i=1;i<=6;i++)
        {
            for (int j=1;j<=i;j++)
            {
                System.out.print("*");

            }
            System.out.println();
        }
    }
    
}

// qsn 2 #oops


class Employee{
    int salary;
    String name;

    public int getsalary(){
        return salary;
    }
    public String getname(){
        return name;
    }
    public void setname(String n){

        name = n;
    }
}

public class Oops {
    public static void main(String[] args) {
        Employee harry = new Employee();
        harry.setname("Ridham Sihag");
        System.out.println(harry.getname());
        System.out.println(harry.getsalary());

        CellPhone Apple = new CellPhone();
        Apple.ring();
        

        
        
        
    }


    
}

class CellPhone{
    public void ring(){
        System.out.println("Ringing...");

    }
    public void vib(){
        System.out.println("Vibrating...");
    }

}




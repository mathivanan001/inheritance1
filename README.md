# inheritance1

import java.util.Scanner;
class Employee {
int salary = 50000;
void basic_salary() {
System.out.println(&quot;Basic salary is &quot; + salary);
}
}
class Programmer extends Employee {
int increment = 10000;
int prog_salary = salary + increment;
void print_salary() {
System.out.println(&quot;Programmer salary is &quot; + prog_salary);
}
}
public class emp {
public static void main(String args[]) {
Programmer p1 = new Programmer();
p1.basic_salary();
p1.print_salary();
}
}
Output:
Basic Salary is50000
Programmer Salary is60000

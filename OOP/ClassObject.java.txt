class Student{
int rollNo=101;
String name="Ponmalar";
void display(){
System.out.println("Roll Number:"+rollNo);
System.out.println("Name:"+name);
}
}
class ClassObject{
public static void main(String[]args){
Student s=new Student();
s.display();
}
}
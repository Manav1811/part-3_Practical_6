# part-3_Practical_6

//save by Demo.java  
package pack;  
public class Demo {  
    public void msg() {
        System.out.println("21CE063");
    }  
}  

//save by Test.java  
package mypack;  
import pack.Demo;  
class Test {  
    public static void main(String args[]) {  
        Demo obj = new Demo();  
        obj.msg();  
    }  
}

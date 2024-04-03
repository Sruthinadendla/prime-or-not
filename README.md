# prime-or-not
import java.util.*;

public class Main {
    public static void main(String[] args) {
      Scanner sc=new Scanner(System.in);
      int count=0,sum=0,grade;
      do{
        grade=sc.nextInt();
        if(grade>=0){
          sum+=grade;
          count++;
        }
      }while(grade>=0);
      if(count>0){
        double avg=(double)sum/count;
        System.out.println("the average is"+avg);
      }
      else{
        System.out.println("no grades entered");
      }
  }
}

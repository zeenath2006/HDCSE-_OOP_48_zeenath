import  java.util.Scanner;
public class Main {
  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in);
 System.out.println ("Enter Frist Number");
    int FristNumber = scanner.nextInt();

    
    System.out.println ("Enter Second Number");
    int SecondNumber = scanner.nextInt();

    if(FristNumber > SecondNumber){
      System.out.println("The Larger FristNumber -:" + FristNumber);
    } else if (SecondNumber > FristNumber){
      System.out.println("The Larger SecondNumber -:" + SecondNumber);
    } else {
      System.out.println("Equal -: ");
    }
      
    

    

    
  }
}

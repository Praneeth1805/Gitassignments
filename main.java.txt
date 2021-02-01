import java.util.Scanner;

class Main{
  public static void main(String[] args) {
    String name;
    Scanner inputName = new Scanner (System.in);
    System.out.print("Please enter your name:");
    name = inputName.next();
    System.out.println("Hello "+name);
    inputName.close();
  }
}
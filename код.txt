import java.util.Scanner;
public class Main {
  public static void main(String[] args) {
    Scanner in = new Scanner(System.in);
    int A = in.nextInt();
    int B = in.nextInt();
    int C = in.nextInt();
    int D = in.nextInt();
    int Unic = 1;
    if (B!=A){
        Unic++;
    }
    if (C!=A && C!=B){
        Unic++;
    }
    if (D!=A && D!=B && D!=C){
        Unic++;
    }
    System.out.println(Unic);
  }
}

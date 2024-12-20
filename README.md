import java.util.Scanner;



public class Main {

    public static void main(String[] args) {

        System.out.println("Nの値は1以上30以下。");



        Scanner scanner = new Scanner(System.in);

        int N = scanner.nextInt();



        int fare = 100 + 10 * N;

        System.out.println("運賃: " + fare);



        scanner.close();

    }

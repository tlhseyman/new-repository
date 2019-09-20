package sample;

public class Udemy2ForLoop {
    public static void main(String[] args) {
               //Multiplication table;

   System.out.println("\t\t\t Multiplication Table");
        for (int q = 1; q < 10; q++) {
            System.out.print("\t   " + q);
        }

   System.out.println("\n---------------------------------------------------------------------------");
       for (int z = 1; z < 10; z++) {
            System.out.print(z + " | ");
            for (int c=1; c<10; c++){
                System.out.printf("\t%3d ", z*c);
            }
            System.out.println();
        }
    }
}

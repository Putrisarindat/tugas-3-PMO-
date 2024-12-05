public class ContohOperatorGabunganPutriSarindat {
    public static void main(String[] args) {
        
        int a = 5;  
        int b = 3;  

        int hasilAnd = a & b;  
        System.out.println("Bitwise AND: " + hasilAnd);

        int hasilOr = a | b;   
        System.out.println("Bitwise OR: " + hasilOr);

        boolean x = true;
        boolean y = false;

        boolean hasilLogikaAnd = x && y;  
        System.out.println("Logical AND: " + hasilLogikaAnd);

        boolean hasilLogikaOr = x || y;   
        System.out.println("Logical OR: " + hasilLogikaOr);

        int angka = 10;

        angka = 20;
        System.out.println("Nilai setelah penugasan: " + angka);

        angka += 5;  
        System.out.println("Setelah operasi += : " + angka);
    }
}



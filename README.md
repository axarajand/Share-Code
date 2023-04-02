import java.util.Stack;

public class App {
    public static void main(String[] args) throws Exception {
        Stack<String> Mainan = new Stack<String>();

        Mainan.push("Bola");
        Mainan.push("Voli");
        Mainan.push("Basket");

        System.out.println("Isi dari stack  \t\t : " + Mainan);
        System.out.println("Index yang dihapus  \t\t : " + Mainan.pop());
        System.out.println("Index terakhir  \t\t : " + Mainan.firstElement());
        System.out.println("Index pertama  \t\t\t : " + Mainan.lastElement());
        System.out.println("Index stack  \t\t\t : " + Mainan.size());

        System.out.println("Apakah stack kosong  \t\t : " + Mainan.isEmpty());
        System.out.println("Ambil stack ke-2  \t\t : " + Mainan.get(1));
        System.out.println("Isi dati stack setelah pop  \t : " + Mainan);
    }   
}   

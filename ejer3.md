public class Sum {
    public static void main(String[] args) {
        int num1 = 5;
        int num2 = 10;
        int num3 = 15;
        System.out.println("The sum of " + num1 + ", " + num2 + ", and " + num3 + " is " + suma(num1, num2, num3));
    }

    public static int suma(int a, int b, int c) {
        return a + b + c;
    }
}


//segunda parte

public class Coche {
    private int puerta;

    public Coche() {
        puerta = 0;
    }

    public void poner_puerta() {
        doors++;
    }

    public int getPuerta() {
        return doors;
    }
}

public class Main {
    public static void main(String[] args) {
        Coche micoche = new Coche();
        micoche.poner_puerta();
        System.out.println("mi coche tiene " + micoche.getPuerta() + " puerta(s).");
    }
}

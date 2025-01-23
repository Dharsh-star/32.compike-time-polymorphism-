# 32.compike-time-polymorphism-

public class Main {
    public int addition(int X, int Y) {
        return X+Y;
    }
    public int addition(int X, int Y, int Z) {
        return X+Y+Z;
    }
    public double addition(double X, double Y) {
        return X+Y;
    }

    
    public static void main(String[] args) {
        Main number = new Main();
        int res1 = number.addition(444,555);
        System.out.println("Addition of two integers:" + res1);
        int res2 = number.addition(333,444,555);
        System.out.println("Addition of three integers:" + res2);
        double res3 = number.addition(10.15, 20.22);
        System.out.println("Addition of two double:" + res2);
        
    }
    
}

Output

Addition of two integers:999
Addition of three integers:1332
Addition of two double:1332

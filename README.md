public class DoArithmetic {
    double inputA;
    double inputB;
    double output;
    String operator;
    public double Add(double inputa, double inputb)
    {
      return inputa+inputb;
    }
}

public class Calculator {
    public static void main(String[] args) {
        System.out.println("Starting Calculaor");
        run();
    }
    public static void run() {
        //run my Method choreography
        DoArithmetic a = new DoArithmetic();
      double result = a.Add(2,2);
      System.out.println(result);

    }
}


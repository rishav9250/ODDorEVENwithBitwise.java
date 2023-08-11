# ODDorEVENwithBitwise.java
here is a code ofODDorEVENwithBitwise in java.

public class ODDorEVENwithBitwise {
    public static void ODDorEven(int n){
        int Bitmast =1;
        if((n&Bitmast)==0){
            System.out.println("even");
        }
    else{
        System.out.println("odd");
    }
    }
public static void main(String[] args) {
    ODDorEven(4);
}
}

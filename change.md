public class Main {
    public static void main(String[] args) {
        printThreeWords();
        checkSumSing();
        printColor();
    }
    // MethodOne:
    public static void printThreeWords(){
        System.out.println("Orange");
        System.out.println("Banana");
        System.out.println("Apple");
    }
    // MethodTwo:
    public static int checkSumSing(){
        int a = 5;
        int b = 10;
        int result = a + b;

        if(result >= 0){
            System.out.println("Сумма положительна");
        } else {
            System.out.println("Сумма отрицательная");
        }
        return result;
    }
    // MethodThree :
    public static void printColor(){
        int value = 10;
        if ( value <= 0){
            System.out.println("Красный");
        } else if (value <= 100){
            System.out.println("Желтый");
        }else {
            System.out.println("Зеленый ");
        }

    }
    // MethodFour :
    public static void compareNumbers(){
        int a = 5;
        int b = 10;
        if ( a >= b){
            System.out.println("а >= b");
        }else {
            System.out.println(" a < b");
        }
    }
}
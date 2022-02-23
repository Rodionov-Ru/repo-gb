public class Das {
    public static void main(String[] args) {
        HomeWork_1(5, 4);
        HomeWork_2(-10);
        HomeWork_3(234);
        HomeWork_4(5,"Привет");
    }
    public static int HomeWork_1 (int a , int b){
        int result = a + b;
        if(result > 20 ){
            System.out.println("False");
        }else if (result <10){
            System.out.println("False");
        }else{
            System.out.println("True");
        }
        return result;
    }
    public static void HomeWork_2(int a){
        if (a < 0){
            System.out.println("отрицательное  число");
        }else if (a > 0){
            System.out.println("положительное число ");
        }
    }
    public static void HomeWork_3(int a){
        if ( a < 0){
            System.out.println("True");
        }else {
            System.out.println("False");
        }
    }
    public static void HomeWork_4(int number , String attempts){
        for(int a =0; a < number;a++){
            System.out.println(attempts);
        }
    }

}
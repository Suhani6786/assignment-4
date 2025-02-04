public class ReverseString {
    public static void main(String[] args) {
        String input = "World";
        String reversed = new StringBuilder(input).reverse().toString();
        System.out.println(reversed);
    }
}


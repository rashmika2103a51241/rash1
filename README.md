public class MaxNumberPosition {
    public static void main(String[] args) {
        int[] numbers = {5, 8, 2, 10, 10, 4, 6, 10, 3};

        int max = numbers[0];
        int maxIndex = 0;

        for (int i = 1; i < numbers.length; i++) {
            if (numbers[i] > max) {
                max = numbers[i];
                maxIndex = i;
            }
        }

        System.out.println("Maximum number: " + max);
        System.out.println("Position/Index of the first occurrence: " + maxIndex);
    }
}

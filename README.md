import java.util.Scanner;

public class HotelBooking {
    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        int roomNo;
        String guestName;
        double price;
        boolean available;

        System.out.print("Enter Room Number: ");
        roomNo = sc.nextInt();

        sc.nextLine();

        System.out.print("Enter Guest Name: ");
        guestName = sc.nextLine();

        System.out.print("Enter Room Price: ");
        price = sc.nextDouble();

        System.out.print("Is Room Available? (true/false): ");
        available = sc.nextBoolean();

        System.out.println("\n--- Booking Details ---");
        System.out.println("Room Number: " + roomNo);
        System.out.println("Guest Name: " + guestName);
        System.out.println("Price: " + price);
        System.out.println("Available: " + available);

        sc.close();
    }
}

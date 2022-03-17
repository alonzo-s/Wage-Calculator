public class Assignment1 
{
    public static void main(String[] args)
    {
        // Declare variables
        String firstName;
        int hours;
        double hourlyRate;
        double grossPay;
        
        // Scanner object to read input
        Scanner keyboard = new Scanner(System.in);
        
        // Input name
        System.out.print("What's your name? ");
        firstName = keyboard.nextLine();
        
        // Input whole hours with validation
        System.out.print("How many whole hours did you work " +firstName +"? ");
        hours = keyboard.nextInt();
        while (hours < 0)
        {
            System.out.println("Invalid Input");        // Error message
            System.out.print("Enter whole hours worked: ");
            hours = keyboard.nextInt();
        }
        
        // Input hourly rate with validation
        System.out.print("What's your hourly pay rate " +firstName + "? ");
        hourlyRate = keyboard.nextDouble();
        while (hourlyRate <= 0)
        {
            System.out.println("Invalid Input");        // Error message
            System.out.print("Enter a rate greater than zero: ");
            hourlyRate = keyboard.nextDouble();
        }
        
        // Calculate pay
        grossPay = hours * hourlyRate;
        
        // Output info
        System.out.println(firstName + "'s gross pay is due " +grossPay);
        
    }
}

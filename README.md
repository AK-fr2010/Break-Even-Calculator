# Break-Even-Calculator
It calculates if you're Business or Life is going in Profit Or Loss . :)

    import java.util.Scanner;
       public class Main {
        public static void main(String[]args){
         Scanner scanner = new Scanner(System.in);

        String Product ;
        int sales ;
        double marketingBudget ;
        double totalExpense ;
        double sellingPrice ;
        double breakEven ;
        char Dollars = '$';

        System.out.print("Hi , Welcome to a solution to all your financial problems . \nThis tool will help you to calculate as to how much you would have to earn to break even and start earning profit .\nFirst lets start with your Product's Name :");
        Product = scanner.nextLine();

        System.out.print("So the current sales of " + Product + " Is : " );
        sales = scanner.nextInt();

        System.out.print("What is the Monthly marketing budget of " + Product + " : " + Dollars );
        marketingBudget = scanner.nextDouble();

        totalExpense = sales + marketingBudget;

        System.out.print("Thus the Total Expense of Your product is : " + Dollars + totalExpense +"\nNow , Please list the Selling Price of you Product : " + Dollars);
        sellingPrice = scanner.nextDouble();

        breakEven = totalExpense / sellingPrice ;
        System.out.print("From the above information , I can conclude that to break even You would have to reach the average of : " + Dollars + breakEven);





    }
}

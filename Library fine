import java.util.Scanner;
public class Library{
	public static void main(String[] args) {
		Scanner Scanner = new Scanner(System.in);
		int Bookid;
		System.out.print("enter BookID: ");
		Bookid = Scanner.nextInt();
		int Returndate;
		System.out.print("enter Return Date: ");
		Returndate = Scanner.nextInt();
		int Duedate;
		System.out.print("enter Due Date: ");
		Duedate = Scanner.nextInt();
		int Days = Returndate - Duedate;
				double fine;
				float rate;
		System.out.println("Days overdue: "+ Days);
		if(Days>=15) {
			fine = 100;
			rate = 1.0f;
		}
		else if(Days>=8 && Days<15) {
			fine =50;
			rate = 0.5f;
		}
		else{
			fine = 20;
			rate = 0.1f;
		}
		double amount = fine;
		System.out.println("fine amount: " + amount);
		System.out.println("fine rate: " + rate);
	}
}

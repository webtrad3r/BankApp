package javaapplication94;

import java.text.SimpleDateFormat;
import java.util.Date;
import java.util.Scanner;

public class JavaApplication94 {

    public static void main(String[] args) {

        String PersonalFirstName, PersonalLastName, PersonalAddress, PersonalParent;
        String BusinessFirstName, BusinessLastName, BusinessAddress;
        // String[] names1 = new String[4]; 
        int PersonalDOB, PersonalBalance = 0, PersonalWithdraw = 0, PersonalDeposit = 0;
        int BusinessDOB, BusinessBalance = 0, BusinessWithdraw = 0, BusinessDeposit = 0;
        Scanner sc = new Scanner(System.in);
        Date now = new Date();
        //System.out.println("toString(): " +now);
        SimpleDateFormat dateFormat = new SimpleDateFormat("E, y-M-d 'at' h:m:s a z");
        dateFormat = new SimpleDateFormat("dd/MM/yyyy");
        System.out.println("Your DOB: " + dateFormat.format(now));
        System.out.println("**************Personal Account************");
        System.out.println("Enter First Name");
        PersonalFirstName = sc.next();
        System.out.println("Enter Last Name");
        PersonalLastName = sc.next();
        System.out.println("Enter Address");
        PersonalAddress = sc.next();
        System.out.println("Enter Deposit");
        PersonalDeposit = sc.nextInt();
        PersonalBalance = PersonalBalance + PersonalDeposit;
        System.out.println("Enter DOB");
        PersonalDOB = sc.nextInt();
        
        if (PersonalDOB <= 17) {
            System.out.println("Enter parent name");
            PersonalParent = sc.nextLine();       
        } else {
            System.out.println("You deposited " + PersonalDeposit + " and your balance is " + PersonalBalance);
            System.out.println("Enter amount for withdraw");
            PersonalWithdraw = sc.nextInt();
            PersonalBalance = PersonalBalance - PersonalWithdraw;
            System.out.println("You withdrawed " + PersonalWithdraw + " and your new balance is " + PersonalBalance);

        }

    }

}

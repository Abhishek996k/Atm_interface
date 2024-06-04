# Atm_interface
while(true){
    System.out.println("WELCOME TO AUTOMATED TELLER MACHINE");
    System.out.println("CHOOSE 1 FOR CHECKING BALANCE");
     System.out.println("CHOOSE 2 FOR WITHDRAWING MONEY FROM YOUR ACCOUNT");
      System.out.println("CHOOSE 3 FOR DEPOSITING MONEY IN YOUR ACCOUNT");
       System.out.println("CHOOSE 4 FOR EXIT");

   
       
    int choice=sc.nextInt();

       switch(choice){
        case 1:
        checkbalance();
        break;
       
       case 2:
       Withdraw();
       break;

       case 3:
       deposit();
       break;

       case 4:
       exit();
       break;
}

}

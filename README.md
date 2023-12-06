# BANKING_SYSTEM-_IN_CMD.java

This Java-based banking system project offers real-time operations, resembling functionalities found in modern digital banking platforms like YONO. Users can interact with various types of bank accounts such as savings, current, and loan, performing a wide array of real-time operations.

#Features
- Account Operations: Deposit, withdrawal, transfer funds, and change MPIN.
- Security Measures: Account locking, MPIN validation, and security question verification.
- Database Interaction: Uses JDBC to interact with the database for balance updates and MPIN changes.
- File Interaction: Store detaials of each user in file.

#Structures
- App.java - Contains main method and connection to JDBC
- BankingSystem.java - openAccount, CloseAccount , SQL queries
- BankAccount.java -ShowAccount , Deposit, WithDraw, MpinChange , TransactionHistory
- SavingAccount.java - Intialization of class
- CurrentAccount.java - Intialization of class
- Loan.java - Intialization of class, LoanPayInstallments
- Transaction.java - Intialization of class , TransactionHistory
- Utils.java - writeSavings, WriteCurrent, WriteLoan
- Displayable.java - Interface Displayble

#tapproject

This is a simple J2EE project based on the case stury - "Banking Application - Customer Management" for the TCS Technology Appreciation Program.

This project is done by,
  1. Gowtham Raj J (myself)
  2. Ambalavanan M M
  3. Anirudh A

##Case Study
1. Introduction to the Process
2. Process Steps in Detail
3. Problems with a Manual Process
4. Proposed System for Computerization
5. Reports Required
6. Checks and Validations
7. Important Instructions

###1. Introduction to the Process
	Model Bank is in need of a computerized system to manage their, customer details in a
	centralized manner. To ease the management activities the· system must have the
	following facilities.
		* Creation of new account
		* View current balance of the account
		* Fund Transfer between the accounts
		* Calculation of interest amount.

###2. Process Steps in Detail

	2.1 Creation of a new account
	After logging into the user creation module, the following details should be entered
	for creation the new user.
		Account Number :
		Customer Name :
		Customer Address
		Customer City : Customer State :
		Customer Phone:
		Customer Email:
		Customer Zip :
		Date of Birth :
		Type of account (FD/RD/SB):
		Rate of interest :
		Initial Balance :

	Note:
		* The Account number should be generated uniquely and the field should not be an
		editable one.
		* The above mentioned fields are sample fields only. One can add/remove/modify the
		above fields if necessary.
	
	2.2 View current balance of the account
		In the view balance module, admin should be able to view the balance information
		of all the accounts. Admin should be entering either the full account number, or
		full name or part of the customer name. System should be able to provide the
		details based on the input provided.

	2.3. Fund Transfer between the accounts
		In the fund transfer module, the admin should be able to transfer the funds
		between different accounts within the same bank.

	Rules:
		* If the customer withdraws the amou~t directly from the bank, the amount should
			be deducted from the account.
		* lf the customer wishes to transfer the amount to another account(within the same
			bank), then the amount deducted should be deducted and it should be credited
			to the target account.
		* If the target account is not an SB account, then an additional 1 % commission
			should be deducted from the sender account.

	2.4. Calculation of interest amount
		In the interest amount calculation module, the admin should be able to calculate
		the amount of interest( as on the current date), for a particular account.

	Rules:
		* The admin should enter the account number only. System should be able to
		recognize the type of the account and the rate of interest for the particular
		account type.
		* If the account type is FD, it should display the accumulated interest amount
		till the current date.
		* Assume the rate of interest values for the account types(FD/RD/SB). If
		the customer is a senior citizen, then the rate of interest should be little more
		when compared to the non-senior citizens.

###3. Problems with Existing Process
	Problems of the existing system are:
	* Due to more accounts the admin is not able to track all the account details.
	* For customers, fund transfer and withdrawing money are difficult without an
	automated system.

###4. Proposed System for Computerization
	Management has decided to computerize the above-mentioned functions of Cusotmer
	management module of the entire banking system

	Software Requirements:
		FRONT-END: Web based application using J2EE/ASP.net
		BACK-END: Oracle 9i/MYSQL

###5. Reports Required
		5.1. List of fund transfer transactions made within a time frame.
		5.2. List of all failed transactions, along with the reason of the failure.
		5.3. List of cash withdraw made directly from the bank
		5.4. List of all new customer added within a time frame, along with their
		balance and transaction details.

###6. Checks

	Following are a few checks, which one can incorporate, in the computerized solution
	
		* Admin should be logging in with a username and password

		* During Fund transfer I cash withdraw, if there is no sufficient amount left in
		the account, the system should throw an error.

###7. Important Instructions
	* The project is to be developed in the client/server environment and should be
	available on the internet/intranet. If any modifications are to be made or are
	desirable, to the above project description, discuss wit~ your team/your teacher and
	then incorporate these in the project.

	* All inputs/output for the specified processes are to be computerized.

	* The Reports are generated based on the data stored in the tables mentioned below.

	* Design appropriate modules, data fields, records and files required in the
	computerization and program development process. You may prepare your own data,
	wherever necessary.

	* In case if you feel it would be appropriate to add some more functionalites you may
	proceed with it wherever necessary.
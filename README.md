# Credit_Risk


Expected Loss = PD * LGD * EAD


Expected Loss - is the amount a lender might lose by lending to a borrower. It is associated with credit risk.
                Lenders know that there is a certain amount of credit risk associated with every borrower. 
                They expect that there could be a loss when lending to any borrower.

Probability of default (PD) - is the likelihood that a borrower would not be able (or would not be willing) to repay
                              their debt in full or on time. Usually, PD refers to a particular time horizon.

Loss given default (LGD) - is the share of an asset that is lost if a borrower defaults. 
                           It is the proportion of the total exposure that cannot be recovered by the lender 
                           once a default has occurred.

Exposure at default (EAD) - is the total value that a lender is exposed to when a borrower defaults.
                            Therefore, it is the maximum that a bank may lose when a borrower defaults on a loan.
                            
                            
                            
Let’s assume that a borrower wants to buy a house for $500,000. The lender, that is, the bank, funds 80% of the purchase.
This proportion is often referred to as “loan to value”, so we can say that loan to value is 80%.
The loan amount is equal to 80% of $500,000, that is $400,000. 
By now, the borrower has repaid $40,000, so the outstanding balance is $ 360,000.
If the borrower defaults, the exposure at default would, therefore, be $360,000.
Assume that there is empirical evidence that one in four homeowners have defaulted in previous years.
So, probability of default equals 1 divided by 4 which is 25%.
If the borrower defaults, the bank can sell the house immediately for $342,000 meaning, it can recover $ 342,000. 
Then, the remaining loss would be $18,000, and loss given default would be $18,000 / $360,000 = 5%.
If the bank had to calculate its expected loss for that exposure in this very moment, 
it would be, as follows, PD multiplied by LGD multiplied by EAD = 25% multiplied by 5% multiplied by $360,000 = $4,500.                            
                            

For modelling 'Probability of default' two group of variables are used:
- appliaction - related to application which we deal with, so in this case it os loan: loan grade, 
                loan amount, interest rate
- bahavioral - describe person who take the loan: income, age, home ownership, emplyment lenght



![Variables_description](https://github.com/kamilbanas85/Credit_Risk/assets/53495965/ec61d968-3130-4992-ba24-f563809f90e9)

### Project Introduction:


In this project, we will build three models.

  1. **Probability of Default Model:**  (Logistic Regression)
  2. **Loss Given Default Model:**  (Linear Regression)
  3. **Exposure of Default Model:** (Linear Regression)

Utilizing these three models, I aim to compute the overall expected loss (E.L.) for the entire array of loans within the bank's portfolio. Additionally, the final segment delves into the aspects of model maintenance and its deployment for professional applications in the banking domain.

While the real world presents improbable scenarios, such as lenders grappling with unforeseen or extraordinary losses amid severe economic downturns, my project primarily addresses anticipated losses. Specifically, the project concentrates on the expected loss linked to credit risk.

### Expected Losses (EL)/ Expected Credit Loss
Simply, it means the amount a lender might lose by lending to a borrower.

The established credit risk modeling framework defines expected loss as a product of three components: 

                    1. Probability of Default              
                    2. Loss Given Default                      
                    3. Exposure at default

                    EL = PD * LGD * EAD
For the PD Model: We need an indicator of whether the borrower is defaulted or not. (loan status)                                                                                                                                 
For the LGD Model: We will need to calculate how much loan was recovered after the borrower had defaulted. (recoveries column)                                    
For the Exposure at default: We need to calculate the total exposure at the moment the borrower defaulted compared to the total exposure in the past. (Total Recovered Principal Column)                                                  

### Pre-processing

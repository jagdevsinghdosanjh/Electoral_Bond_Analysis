Electoral bonds are interest-free bearer bonds or money instruments that companies and individuals in India can purchase from authorized branches of the State Bank of India (SBI). These bonds are sold in multiples of ₹1,000, ₹10,000, ₹1 lakh, ₹10 lakh, and ₹1 crore. They serve as a means for making anonymous donations to political parties.

Here's how they work:

1. **Purchase**: Individuals and companies can buy electoral bonds through a **KYC-compliant account** at authorized SBI branches.
2. **Donations**: The bonds are used to make donations to a political party.
3. **Anonymity**: The donor's name and other information are not entered on the instrument, ensuring anonymity.
4. **Encashment**: Political parties must encash the bonds within a stipulated time.
5. **No Cap**: There is no limit on the number of electoral bonds a person or company can purchase.

**Who can receive funding via electoral bonds?**
Political parties that secured at least **1% of the votes polled** in recent **Lok Sabha** or **State Assembly elections** and are registered under the **Representation of the People Act, 1951** can receive verified accounts from the **Election Commission of India (ECI)**. The bond amounts are deposited into this account within **15 days** of their purchase. The received donations are then deposited into the **Prime Minister's Relief Fund**.

**Availability and Challenges**:
- Electoral bonds are not available for purchase all the time. They are open for a period of **10 days** in a gap of four months (January, April, July, and October).
- In **Lok Sabha election years**, they are open for **30 days**.
- Challenges to the scheme have been raised in the **Supreme Court**, questioning its constitutionality and impact on Indian democracy.

- For Exploratory Data Analysis, the two files of importance related to Companies who purchased the bonds and the other related to Political Parties who redeemed the bonds can be downloaded from the Election Commission's Website. The link is: https://www.eci.gov.in/disclosure-of-electoral-bonds

- 
- Both these files are in PDF format. I changed these files in CSV format using the Tabula library. The shape (Row, Column) of the Purchaser is (18871, 12), and of the
- Parties are (20421, 9).

- Columns under the name Denominations are in comma-separated format in pdf and generated CSV files. You can replace using string.replace function or can change its data format to numeric using Excel.
-  

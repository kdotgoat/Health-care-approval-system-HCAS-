                                                            HEALTH CARE APPROVAL SYSTEM
The Healthcare Approval System (HCAS) is a Java-based application designed to streamline healthcare approvals.
Instead of rejecting patient treatment requests outright, HCAS intelligently allocates the best possible treatment amount based on the patient's premium category.

The system ensures fair healthcare allocation by:
- Searching available premium covers.
- Matching patients to the most suitable cover.
- Allocating an eligible amount for treatment.
- Managing approvals through a secure database.


Features
- 🏥 Patient Categorization Based on Premium Paid.
- 🔎 Search Algorithm for Cover Matching.
- ✅ Automatic Approval Decision and Amount Allocation.
- 🛡️ Secure Authentication and Database Access.
- 📚 Patient and Cover Record Management.

Technologies Used
- Java (Swing for GUI)
- MySQL (for database)
- JDBC (for Java-MySQL connection)
  
Database Structure
1. patients table – stores patient info (name, premium paid, etc.)
2. covers table – stores different insurance covers and their benefits
3. approvals table – logs approvals with allocated amounts

How It Works:
Patient Requests Treatment
System Searches for Matching Cover based on premium paid.
Approval Decision Algorithm finds the best allocation.
Eligible Treatment Amount is allocated.
Approval is Recorded in the database.

Setup Instructions:
-Java JDK 8 or higher
-MySQL Server
-NetBeans IDE (recommended) or any Java IDE






Verify Account Positions - UiPath Automation
This project automates the process of verifying account positions for clients in the ACME System using UiPath. The automation follows a structured workflow to log into multiple systems, retrieve client account details, compare transactions, and update statuses accordingly.

📌 Features:
Logs into ACME System 1 and System 3.
Accesses dashboards and retrieves client account details.
Searches for clients by Client ID.
Compares account transactions across different systems.
Updates task statuses and adds comments based on the comparison results.
📄 Process Workflow:
Open and log into System 1.
Navigate to the Work Listing section.
Open and log into System 3.
Search for the Client ID and retrieve account details.
Compare transactions from System 1 and System 3.
If the transactions match:
Set the status to Completed.
Add a comment: "Accounts match".
If the transactions don’t match:
Update the task and proceed with account modifications.
Re-evaluate and update the status accordingly.
🔧 Technologies Used:
UiPath (for automation)
Orchestrator (if applicable)
ACME System (for simulation)
🚀 How to Use:
Open UiPath Studio.
Import the project workflow.
Configure ACME System credentials.
Run the automation and monitor results.
Feel free to contribute or suggest improvements! 🚀


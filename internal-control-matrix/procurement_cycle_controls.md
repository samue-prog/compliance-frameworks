# Internal Control Matrix: Procurement to Pay (P2P)

| Control ID | Control Objective | Control Description | Frequency | Owner | Testing Procedure (Forensic Audit) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| P2P-01 | Ensure only valid goods are paid for. | **Three-Way Match:** System matches Purchase Order, Receiving Report, and Vendor Invoice. | Transactional | AP Manager | Inspect a sample of 30 payments; verify all three documents match. |
| P2P-02 | Prevent unauthorized spend. | **Approval Limits:** Purchases over $5,000 require CFO signature. | Transactional | CFO | Review system logs for any POs approved above user limits. |
| P2P-03 | Prevent duplicate payments. | **Duplicate Check:** System prevents entry of an invoice number already in the database. | Automated | IT Systems | Attempt to enter a duplicate invoice number in the test environment. |
| P2P-04 | Ensure Segregation of Duties. | The person who adds a vendor cannot be the person who issues a payment. | Continuous | HR/IT | Review User Access Matrix for conflicting permissions (SOD Analysis). |

**Status:** Active 
**Last Reviewed:** 06/06/2026

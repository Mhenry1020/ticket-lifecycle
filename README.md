<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>



# osTicket Guide: Password Reset Ticket Workflow

## **1. Ticket Submission**
- User submits a ticket with subject **"Password Reset Request"**.
- Required details:
  - Username or email address
  - Affected system (e.g., email, intranet, VPN)
- System auto-generates a confirmation email.

---

## **2. Ticket Assignment**
- osTicket auto-assigns the ticket to the **IT Support Team**.
- Status is set to **"Open"**.
- If flagged as urgent (e.g., account lockout), priority is set to **"High"**.

---

## **3. IT Agent Response**
- Agent reviews the request and sends a response asking for identity verification:
  - Employee ID
  - Last successful login date
  - Security question response (if applicable)
- Ticket status updates to **"Pending User Response"**.

---

## **4. User Verification**
- User provides requested verification details.
- osTicket logs the response and alerts the assigned agent.
- Status updates to **"In Progress"**.

---

## **5. Password Reset & Resolution**
- Agent resets the password and sends temporary credentials.
- Instructions included:
  - First-time login steps
  - Password change requirement
  - Enabling multi-factor authentication (if required)
- Status updates to **"Resolved"**.

---

## **6. Ticket Closure**
- If the user confirms success, the agent **closes** the ticket.
- If no response after 48 hours, osTicket auto-closes the ticket.
- The ticket is archived for compliance and record-keeping.

---

✅ **Password reset completed successfully!**

# 🤖 n8n Job Application Automation (Cold Email Engine)

An end-to-end **automation system built with n8n** to apply for jobs at scale using **personalized cold emails**, while maintaining **email reputation, error handling, and tracking**.

This project simulates how real-world outreach platforms (like Lemlist, Apollo, Instantly) work — but built **from scratch** using automation and logic.

---

## 🚀 Why This Project?

Applying manually to hundreds of jobs is:
- Time-consuming
- Error-prone
- Hard to track

This automation solves that by:
- Sending **controlled, scheduled emails**
- Handling **failures safely**
- Tracking **Sent / Blocked / Pending** states
- Avoiding workflow crashes on invalid emails

---

## 🧠 What This Automation Does

✅ Reads HR contact data from **Google Sheets**  
✅ Sends **job application emails** automatically  
✅ Attaches resume from Google Drive  
✅ Handles SMTP failures without stopping the workflow  
✅ Marks failed emails as **Blocked**  
✅ Adds **rate-limiting** to avoid spam flags  
✅ Runs daily using a **scheduler**  

---

## 📊 Google Sheet Structure

| Column Name | Purpose |
|------------|--------|
| Name | HR Name |
| Email | HR Email |
| Title | Job Title |
| Company | Company Name |
| Status | Pending / Sent / Blocked |
| Sent Date | Timestamp |
| Error Reason | SMTP failure reason (if any) |

---

## 📌 Future Improvements

- Email verification before sending
- AI-generated personalized email content
- Follow-up email automation (Day 5)
- Domain-level auto-blocking
- AWS SES integration for higher volume

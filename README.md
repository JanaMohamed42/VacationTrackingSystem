# 📌 Vacation Tracking System

A web-based system that allows employees to manage their own vacation, sick leave, and personal leave easily and efficiently.

---

## 🌐 Domain: Human Resources (HR)

This system belongs to the Human Resources Management domain, focusing on employee self-service leave tracking and approval.

It aims to:
- Simplify the vacation request process
- Reduce manual workload on HR departments
- Empower employees and managers to manage leave efficiently
- Provide clear communication and transparency through notifications and logs

---

## 🌟 Vision

- Provide employees with a simple way to manage their own vacation, sick leave, and personal leave  
- Reduce the workload of HR and managers  
- Speed up the leave request process  
- Ensure the system is easy to use, intuitive, and accessible  

---

## ✅ Functional Requirements

- Validate leave requests using internal business rules  
- Support optional manager approval  
- Allow employees to:
  - View leave requests from the past 12 months  
  - Submit new leave requests up to 18 months in the future  
- Send email notifications:
  - To managers (for approval)
  - To employees (for status updates)  
- Use existing hardware and software (no new infrastructure)  
- Operate through the company’s intranet portal  
- Support Single Sign-On (SSO) for authentication  
- Maintain logs of all system activity  
- Allow HR/Admin to override requests (with logging)  
- Allow managers to award additional leave time (within system-set limits)  
- Provide a web service interface for internal systems  
- Retrieve employee data from legacy HR systems  

---

## ⚙ Non-Functional Requirements

- Web-based interface accessible via modern browsers  
- Easy and user-friendly UI  
- Secure login and protected data access  
- Scalable to support many users at once  
- Fast and responsive system performance  

---

## 🚫 Constraints

- Employees can only request leave:
  - Up to 18 months in the future  
  - For the past 12 months  
- Approved requests may not be canceled unless system rules allow  
- Manager/HR actions are limited by role and must be logged  
- No new servers or hardware should be required  

---

## 📊 System Diagrams


---

## 👤 Actors

- *Employee:* Requests and manages leave  
- *Manager:* Approves or rejects employee requests  
- *HR Clerk:* Manages employee records and overrides system rejections  
- *System Admin:* Maintains technical resources and system logs  

---

## 🧩 Use Cases Covered

- Submit Vacation Request  
- Edit Pending Request  
- Cancel Approved Request  
- Manager Approval Flow  
- System Email Notification

# event-registration
# 🎉 Event Registration Website (Wix-Based)

This repository documents the development of an **Event Registration Website** created using a **Wix Template** and enhanced with **Velo by Wix** for dynamic functionality.

## 📄 Project Overview

This project enables users to:
- View event details (schedule, location, speakers)
- Register for events using a form
- Receive confirmation after registration
- Manage content dynamically via the Wix dashboard

---

## 🛠️ Technologies Used

### Frontend:
- HTML5, CSS3, JavaScript
- Wix Editor X (with React-like components)
- Wix UI Widgets

### Backend:
- Velo by Wix (Node.js runtime)
- Wix Data Collections (internal database)
- HTTP Functions & Email Integration
- Wix CRM

---

## 📑 Functional Pages

| Page              | Description                                                                 |
|-------------------|-----------------------------------------------------------------------------|
| Home              | Event title, banner, and navigation links                                  |
| About Event       | Description of the event's objectives and goals                            |
| Schedule          | Event timeline with collapsible sessions and dynamic loading               |
| Speakers          | Speaker cards dynamically rendered from Wix database                       |
| Registration      | Form for attendee registration with validation and confirmation            |
| Location/Contact  | Google Map + Contact form (stored in Wix CRM)                              |
| Confirmation      | A success message after form submission                                    |
| Admin Dashboard   | (Optional) View registration data (secured with Velo authentication)       |

---

## 🗃️ Wix Data Collections

- **Registrations**: Name, Email, Phone, Event ID, Timestamp  
- **Speakers**: Name, Designation, Image, Description  
- **Schedules**: Session Title, Time, Description, Speaker Ref  
- **Contacts**: Name, Email, Message, Timestamp  

---

## 🔐 Non-Functional Features

- Responsive on all devices
- Secure with form validation and optional CAPTCHA
- Scalable to support more events and users
- Easy maintainability for admins

---

## 🔮 Future Enhancements

- 💳 Payment Gateway Integration  
- 📲 QR Code for Event Check-in  
- 🔔 Automated Email Reminders  
- 🗓️ Support for Multiple Events  

---

## 🌐 Links

- 📌 **Wix Template Used**: [Event Website Template](https://www.wix.com/website-template/view/html/2376)  
- 📚 **Velo Documentation**: [Velo by Wix Docs](https://www.wix.com/velo)

---


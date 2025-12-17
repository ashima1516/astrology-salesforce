# Astrology Consultation Booking System (Salesforce)
## 📌 Overview
A Salesforce-based astrology consultation booking system built using
Screen Flows and Record-Triggered Flows.

Users submit consultation details through a screen flow.
Automations handle email notifications, status tracking, and dashboards
for astrologers.

## 🎯 Features Implemented
- User Consultation Booking (Screen Flow)
- Duplicate Submission Prevention
- Email Notification on Record Creation
- Status-Based Automation
- Astrologer Dashboard (List Views)
- Consultation Lifecycle Tracking

## 🔄 Automation Details
### Screen Flow
- User input form
- Input validations
- Prevent multiple submissions
- Success confirmation screen

### Record-Triggered Flows
- Send consultation email on creation
- Update Email_Sent__c
- Update Contacted_Date__c when status changes to Contacted
- Handle Consultation Done status
## 📊 Astrologer Dashboard
- List view showing:
  - Upcoming consultations
  - Email Sent = TRUE
  - Status-based filtering

## 🚀 Future Enhancements
- Scheduled reminder email
- Admin notifications
- Experience Cloud portal

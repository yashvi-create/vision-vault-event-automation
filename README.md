# Vision Vault — Event Driven Cloud Automation

A serverless AWS automation project built using Amazon EventBridge Scheduler and Amazon SNS to deliver automated email notifications through an event-driven workflow.

---

## Architecture

```text
Amazon EventBridge Scheduler
            ↓
      Amazon SNS Topic
            ↓
      Email Notification
```

---

## AWS Services Used

- Amazon EventBridge
- Amazon SNS
- IAM

---

## Features

- Event-driven cloud automation
- Scheduled serverless workflow
- Automated email notifications
- SNS email subscription
- AWS Free Tier friendly
- Real-time cloud integration

---

## Workflow

1. EventBridge Scheduler triggers automatically on a fixed schedule.
2. The scheduler publishes a message to an SNS topic.
3. Amazon SNS delivers the notification email.
4. The user receives the automated message.

---

## Project Screenshots

### SNS Topic Configuration
![SNS Topic](/2-sns-topic.png.png)

---

### Email Notification Delivery
![Email Notification](/3-email-notification.png)

---

## Architecture Diagram
![Architecture Diagram](/vision-vault-event-automation.png)

---

## Learning Outcomes

- Event-driven architecture
- AWS cloud automation
- Serverless scheduling
- Notification workflows
- SNS integrations
- AWS infrastructure concepts

---

## Repository Structure

```text
📁 architecture
📁 screenshots
README.md
```

---

## Author

Yashvi Thakar

Cloud • AWS • Networking • Infrastructure • Automation

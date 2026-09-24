# Simulated Phishing Analysis

## 🧪 Scenario

This project analyzes a simulated phishing email designed to imitate a Microsoft 365 account security notification.

The scenario represents a common social engineering technique in which an attacker creates a sense of urgency and attempts to convince the recipient to interact with a fraudulent authentication link.

> ⚠️ This is a simulated security awareness exercise. No real phishing infrastructure, credentials, or malicious links are used.

---

## 📧 Simulated Email

**Subject:** Urgent: Your Microsoft 365 password will expire today

**Sender:** Microsoft 365 Support <support@micr0soft-security.example>

**Message:**

> Your Microsoft 365 password will expire today.
>
> To avoid losing access to your account, please verify your credentials immediately.
>
> Click the link below to keep your account active:
>
> **[Verify your account]**
>
> If you do not complete this verification, your account may be suspended.
>
> Microsoft 365 Security Team

---

## 🔍 Phishing Indicators

### 1. Urgency

The message claims that the password will expire **today** and that the account may be suspended.

Creating urgency is a common social engineering technique intended to reduce the time available for the recipient to evaluate the message carefully.

### 2. Suspicious Sender Address

The sender uses:

`support@micr0soft-security.example`

The domain contains a visually deceptive spelling of "Microsoft" and does not represent an official Microsoft domain.

### 3. Credential Request

The message attempts to convince the recipient to verify their credentials through an email link.

Unexpected requests for passwords or authentication information should be treated with caution.

### 4. Generic Greeting

The message does not identify the recipient by name or provide contextual information about the account.

### 5. Threat of Account Suspension

The statement that the account may be suspended increases pressure on the recipient and encourages immediate action.

### 6. Suspicious Link

The email instructs the recipient to click **"Verify your account"** without providing a legitimate reason to authenticate through the message.

In a real investigation, the destination URL and domain reputation would be examined before interacting with the link.

---

## ⚠️ Risk Assessment

| Indicator | Risk |
|---|---|
| Urgent language | High |
| Suspicious sender domain | High |
| Credential request | High |
| Account suspension threat | Medium |
| Generic message | Medium |
| Unexpected authentication link | High |

The combination of these indicators makes the message highly suspicious and consistent with a phishing attempt.

---

## 🛡️ Recommended Actions

A recipient who receives a message like this should:

1. **Do not click the link.**
2. **Do not provide credentials or authentication codes.**
3. Verify the sender's address and domain.
4. Access the organization's official website or application directly instead of using the email link.
5. Report the message through the organization's established phishing-reporting process.
6. If credentials were already submitted, immediately notify the organization's security or IT team and follow the applicable incident-response procedure.

---

## 🧠 Security Awareness Lessons

This scenario demonstrates several principles of phishing awareness:

- Urgency should not replace verification.
- Sender addresses and domains should be inspected carefully.
- Unexpected credential requests are a major warning sign.
- Links in suspicious messages should not be trusted automatically.
- Security incidents should be reported through established channels.

---

## 📚 Skills Demonstrated

- Phishing detection
- Social engineering analysis
- Risk identification
- Security awareness
- Security documentation
- Basic security analysis

---

## 📌 Conclusion

This simulated exercise demonstrates how multiple small indicators can combine to identify a potentially malicious message.

Rather than relying on a single warning sign, users should evaluate the sender, message content, urgency, requested action, and destination of any links before taking action.

> **Never let urgency replace verification.**

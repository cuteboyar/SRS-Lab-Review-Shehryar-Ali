# Software Requirements Specification (SRS)

## Requirement Review and Improvement

---

### 1. Requirement

Original:
The system should be user-friendly.

Problems:
- Not Clear
- Not Measurable
- Not Testable
- Ambiguous

Improved Requirement:
The system shall allow new users to complete registration within 2 minutes without external assistance.

---

### 2. Requirement

Original:
The system shall store student records safely.

Problems:
- Not Specific
- Not Testable
- Ambiguous

Improved Requirement:
The system shall store student records in an encrypted database using AES-256 encryption.

---

### 3. Requirement

Original:
The system should load quickly.

Problems:
- Not Measurable
- Not Clear
- Not Testable

Improved Requirement:
The system shall load the dashboard page within 3 seconds under normal network conditions.

---

### 4. Requirement

Original:
The system shall allow users to register, login, and manage their profile.

Problems:
- Not Atomic (Multiple requirements combined)

Improved Requirements:
1. The system shall allow users to register using email and password.
2. The system shall allow registered users to log in using valid credentials.
3. The system shall allow users to update their profile information.

---

### 5. Requirement

Original:
The system shall send notifications.

Problems:
- Not Clear
- Not Specific
- Not Complete

Improved Requirement:
The system shall send email notifications to users within 1 minute after successful registration.
# Day 3 – Data Security

## 🎯 Objective
Understand how Salesforce controls access to data at different levels using point-and-click security tools.

---

## 🔐 4 Levels of Data Security in Salesforce

### 1️⃣ Organization Level
- Controls login access
- Password policies
- Login hours
- Login IP ranges

---

### 2️⃣ Object Level Security
Controlled using:
- Profiles
- Permission Sets

Defines:
- Create
- Read
- Edit
- Delete (CRUD)

🧠 Key Point:
- A user can have only ONE profile
- A user can have MULTIPLE permission sets

---

### 3️⃣ Field Level Security (FLS)
- Controls visibility of individual fields
- Fields can be:
  - Hidden
  - Read-only
- Managed through profile or permission set

🧠 Example:
A Sales user can see "Revenue" field but cannot edit it.

---

### 4️⃣ Record Level Security
Controls access to specific records.

Managed using:

#### 🔹 Organization-Wide Defaults (OWD)
- Private
- Public Read Only
- Public Read/Write

OWD sets the baseline access level.

---

#### 🔹 Role Hierarchy
- Users higher in hierarchy inherit access from users below them.

Example:
Manager can see records owned by Sales Rep.

---

#### 🔹 Sharing Rules
- Used to automatically extend record access
- Based on role or public group

---

## 🛠 Practical Work Done
- Modified profile object permissions
- Tested CRUD permissions
- Applied Field-Level Security
- Changed OWD settings
- Created and tested role hierarchy
- Understood sharing rule behavior

---

## 🧠 Key Concepts Learned
- Security works in layers
- Object access must be granted before record access
- Roll-up summary works only in Master-Detail
- OWD defines baseline access
- Profiles control object & field access
- Sharing rules expand record access

---

## 🎯 Outcome
Built strong understanding of Salesforce security architecture including object, field, and record-level access control.

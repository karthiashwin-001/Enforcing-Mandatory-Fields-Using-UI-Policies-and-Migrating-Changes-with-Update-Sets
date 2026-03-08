# 🚀 Enforcing Mandatory Fields Using UI Policies and Migrating Changes with Update Sets

---

## 📌 Project Overview

This project demonstrates how to enforce business rules dynamically in **ServiceNow** using **UI Policies** and how to migrate configuration changes between ServiceNow instances using **Update Sets**.

The main objective of this project is to ensure that the **Priority field becomes mandatory when the Incident State is changed to "In Progress"**. This helps maintain data completeness and improves the efficiency of incident management.

The project also demonstrates how **Update Sets can be used to capture, export, and import configurations** between different ServiceNow instances.

---

## 📝 Project Description

In many ServiceNow implementations, incidents may move through different workflow states without important information being filled in. This can lead to incomplete records and inefficient incident management.

To solve this problem, a **UI Policy** is implemented to dynamically enforce the **Priority field as mandatory** whenever the **State of an incident is set to "In Progress"**.

All configuration changes are captured using an **Update Set**, which allows the configuration to be exported as an **XML file** and imported into another ServiceNow instance. This demonstrates how ServiceNow supports efficient configuration management and migration across environments.

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|--------|
| ServiceNow | Platform used for implementing the project |
| UI Policies | Used to dynamically control form behavior |
| UI Policy Actions | Used to enforce field-level rules |
| Update Sets | Used to track and migrate configuration changes |
| Incident Module | Used for testing the implemented configuration |

---

## 📊 Project Milestones

| Milestone | Task | Status |
|-----------|------|--------|
| Milestone 1 | Create Update Set | ✅ Completed |
| Milestone 2 | Create UI Policy | ✅ Completed |
| Milestone 2 | Verify Update Set | ✅ Completed |
| Milestone 2 | Export Update Set | ✅ Completed |
| Milestone 2 | Import Update Set | ✅ Completed |
| Milestone 3 | Test Incident Module | ✅ Completed |

---

## ⚙ Project Workflow

1️⃣ Create a **Local Update Set** in ServiceNow.  
2️⃣ Set the Update Set as **Current** to track changes.  
3️⃣ Create a **UI Policy** on the Incident table.  
4️⃣ Add a **UI Policy Action** to make the Priority field mandatory.  
5️⃣ Verify that the configuration is captured in the Update Set.  
6️⃣ Export the Update Set as an **XML file**.  
7️⃣ Import the Update Set into another ServiceNow instance.  
8️⃣ Preview and commit the Update Set.  
9️⃣ Test the configuration in the **Incident module**.

---

## 🎯 Expected Result

When the **State of an Incident is changed to "In Progress"**, the **Priority field automatically becomes mandatory**.

The incident cannot be saved without selecting a priority value, ensuring **proper data entry and improved workflow management**.

---

## 🎥 Project Demonstration Video

▶ **Watch the Demo Video**

🔗 [Click here to watch the video](https://drive.google.com/file/d/1yd527Cl7qVqA1BhuOrvi_n7oMrtWiUzG/view?usp=drive_link)

---

## 📸 Project Screenshots

📂 **View All Screenshots**

🔗 [Click here to see screenshots](https://drive.google.com/drive/folders/1HJsYnt8ZFqSpy2rfYk-RTSFT1_gZ7lVb?usp=drive_link)

---

## 👥 Team Members

| Name | Role |
|-----|------|
| 👨‍💼 **Karthikeyan M** | Team Leader |
| 👨‍💻 **Balamurugan KS** | Team Member |
| 👨‍💻 **Dhanush P** | Team Member |
| 👨‍💻 **Mohammed Ismail S** | Team Member |

---

## 📂 Repository Structure

```
ServiceNow-UI-Policy-Project
│
├── README.md
├── Documentation
│   └── Project_Documentation.pdf
├── Screenshots
└── Update_Set_XML
```

---

## 📌 Conclusion

This project successfully demonstrates how **UI Policies can be used to enforce business rules dynamically in ServiceNow without writing scripts**.

By making the **Priority field mandatory when the Incident State changes to "In Progress"**, the system ensures that important information is captured before progressing further in the workflow.

The use of **Update Sets** allows administrators to efficiently track, export, and migrate configuration changes between ServiceNow instances, making **deployment and configuration management more efficient**.

---

## 📜 License

This project is created for **educational purposes**.

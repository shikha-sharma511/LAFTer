# LAFTer
LAFTer Local Area Faculty Tracker: A local area program which informs about every faculty's latest punched in location while maintaining the wall between faculty privacy and student accessibility.


# LAFTer: Local Area Faculty Tracker

A prototype application designed to help students and staff quickly find faculty members and ascertain their availability and location within a university or campus environment.

---

## 💡 Problem Statement

In large academic institutions, it can often be challenging for students and even other faculty members to:
1.  **Locate faculty members:** Knowing where a professor is at a given moment can be difficult, especially if they are not in their usual office.
2.  **Ascertain availability:** Understanding if a faculty member is available for a quick chat, or if they are in a meeting or "Do Not Disturb" mode.
3.  **Access quick contact/office information:** Efficiently retrieving basic details like cabin numbers or contact numbers.

This often leads to wasted time, missed opportunities for interaction, and frustration for both students seeking help and faculty trying to manage their time.

---

## ⏳ Current Progress Status

This repository contains a **functional prototype** of the LAFTer application. The core functionalities are implemented, demonstrating the concept.

**Current Status:**
* **Fully functional front-end application** with two distinct user interfaces: a **Student View** and a **Faculty Portal**.
* **Static faculty data** is embedded within the JavaScript code for demonstration purposes.
* **Basic chatbot logic** for processing natural language queries in the Student View.
* **Faculty controls** for updating their simulated location, presence, location sharing, and "Do Not Disturb" (DND) status.
* **Responsive UI** using Tailwind CSS-like utility classes.

---

## 🧩 How the Prototype Solves the Problem

The LAFTer prototype addresses the problem by providing a dual-interface system:

1.  **Student View:**
    * **Interactive Chatbot:** Students can type natural language questions (e.g., "Where is Dr. Johnson?", "Is Prof. Chen available?", "Contact info for Dr. Rodriguez?") and receive immediate, relevant answers.
    * **Faculty Status Overview:** A dashboard displays the current status (on/off campus, DND, location if shared) of all faculty members at a glance.
    * **Quick Action Buttons:** Pre-defined buttons for common queries like "List all Faculty" or "Who's in Lab A-204?".
    * **Intelligent Responses:** The chatbot understands various query types and respects faculty privacy settings.

2.  **Faculty Portal:**
    * **Self-Service Updates:** Faculty members can easily update their current location, mark themselves as present/absent, toggle location sharing (public/private), and activate/deactivate "Do Not Disturb" mode.
    * **Real-time Status:** Provides immediate feedback on their current published status.

By centralizing and making this information accessible, LAFTer aims to improve communication efficiency and streamline interactions between students/staff and faculty.

---

## 🛠️ Technologies/Tools Used

* **HTML:** For the overall structure and layout of the web application.
* **CSS (Tailwind-inspired):** Styling is applied using utility-first classes, mimicking the approach of Tailwind CSS for a modern, responsive design.
* **JavaScript (Vanilla JS):** All application logic, state management, and DOM manipulation are handled using plain JavaScript.
* **Lucide Icons:** A set of beautiful, open-source icons used throughout the interface to enhance visual clarity.
```

## Screenshots-

https://drive.google.com/drive/folders/1NAlMb65JKIt9K2p3xtJLyheCslsfvz8R?usp=sharing

# Event Tracker App Launch and Development Summary

**Ryan Hatch**  
**CS 360 Mobile Architect & Programming**  
**October 27, 2024**

---

## Requirements and Goals
The Event Tracker app was built to make managing events easy. Users can add, view, and delete events with just a few taps, while receiving timely notifications to stay on top of things. The main goals were to create a smooth, organized experience for tracking events, complete with user authentication, an events database, and support for both notifications and SMS reminders.

### Key Requirements
- **User Authentication:** Secure access to personal events and data.
- **Database Management:** ```CRUD``` operations for reading, adding, editing, and deleting events.
- **Permissions:** Integration for notifications and SMS reminders.

---

## Application Details from Latest Build
- **Application ID:** `com.event.track`
- **Version Code:** 1
- **Version Name:** 1.0
- **APK Variants:**
  - Release Build: `app-release.apk`
  - Debug Build: `app-debug.apk`
- **Supported SDKs:**
  - **Minimum SDK Version:** API level 28 (Android 9.0)
  - **Maximum SDK Version for Dexing:** API level 34 (Android 14)
  - **Baseline Profiles:**
    - <i>API 28-30: Optimized for Android 9 – 11.</i>
    - <i>API 31 and above: Optimized for Android 12 and newer models.</i>

### Supported Android Versions
The Event Tracker app supports Android versions from API level 28 to 34, covering devices from Android 9 through Android 14. Baseline profiles have been implemented separately for versions 28-30 and 31+, optimizing performance for each range. This ensures optimal performance across devices.

---

## Permissions Requested
The app requests only essential permissions to support its core functionality:
- **Send SMS:** Sends event notifications.
- **Receive SMS:** Manages responses for event confirmations.
- **Post Notifications:** Delivers timely event reminders.

<i>Each permission is tailored towards enhancing the user experience (UX) while keeping privacy a priority.</i>

---

## Monetization Plan
The app will follow a **freemium model**:
- **Free Users:** Non-intrusive ads within the interface.
- **Ad-Free Option:** A one-time in-app purchase to remove ads.
- **Premium Features:** One-time purchase unlocks features like recurring events, export options, larger event database management, advanced notifications, and more customization over events, reminders, and users.

---

## User Interface (UI) Design
The UI design tailors towards user-friendly navigation and simplicity:
- **Main Screen:** Guides users to log in or register a new account.
- **Login/Registration Screen:** Simplified authentication for event access.
- **Event Display Screen:** Displays all events in a clean list format with options to add, edit, or delete events.

<i>The Event Tracker's UI/UX is designed for straightforward navigation, keeping things simple and consistent.</i>

---

## Development Approach and Techniques
The development approach for the Event Tracker focused on several strategies:
- **Incremental Development:** Core functions like login and event storage were built, tested, and debugged individually for optimal UX.
- **Modular Code Structure:** Organized with database helper functions for streamlined interactions.
- **Performance Optimization:** Baseline profiles tailored for API levels 28-30 and 31+, ensuring smooth performance across Android models.

<i>This approach improved development efficiency, creating a solid foundation for future additions and functionality across a range of Android models.</i>

---

## Testing and Validation
Testing was conducted to ensure each component in the app performed as expected:
- **Permission Handling:** Verified for smooth functionality without interfering with UX.
- **Database Operations:** CRUD operations were tested for efficiency.
- **Error Handling:** Login validations and permissions denials provide clear and helpful feedback.

<i>The testing phase helped identify edge cases, making the app more stable, reliable, and user-friendly.</i>

---

## Workflow For Overcoming Challenges
One significant challenge was integrating SMS permissions without interrupting UX. A layered permission-checking system was implemented to request permissions only when necessary, resulting in a more optimized workflow.

---

## Demonstrating Knowledge and Skills
Integrating a full database with UI components for managing events demonstrated a solid grasp of Android’s database handling and UI design. This project provided hands-on experience in building a seamless UI and UX that connects users with back-end processes. It offered valuable insight into creating an efficient, natural user experience that balances both interface and behind-the-scenes control.

---

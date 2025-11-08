# DigiParental
KidSafe Monitor is a cross-platform mobile application designed to help parents supervise their children's smartphone activity in real time. It ensures a safe digital environment by notifying parents about unsafe or distracting content and enables them to take immediate action.
-------------------------------------------------------------------------------------------------------------
# Features
- Live Screen Monitoring
- Parents receive live screenshots of the child’s phone screen.
- Instant notifications alert parents to inappropriate or distracting activities.
- Remote Blocking
- Parents can remotely block apps, websites, or activities directly from their phone.
- Screen Activity History
- All past screen activity is saved securely. Parents can review activity logs at any time.
- Smart Notifications
- Detects prolonged usage of distracting apps (e.g., Instagram, YouTube).
- Allows negotiable usage for 10–15 minutes, restricted to once every 3 hours.
- Sends alerts when screen time limits are crossed.
- One-tap pop-up notification to share the child’s device screen in real-time with the parent’s device.
- Secure Onboarding
- Parent identity verification through Aadhaar integration (planned feature).
- Real-time parent photo capture during registration to ensure rightful ownership.
- Cross-Platform Compatibility
-------------------------------------------------------------------------------------------------------------
# Architecture Overview
**Child’s Device (Client App)**
- Captures screen activity periodically (with OS-compliant background process).
- Sends encrypted screenshots and app usage logs to the backend.
- Backend Server
- Processes incoming data.
- Triggers notifications when unsafe activity or excessive screen usage is detected.
- Stores logs securely.
-------------------------------------------------------------------------------------------------------------
**Parents’ Device (Client App)**
- Receives push notifications with screenshots.
- Provides a dashboard for reviewing activity histories.
- Allows remote control actions (block/unblock apps, enforce limits).
-------------------------------------------------------------------------------------------------------------
**Security Layer**
- Aadhaar/KYC verification for parents.
- Biometric/Photo verification to prevent unauthorized access.
-------------------------------------------------------------------------------------------------------------
**Key Use Cases**
- Study Mode Monitoring: Ensure children remain focused on study apps/resources.
- Inappropriate Content Prevention: Block NSFW or distracting apps on the child’s phone.
- Digital Wellbeing: Manage screen time habits effectively.
- Emergency Supervision: Get instant updates if the child tries to access restricted apps or websites.
-------------------------------------------------------------------------------------------------------------
**Future Enhancements**
- AI-powered content recognition from screenshots.
- Time-based device lock/unlock scheduling.
- Location tracking integration for additional safety.
- Detailed reports on the child’s phone usage trends.
- Multi-child supervision dashboard for parents with more than one child.

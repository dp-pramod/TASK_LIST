# O-Health Project Task Tracker

## Pramod

| Task Description | Priority | Status |
|------------------|----------|--------|
| **O-Health Internal Dashboard**<br>Build an internal dashboard to monitor system health and operational activity.<br>Include issue tracking, task assignments, priorities, and status updates. | High | 🔵 In Progress |
| **Migrate SMS Service from Twilio to Fast2SMS**<br>Replace the existing Twilio SMS integration with Fast2SMS.<br>Update the configuration and verify SMS delivery across all relevant workflows. | High | 🔵 In Progress |
| **Instant Question Load After Mic Stops**<br>Redesign the workflow to load the instant question 0.5 seconds after the microphone stops.<br>Handle processing in the background.<br>Deploy and test on DGX & Deploy and test on PROD | High | 🔵 In Progress |
| **DPDP Certification**<br>Upload the required evidence.<br>Make the necessary minor adjustments in the relevant areas, addressing each requirement one by one. | High | ⚪ Yet to Start |
| **Application-Wide Event Logging — Web and Mobile**<br>Implement comprehensive logging across the entire web and mobile applications.<br>Capture every event, including minor interactions, user actions, system events, and errors.<br>Improve log clarity and consistency to simplify debugging and trace events back to their source. | High | ⚪ Yet to Start |
| **Yashoda Integration — Follow-up and Support**<br>Follow up on the Yashoda integration and coordinate pending activities.<br>Provide any support required to resolve issues and complete the integration. | High | 🟣 Ready to Deploy |
| **UI/UX Enhancements — Modern Design**<br>Improve the application's interface with a modern, consistent visual design.<br>Enhance navigation, layouts, and interactions to make the application easier to use. | High | ⚪ Yet to Start |
| **Code and Database Optimization for Scalability**<br>Optimize application code and database queries to improve performance.<br>Support growth in users, tenants, and data volume across deployment environments. | High | ⚪ Yet to Start |
| **Save Original Native-Language Text with Audio Data**<br>Update the audio data saving logic to retain the raw text in the original spoken language.<br>Store this text alongside the corresponding audio data. | High | ⚪ Yet to Start |
| **Automated Code and Database Backups and File Transfers**<br>Automate code and database backups and transfer the backup files to the designated storage location.<br>Verify backup integrity and track transfer success or failure. | High | ⚪ Yet to Start |
| **Enable Voice-Based Consent**<br>Add an option for users to provide consent through a spoken response.<br>Capture and record the voice-based consent against the relevant patient record. | High | ⚪ Yet to Start |
| **Synchronize DGX Development with the Production Replica**<br>Align the DGX development environment with the production replica, including Kafka and all other supporting services.<br>Verify service configurations, dependencies, and connectivity. | High | 🔵 In Progress |
| **Dockerize the Entire Codebase**<br>Containerize all application components and dependencies.<br>Enable easy one-click deployment.<br>Support scalability across deployment environments. | High | 🟠 On Hold |

## Siddanth

| Task Description | Priority | Status |
|------------------|----------|--------|
| **Updated API Integration and End-to-End ABDM Verification**<br>Integrate the newly modified APIs into the application.<br>Verify the complete ABDM workflow end to end and resolve any integration issues. | High | 🔵 In Progress |
| **Fix Vitals Disappearing After Manual Entry — Web and Tauri**<br>Fix the issue where manually entered vitals disappear when navigating to the Patient Information tab.<br>Ensure the entered values are retained in both web and Tauri applications. | High | 🟡 Unit Testing |
| **Vitals Offline Audio Playback — TTS Logic**<br>Implement the missing text-to-speech (TTS) logic for vitals offline audio playback in both web branches and both mobile branches.<br>Ensure the behaviour matches the existing assessment audio logic. | High | ⚪ Yet to Start |
| **Application-Wide Event Logging — Web and Mobile**<br>Implement comprehensive logging across the entire web and mobile applications.<br>Capture every event, including minor interactions, user actions, system events, and errors.<br>Improve log clarity and consistency to simplify debugging and trace events back to their source. | High | ⚪ Yet to Start |
| **Stop Audio When Leaving Assessment or Vitals**<br>Stop all audio playback immediately when the user exits an assessment or leaves the vitals page.<br>Ensure no audio continues or starts playing after leaving either screen. | High | ⚪ Yet to Start |
| **Synchronize Web, Mobile, and Tauri Applications**<br>Align features, workflows, and application behaviour across web, mobile, and Tauri.<br>Ensure updates and fixes are consistently applied across all three platforms. | High | ⚪ Yet to Start |
| **Patient-Side Language Selection Across All Tenants**<br>Add a common language selection option to the patient-facing web and Tauri applications across all tenants.<br>Match the existing mobile language selection behaviour and experience. | High | ⚪ Yet to Start |
| **Offline Audio Sync — Background Downloads and Progress**<br>Enable offline audio files to download and sync in the background.<br>Display download progress in a visible location so users can track the sync status. | High | ⚪ Yet to Start |
| **Reusable Report Display Component — Web, Mobile, and Tauri**<br>Create a reusable component to display reports across web, mobile, and Tauri applications.<br>Ensure consistent report content, formatting, and behaviour across all three platforms. | High | ⚪ Yet to Start |
| **Responsive Layouts Across Devices**<br>Make all screens and pages responsive across mobile phones, tablets, and desktops.<br>Ensure layouts, text, and controls adapt to different screen sizes and orientations. | High | ⚪ Yet to Start |
| **Play Store Deployment and Automatic App Update Pipelines**<br>Configure the mobile application deployment pipeline for the Google Play Store.<br>Set up automatic app update workflows for the Tauri and mobile applications. | High | ⚪ Yet to Start |
| **Improve Vitals UI Animations**<br>Add smooth, intuitive animations to the vitals interface.<br>Improve visual feedback during data entry, loading, and vitals updates. | High | ⚪ Yet to Start |
| **Microphone Usage Guide — 5-Second Animation**<br>Add a small visual guide with a 5-second animation demonstrating how users should position themselves and speak near the microphone. | High | ⚪ Yet to Start |
| **Minimum 3-Second Wait on Consent Page**<br>Keep the Proceed button disabled for at least 3 seconds after the consent page loads.<br>Enable it once the waiting period has elapsed and the required consent has been provided. | High | ⚪ Yet to Start |
| **Offline Audio Sync — Version and Language Status**<br>Display the currently synced audio version on the sync page.<br>Show which languages have synced successfully.<br>Indicate whether the latest version is synced or a newer version is available to download. | High | ⚪ Yet to Start |
| **Fix Intermittent English Fallback in Language Selection**<br>Investigate and fix the issue where the selected primary or secondary language unexpectedly falls back to English.<br>Ensure the selected languages are consistently maintained throughout the application. | High | ⚪ Yet to Start |
| **Standardize Tenant Logo Sizes**<br>Apply consistent logo dimensions and spacing across all tenants.<br>Preserve each logo's aspect ratio and ensure consistent display across screen sizes. | High | ⚪ Yet to Start |
| **End-to-End Issue Documentation and FAQ PDF**<br>Document issues across the complete application workflow, including troubleshooting steps and resolutions.<br>Compile frequently asked questions and publish the documentation as a PDF. | High | ⚪ Yet to Start |

**Priority:** High · Medium · Low

**Status:** 🔵 In Progress · 🟡 Unit Testing · 🟣 Ready to Deploy · ⚪ Yet to Start · 🟠 On Hold · 🟢 Completed

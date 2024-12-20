# Internship-Reviewer-App (INTERNOVA)
This project is a mobile application developed using Flutter, designed to help students review and rate their internship experiences. The app allows users to provide feedback on various aspects of their internships, including company environment, mentorship, and skill development.

# Group Details
### Group Name: Triple-A

|                    Name                   |    Matric Number     |                                          Tasks                                                              |
|-------------------------------------------|----------------------|-------------------------------------------------------------------------------------------------------------|                                 
|      MOHAMAD AIMAN AKIM BIN ADANAN        |       2113823        |             Complete the title, background problem, app compatibility and screen navigation flow            |
|            MUHAMMAD BIN ABAS              |       2113201        |                        Complete the objective, target user, and sequence diagram                            |
|       ARIF MUQRI BIN AHMAD NAZIRI         |       2113825        |             Complete the preferred platform, features/functionalities, and technical feasibility            |


# Case Study 1
## Project Initiation

**1. Title:**
Internship Reviewer Application (INTERNOVA)

**2. Background of the problem**
1) **Unstructured Feedback:** Interns often don’t receive consistent or organized feedback on their performance.
2) **Poor Communication:** Interns lack clear channels to communicate with mentors or supervisors.
3) **Inconsistent Evaluations:** Internship assessments vary widely, leading to unfair evaluations.
4) **Tracking Progress:** It’s difficult for both interns and employers to track progress and achievements during the internship.

**3. Purpose or objective**

**4. Target user**

**5. Preferred platform** <br/>
With Firebase serving as the back-end, Internova will use Flutter for cross-platform development with an eye towards Android. This strategy complies with market trends for affordable, high-performing mobile solutions while guaranteeing accessibility for students and young professionals. It has responsive features like document sharing, progress monitoring, and real-time feedback and is portable.

**6. Features and functionalities** <br/>
*Authentication:*
- User login and registration with Firebase Authentication (supporting email, Google, or social logins).
- Secure authentication flow with email verification and password reset options.

*User Profiles:*
- Profile creation and editing for interns and employers, stored in Firebase Firestore.
- Fields for interns' skills, interests, and past internship experiences; employer-specific details for companies.

*Internship Details and Logs:*
- View detailed internship descriptions, requirements, and mentor details fetched from Firestore.
- A progress log for interns to add daily or weekly updates, with timestamps and supervisor comments.

*Feedback Page:*
- Structured feedback templates for mentors and peers.
- Real-time updates using Firebase Real-time Database or Firestore.
- Option for anonymous feedback submission to encourage honest input.

*Notifications:*
- In-app and push notifications using Firebase Cloud Messaging (FCM) for new feedback, updates on logs, and reminders for document uploads.

*Document Upload and Sharing:*
- Upload resumes, reports, or certificates directly to Firebase Storage.
- Share documents with mentors or employers via in-app links or external sharing options.


## Requirement Analysis

**1. Technical Feasibility/Back-End Assessments** <br/>
*Platform:*
- Flutter: Enables rapid development with reusable widgets, ensuring consistent UI across Android devices.

*Back-end and Infrastructure:*
- Firebase Authentication: Simplifies user login/registration workflows.
- Firebase Firestore: Serves as the primary database for storing user profiles, logs, internship details, and feedback.
- Firebase Storage: Manages document uploads and sharing securely.
- Firebase Cloud Messaging (FCM): Handles push notifications for engagement.

**2. App Compatibility**

**3. Sequence Diagram**

**4. Screen Navigation Flow**

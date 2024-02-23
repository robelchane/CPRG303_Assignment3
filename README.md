# CPRG303_Assignment3
Creating ADR for scenario 2


Architectural Decision Record (ADR) For Scenario 2

Architectural Decision Record (ADR) For Scenario 2
	Native, web, or hybrid app
Context: The application supports multiple platforms for example iOS and Android, the team must pick to develop a native, web, or hybrid app.
Decision: Considering the user, I decided to develop a Native app. 
Rationale: Native was selected to make certain effective maintenance, offline support, and development for both Android and iOS. This decision agrees to reduce development time and effort although having a regular user experience beyond several devices. 
Status: Proposed
Consequences: Choosing a native app may result in enhanced development time and effort, as split codebases will need to be retained for Android and iOS platforms.
	UI Framework
Context: The framework should approach smoothly, be open to change, and be compatible with the selected development approach.
Decision: Considering the user, I decided to develop and use React Native
Rationale: React Native was picked for its capacity to execute native components, Using React Native can reduce the project cost with a single code base. Furthermore, it helps improve productivity and speed up the UI design process. React Native can be deployed on iOS and Android.
Status: Proposed
Consequences: React Native Elements make simpler UI development, but there may be learning documentation who are unaware of the framework.
Backend Language
Context: The backend should be efficient, versatile, and scalability, making it get a better performance of the app.
Decision: Considering the user, I decided to develop and use Node.js
Rationale: Node.js was picked as the backend language because of its non-blocking I/O model, which is suitable for controlling asynchronous duties for instance updating real-time and data synchronization. We can integrate push notifications with Node.js as well for messaging with students and instructors.
Status: Proposed

	Permissions
Context: We need to keep in touch with teachers and students, so we need to communicate via message and get notifications. Also, we need to have some storage to keep our files. In addition, it should be secured to keep our personal info and grades.
Decision: Considering the user, I decided to use message, notification, file storage, and security permission.
Rationale: Messaging should have permission to send and receive messages to students, teachers, and groups message. Also, notifications should have permission to get push notifications for essential updates, for example, new messages, and class announcements. professors should have permissions to manage, share, and upload files within the app. Additionally, using SSL/TLS protocols for the encryption of personal grade and student info.
Status: Proposed
Consequences: Unnecessary permissions and background activities can cause to battery consumption on mobile devices.

	Data Storage
Context: needs to pick a data storage solution for controlling the app's data, with user profiles, schedules, instructor notes, and announcements. 
Decision: decided to use a blend of SQL and NoSQL databases
Rationale: Using a blend of SQL and NoSQL databases was guided by the essentials to manage both structured and unstructured data effectively. SQL databases give relational data managing for structured info for example schedules and user profiles, in contrast, NoSQL databases suggest flexibility for storage of varied data types like assignment deadlines, announcements, and others.
Status: Proposed
Consequences: Operating and retaining both SQL and NoSQL databases at once can be complicated.

	Additional Frameworks or Technology Stacks
Context: need for verification, real-time database, push notifications, and cloud storage.
Decision: decided to use integrate Firebase
Rationale: Firebase was integrated to control its real-time database and verification services. This decision reduces to bare-bones backend development by excluding the necessity, in contrast also providing faultless data synchronization and user verification competencies out of the box.
Status: Proposed
Consequences: Firebase has free access with large usage bounds, higher than these limits free usage can suddenly charge you.


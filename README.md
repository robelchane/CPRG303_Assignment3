# CPRG303_Assignment3
Creating ADR for scenario 2


Architectural Decision Record (ADR) For Scenario 2
Status: Proposed

	Native, web, or hybrid app
Decision: Native app. 
Rationale: Native was selected to make certain effective maintenance, offline support, and development for both Android and iOS. This decision agrees to reduce development time and effort although having a regular user experience beyond several devices. 

	UI Framework
Decision: Use React Native
Rationale: React Native was picked for its capacity to execute native components, Using React Native can reduce the project cost with a single code base. Furthermore, it helps improve productivity and speed up the UI design process.

	Backend Language
Decision: Use Node.js
Rationale: Node.js was picked as the backend language because of its non-blocking I/O model, which is suitable for controlling asynchronous duties for instance updating real-time and data synchronization. We can integrate push notifications with Node.js as well for messaging with students and instructors. We can use FCM for Android and APNs for Apple.

	Permissions
Decision: Apply granular permissions
Rationale: Granular permissions were applied to make sure that users have a suitable approach to data and features based on their functions and benefits surrounded by the university society. Permissions at the application level, privacy, and data security are increased for example using SSL/TLS protocols for the encryption of personal grade and student info. 

 Data Storage
Decision: Use a blend of SQL and NoSQL databases
Rationale: Using a blend of SQL and NoSQL databases was guided by the essentials to manage both structured and unstructured data effectively. SQL databases give relational data managing for structured info for example schedules and user profiles, in contrast, NoSQL databases suggest flexibility for storage of varied data types like assignment deadlines, announcements, and others.

	Additional Frameworks or Technology Stacks
Decision: Integrate Firebase
Rationale: Firebase was integrated to control its real-time database and verification services. This decision reduces to bare-bones backend development by excluding the necessity, in contrast also providing faultless data synchronization and user verification competencies out of the box.

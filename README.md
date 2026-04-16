
Introduction
The SecureCloud Task & Resource Manager (STRM) is a hybrid productivity application designed for field agents who work in areas with unstable internet connections. The goal of this project is to provide a reliable tool where users can log assets locally while offline and synchronize them to a secure cloud database once a connection is available. This ensures that no data is lost during field operations.

The application uses an Offline-First approach. It allows the agent to interact with the UI even without internet, using local persistence strategy.

Frontend: Flutter (Cross-platform)

Local Storage: SharedPreferences (Local Cache for data persistence)

Cloud Database: Google Firebase Firestore (Real-time Sync)

Authentication: Firebase Auth (Anonymous Secure Access)

External Data: RESTful API (JSONPlaceholder)

Conclusion
The development of the SecureCloud Task & Resource Manager (STRM) project successfully demonstrates a reliable "Offline-First" application. Through this project, I learned how to combine local data storage with cloud synchronization to solve real-world problems for field agents.

The main success of this app is its ability to save data even without an internet connection. By using a Local Storage Strategy, agents can log tasks safely on their devices, preventing any data loss. Once the internet is restored, the Cloud Sync feature effectively pushes the logs to the Firebase Firestore database for the central office to see.

Additionally, the use of a RESTful API allows the app to fetch live system updates, while Firebase Authentication ensures that only authorized users can access the system. Overall, this project shows a complete and secure workflow that is essential for modern field operations. It is a stable, professional, and efficient tool that meets all technical requirements.

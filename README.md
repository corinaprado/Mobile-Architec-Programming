# Mobile-Architec-Programming

The application I developed was an Inventory Tracker app designed to help users manage inventory efficiently. The primary goal of the app was to provide a simple system for tracking inventory quantities, updating stock levels, and receiving low-inventory notifications. The application addressed the needs of users who require an organized method for monitoring inventory without relying on manual tracking processes. By including user authentication, inventory management functions, and SMS notifications, the app helped users maintain accurate inventory records and stay informed when stock levels became low.

Screens, Features, and User-Centered Design

Several screens were necessary to support user needs and create a user-centered experience:

Login Screen: Allowed users to create accounts and securely access the application.
Inventory Screen: Displayed inventory items, quantities, and controls for updating or deleting items.
Add Item Screen: Enabled users to quickly add new inventory items and quantities.
SMS Permission Screen Elements: Allowed users to grant or deny notification permissions while still maintaining access to core functionality.

My UI design focused on simplicity and usability. Buttons were clearly labeled, inventory information was displayed in an organized table format, and color-coded action buttons helped users quickly recognize functions such as increasing quantity, decreasing quantity, or deleting items. These design choices made navigation intuitive and supported efficient task completion.

Development Process and Strategies

I approached development by breaking the project into smaller, manageable tasks. Rather than attempting to build the entire application at once, I implemented one feature at a time and tested it before moving forward.

My development process included:

Designing the user interface.
Creating the SQLite database and tables.
Implementing user account creation and login validation.
Developing inventory CRUD functionality.
Adding RecyclerView support for displaying inventory records.
Implementing SMS permission handling and notifications.

This step-by-step strategy helped reduce errors and made debugging easier. In future projects, I plan to continue using incremental development because it improves organization and allows issues to be identified early.

Testing and Validation

Testing was an essential part of development. After implementing each feature, I tested it in the Android emulator to verify functionality. I also used Logcat and Android Studio debugging tools to identify and resolve errors.

Testing included:

Account creation and login validation
Database storage and retrieval
Adding inventory items
Updating inventory quantities
Deleting inventory records
SMS permission approval and denial scenarios
Navigation between application screens

This process revealed several issues, including layout errors, missing resource references, database connection problems, and RecyclerView configuration mistakes. Identifying these issues early prevented larger problems later in development and improved the overall reliability of the application.

Challenges and Innovation

One of the biggest challenges was transitioning from static inventory data to a dynamic RecyclerView that displayed database records. Initially, inventory items were displayed using hard-coded values and plain text. To improve usability, I redesigned the inventory display to load data directly from SQLite and present it within a table-like RecyclerView layout.

Another challenge involved handling user authentication and database interactions while maintaining a smooth user experience. Through troubleshooting and experimentation, I learned how to organize database operations and UI updates more effectively.

Area of Greatest Success

The component I was most successful with was the integration of the SQLite database with the user interface. I successfully created tables, stored user information, managed inventory records, and displayed data dynamically through a RecyclerView. Implementing CRUD functionality demonstrated my understanding of database management, mobile application architecture, and user-focused design principles.

Overall, this project strengthened my skills in Android development, database integration, debugging, and user-centered application design. It also provided valuable experience in following a complete software development lifecycle from planning and design through implementation, testing, and launch preparation.

### **Android component model**

Defines how Android apps are built and interact with each other using specific building blocks, known as *components*, each designed to handle different functions of an app.
Different componets :


| **Component**          | **Purpose**                                           | **Example**                                                       |
|------------------------|-------------------------------------------------------|-------------------------------------------------------------------|
| **Activities**          | Represents a single screen for user interaction.     | A photo gallery app with different screens like the main view and photo editor. |
| **Services**            | Runs background tasks without user interface.        | A music player continuing to play music when switching to another app. |
| **Broadcast Receivers** | Listens for system-wide messages to trigger actions.  | Reacting to a “battery low” notification by dimming the screen or saving progress. |
| **Content Providers**   | Manages and shares structured data between apps.     | The Contacts app sharing contact data with messaging or email apps. |



#### **Important Concepts in the Android Component Model**

* **Intent**: This is a messaging object that lets components communicate.  
* **Lifecycle**: Each component has a specific lifecycle, which means they go through stages like “created,” “started,” “paused,” and “destroyed.”

### Managing Applications Data 

| **Storage Type**         | **Description**                                          | **Advantages**                        | **Disadvantages**                      | **Best For**                                      |
|--------------------------|----------------------------------------------------------|---------------------------------------|----------------------------------------|--------------------------------------------------|
| **Internal Storage**      | Stores data privately on the device’s internal memory.   | Secure, private to the app.           | Limited storage space.                 | Sensitive data that needs privacy.               |
| **SD Cards**              | Uses SD card for additional storage.                     | Expands storage for large files.      | Not secure, not all devices support it. | Large files like images or videos.               |
| **SQLite Databases**      | Structured data storage using relational model.         | Efficient for structured data.        | Requires SQL knowledge.                | Complex or related data, like user info.         |
| **Shared Preferences**    | Stores small data as key-value pairs.                    | Easy to use, persists across sessions.| Limited to basic data types.           | Small data like settings or preferences.         |
| **Web Storage**           | Stores data remotely on web servers or cloud.           | Unlimited storage, syncs across devices. | Needs a network connection.            | Data shared across devices or users.             |

## **UI**

### **User Interface (UI) Design in Android**

UI design in Android means creating the screens and interactive elements of an app that users see on their devices.

### **Key UI Components**

* **Main Action Bar (MAR)**: The main bar where users can navigate and access key options.  
* **Split Action Bar (SAB)**: An additional action bar, useful on larger screens, for extra options.  
* **Content Area**: The main area of the screen where the core content of the app is displayed.

### **Views and ViewGroups**

* **Views**: These are the basic elements you see in an app, such as buttons, checkboxes, and text fields. They respond to user actions like clicks and touches.  
* **ViewGroups**: These are containers that hold other Views or ViewGroups. They help organize and structure the UI by grouping different elements together in layouts.

### **Layouts in Android**

Layouts define how elements are arranged on the screen. In Android, layouts are commonly specified using XML (a markup language), which is simple to use and allows easy control over element positioning and organization.

**Advantages of Using XML Layouts**:

* **Popular Format**
* **Separation of Concerns**: Keeps the UI design separate from the app’s logic, making it easy to change one without affecting the other.  
* **Easy to Use**

#### **Types of Layouts**

1. **Linear Layout**  
2. **Frame Layout**: Serves as a simple container, usually for displaying a single view or element.  
3. **Relative Layout**: Allows elements to be positioned relative to each other.  
4. **Table Layout**  
5. **Constraint Layout**: A flexible layout that lets you position and scale elements based on specific rules or constraints.




















## Moblie Testing

- **Importance of Mobile:** Mobile devices play a crucial role in daily life.
- **User Preference:** Most users prefer accessing websites and apps on phones over computers for small tasks.
- **QA Responsibility:** Quality Assurance engineers must ensure application quality on mobile devices.
- **Mobile Testing:** Essential for testing apps across all possible devices to maintain quality.
- **What is Mobile App Testing?** Checking apps and websites on different mobile devices to ensure they work well.
- **Why is it Done?** To improve the app’s quality.
- **Trends:** Many companies using modern DevOps are building apps with microservices for better performance.  

### Types Of Applications

| **Type**                  | **Description**                                                                                                                | **Examples**                          |  
|---------------------------|--------------------------------------------------------------------------------------------------------------------------------|---------------------------------------|  
| **Native Applications**   | Built specifically for a platform (iOS, Android) using platform-specific languages.                                            | WhatsApp, Instagram                   |  
| **Web Applications**      | Accessed through a browser, require internet connectivity, and are not installed on devices.                                   | Gmail (web), Google Docs (web)        |  
| **Progressive Web Apps**  | Apps that can be installed directly using links without visiting an app store, offering offline access and push notifications. | Flipkart Lite, Starbucks PWA          |  
| **Hybrid Applications**   | Combine web technologies (HTML, CSS, JavaScript) and native capabilities for cross-platform use.                               | Uber, Twitter|  

### Type of Mobile Application Testing

| **Type of Mobile Application Testing** | **Description**                                                                               |  
|----------------------------------------|-----------------------------------------------------------------------------------------------|  
| **Functional Testing**                 | Checks if the app's functionality works as per requirements across various mobile devices.    |  
| **Compatibility Testing**              | Ensures the app works on different devices, OS, browsers, and networks.                       |  
| **Usability Testing**                  | Evaluates the app's user-friendliness and fixes user experience issues.                       |  
| **Performance Testing**                | Tests the app’s performance under varying loads and stress levels.                            |  
| **Security Testing**                   | Verifies the app's protection against security flaws and vulnerabilities.                     |  
| **Interrupt Testing**                  | Checks how the app behaves during interruptions like calls, notifications, or battery changes.|  
| **Installation Testing**               | Tests if the app installs and uninstalls correctly without issues.                            |  


| **Key Factors Influencing Mobile App Testing**| **Description**                                                                                                   |  
|-----------------------------------------------|-------------------------------------------------------------------------------------------------------------------|  
| **Mobile Devices**                            | Testing the app on various devices with different resolutions, browsers, OS, and hardware is crucial.             |  
| **Mobile Simulators**                         | Simulators mimic the behavior of actual devices, allowing cost-effective testing on different devices.            |  
| **Network Conditions**                        | Testing the app under various network conditions (2G, 3G, 4G) ensures it performs well in different environments. |

### Processes of Mobile Application Testing
1. **Outlining the Process:** Plan testing activities, select devices, and prepare a compatibility matrix.
2. **Identify Testing Type:** Choose the appropriate testing type based on the app.
3. **Test Cases Design:** Create manual and automated test cases for all features.
4. **Manual and Automation Testing:** Execute both manual and automated tests to find issues.
5. **Usability and Beta Testing:** Test the app's user-friendliness with in-house and beta testers.
6. **Performance Testing:** Evaluate app performance and scalability.
7. **Complete Testing and Closure:** Final testing and regression testing before sign-off.

**Final Report:** Includes bug count, types of testing, and compatibility matrix.


### Best Tools for Mobile Application Testing
1. **Appium**  
   - Open-source tool for automating both Android and iOS apps  
   - Supports Java, Ruby, Python, C#  
   - Integrates with Continuous Integration/Development tools
2. **Robotium**  
   - Open-source tool for automating Android apps  
   - Supports Java  
   - Integrates with Maven and Ant
3. **Selendroid**  
   - Open-source tool for testing web, native, and hybrid Android apps  
   - Uses Selenium for scripting  
   - Supports Java, C#, Perl  
   - Features object recognition for enhanced testing

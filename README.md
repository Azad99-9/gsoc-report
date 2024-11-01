# Google Summer of Code 2024 Final Report

---

### Project Title: *Offline Capability Enhancement - Talawa Mobile*

**Organization**: *The Palisadoes Foundation*  
**Mentor**: *Md Noman Khan, Jason Odoom*  

---

## Problem Statement

- **Initial Limitations**:
  - Talawa previously lacked robust offline handling capabilities.
  - The app did not have an efficient caching system, leading to limited functionality without a stable network connection.
  - Without the internet, Talawa behaved inconsistently, displaying loading indicators across screens and allowing no other actions.
  - If launched offline, the application was barely usable, and some situations even led to app crashes.

- **Primary Goals**:
  - Strengthen Talawa’s offline support to handle offline scenarios gracefully.
  - Introduce an efficient caching mechanism to the mobile application.    
---

## Proposed Enhancements

- **Make Talawa Offline Support Robust**:
  - Introduce functionality in the application to handle user offline actions.
  - Facilitate users with the most recently cached data, allowing them to use the app as usual when offline.
  - Cache offline user actions performed by the users and update the application’s user interface to reflect these changes, providing a seamless and reliable experience.
  - Sync all cached user actions with the API one by one in the background as soon as the application is back online, notifying the user of the status of their offline actions.
  - Achieve parity with other social media apps, making Talawa usable and reliable even in offline situations.

- **Introduce an Efficient Caching Mechanism**:
  - Implement an efficient caching mechanism essential for data-intensive applications like social media apps.
  - Improve Talawa’s responsiveness by incorporating this caching mechanism.
  - Utilize a caching approach similar to popular social media apps like Instagram, where caching occurs frequently every time the application fetches the latest data from the API.
  - Cache new data locally on the device, ensuring that the cache database holds the latest fetched data at all times.
  - Populate the application’s user interface with cached data upon opening the application, while fetching the latest data from the API in the background.
  - Allow users to continue with cached data if the application is offline; if online, refresh the user interface with the latest data.


## Achievements & Goals
Throughout the GSoC period, I achieved the following:

- **Goal 1**: *[Briefly describe goal and accomplishment, e.g., implementing a specific feature, optimizing a service, etc.]*.
- **Goal 2**: *[Another main goal and its achievement]*.
- **Goal 3**: *[Another main goal and its achievement]*.

Each milestone contributed to building a more *[adjective describing impact on project, e.g., robust, user-friendly, scalable]* application, successfully enhancing *[mention specific improvements in user experience, performance, etc.]*.

## Future Enhancements
The project opens the door for further enhancements, such as:

- **[Enhancement 1]**: *[Briefly describe potential future improvement]*.
- **[Enhancement 2]**: *[Another possible enhancement]*.

These enhancements could further boost *[mention aspects like usability, efficiency, or adaptability]*.

## Reflection on GSoC Experience
My GSoC journey has been deeply rewarding. Working with *[Organization's Name]* provided valuable insights into *[mention key learning areas: open-source contribution, advanced development practices, teamwork, etc.]*. This experience strengthened my skills in *[mention relevant skills: coding, project management, communication, etc.]* and solidified my commitment to contributing to open source.

---

Thank you to my mentor and the entire community for their support and guidance throughout this journey!

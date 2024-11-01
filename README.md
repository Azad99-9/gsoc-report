# Google Summer of Code 2024 Final Report
---
### About Me

**Name**: *Shaik Mahammad Nabi Azad*

**Git-Hub**: *[Azad99-9](https://github.com/Azad99-9)*

**Linkedin**: *[Shaik Azad](https://www.linkedin.com/in/shaik-azad-4505b7240/)*

---

### Project

**Project**: *[Offline Capability Enhancement - Talawa Mobile](https://summerofcode.withgoogle.com/programs/2024/projects/UztycmP4)*
**Mentor**: *[@noman2002](https://github.com/noman2002)*
**Repository**: *[Talawa](https://github.com/PalisadoesFoundation/talawa)*
**Organization**: *[The Palisadoes Foundation](https://github.com/PalisadoesFoundation)*  

---

## Problem Statement

- **Initial Limitations**:
  - Talawa previously lacked robust offline handling capabilities.
  - The app did not have an efficient caching system, leading to limited functionality and a lack of a stable network connection.
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
---

## Code

- **Issues**: [link](https://github.com/PalisadoesFoundation/talawa/issues?q=is%3Aissue+is%3Aclosed+author%3AAzad99-9)
- **Pull Requests**: [link](https://github.com/PalisadoesFoundation/talawa/pulls?q=is%3Apr+is%3Aclosed+author%3AAzad99-9)

## Documentation

For detailed documentation of my work, please visit the following links:

- **Offline Actions Feature**: [Documentation Link](https://docs.talawa.io/docs/developers/talawa/offline-first-features/offline-user-actions)
- **ActionHandlerService**: [Documentation Link](https://docs.talawa.io/docs/developers/talawa/offline-first-features/action-handler-service)
- **Feed Caching**: [Documentation Link](https://docs.talawa.io/docs/developers/talawa/offline-first-features/feed-caching)
  
## Reflection on GSoC Experience
1. Participating in GSoC has been a transformative journey that has significantly enhanced my professional and technical skills. The experience challenged me to elevate my abilities and pushed me to think critically about problem-solving.
2. I had the incredible opportunity to collaborate with inspiring mentors who guided me through the intricacies of open-source development. Their expertise and insights were invaluable in shaping my understanding of best practices and innovative approaches.
3. The open-source community has not only been a catalyst for my personal growth but also allowed me to contribute meaningfully to a project that aligns with my passions. Engaging with this collaborative environment has deepened my appreciation for teamwork and the power of shared knowledge.

Thank you to my mentor and the entire community for their support and guidance throughout this journey!


---


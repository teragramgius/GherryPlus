# INFORMATION DESIGN

Based on the app's focus on remembering through images and maps places and people for the elderly, and providing support for caregivers through Giada AI, the following system diagram can be proposed:
       
       
       +-----------------------+
       |    User Interfaces    |
       | (for caregivers, for  |
       |        elders)        |
       +-----------+-----------+
                   |
                   |
            +------+------+   +-------------------+
            | Application  |   |    External       |
            |    Server    +---+    Systems        |
            +------+------+   +--------+----------+
                   |                   |
                   |                   |
      +------------+------------+      |
      | User Management Services|      |
      +------------+------------+      |
                   |                   |
      +------------+------------+      |
      | Data Processing Services|      |
      +------------+------------+      |
                   |                   |
      +------------+------------+      |
      |  Database Servers       |      |
      +-------------------------+      |
                                       |
      +------------------------------+ |
      |         Cloud Storage        | |
      +------------------------------+ |
                                       |
      +------------------------------+ |
      |     Image Recognition API    | |
      +------------------------------+ |
                                       |
      +------------------------------+ |
      |   Mapping & Geolocation API  | |
      +------------------------------+ |
                                       |
      +------------------------------+ |
      |    Giada AI Integration      | |
      +------------------------------+ |

      
## Explanation:

- User Interfaces: This component represents the user interfaces of the app, including separate interfaces for caregivers and elders. These interfaces allow users to interact with the app, access various features, and receive information and support.
- Application Server: The application server serves as the core component of the system. It handles the processing and logic of the application, coordinating interactions between different components.
- User Management Services: This component manages user authentication, registration, and profile management. It ensures that caregivers and elders can securely access and personalize their app experience.
- Data Processing Services: This component handles data processing tasks, including image recognition, mapping and geolocation services, and integration with Giada AI. It processes and analyzes data to provide personalized recommendations and support to caregivers and elders.
- Database Servers: The database servers store and manage the app's data, including user profiles, memory-related information, images, and caregiver support resources.
- External Systems: This component represents external systems that the app may integrate with, such as cloud storage for image and data storage, image recognition APIs for identifying people and objects, mapping and geolocation APIs for location-based features, and Giada AI integration for personalized support and assistance.



# NAVIGATION BETWEEN THE SECTIONS

To facilitate navigation between sections in the app, there is a clear and intuitive user interface.
1. Menu/Navigation Bar: Include a menu or navigation bar that remains visible throughout the app, providing easy access to different sections. It is on top of the screen, allowing users to quickly switch between sections.
2. Iconography and Visual Cues: Using icons and visual cues to represent each section and aid in recognition, they are visual indicators of the content or functionality associated with each section, making it easier for users to identify and select the desired section.
3. Clear Labels and Descriptions: Clear and concise labels are provided for each section to convey its purpose. Additionally, consider adding brief descriptions or tooltips that provide additional context when users hover over or tap on a section, helping them understand the content or functionality offered in that section.
4. Search Functionality: A search feature allows users to search for specific content or sections within the app. This can be particularly helpful when the app has a large amount of content or when users are looking for specific information.
5. Search Functionality: Implement a search feature that allows users to search for specific content or sections within the app. This can be particularly helpful when the app has a large amount of content or when users are looking for specific information.
6. Back and Home Buttons: Include back and home buttons or icons that allow users to easily navigate back to the previous screen or return to the app's home screen. This provides a familiar navigation pattern and helps users maintain their orientation within the app.

# BLUEPRINTS
## Blueprint 1: Login/Register Page
- User Type Selection: Two checkboxes allowing the user to identify themselves as either a caregiver or an elderly individual.
- Registration Form: Fields for entering first name, last name, password, and password confirmation.
- Sign-Up Button: After filling out the form, users can submit their information to create an account.
- Login options: Two buttons to login, as a caregiver or as an elderly person.

# WIREFRAMES
For each subsection (profile page, activities, community chat)
The more we go in depth the better it is

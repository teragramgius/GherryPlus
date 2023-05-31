### INFORMATION ARCHITECTURE

We first identify the main components our system is going to be made
of, we characterize and describe these components, and only then we describe the
grouping of these components into broader sections.

# SECTIONS

# SYSTEM DIAGRAM

# SEARCH AIDS
CAO=S design model
The CAO=S (Context, Activities, Objects, and Structure) model is a user-centered design framework that helps designers understand and plan the various elements of an interactive system. Based on the CAO=S design model, let's identify the concepts, actors, and operations for your application, aimed at caregivers and elderly people with memory loss problems.

# Concepts:
Information entities managed by the system from the user point of view (ex. YOGA, EVENTS, terminology... ) EXPAND
Personal profiles: Information about the elderly individuals and their caregivers, including contact details, medical history, and preferences Reminders: Scheduled alerts for medication, appointments, and daily activities Memory exercises: Interactive activities or games designed to improve cognitive function Social connections: Features that facilitate communication and interaction between users, such as messaging or video calls Resource library: Educational materials and resources for caregivers and elderly individuals, such as articles, videos, and support group information Actors:

Direct actors: - End users: Caregivers (family and professional) and elderly individuals with memory loss problems

Indirect actors: - Healthcare professionals: Doctors, nurses, and therapists providing guidance and care to elderly individuals and their caregivers - Support network: Family members, friends, and community members who may be involved in the care of elderly individuals - App developers and administrators: The team responsible for designing, developing, and maintaining the application Operations:

Create: Add new information, such as personal profiles, reminders, or social connections Read (view): Access existing information, such as personal profiles, reminders, memory exercises, social connections, or resources

Update (edit): Modify existing information, such as updating personal profiles, rescheduling reminders, or managing social connections

Delete: Remove information, such as deleting personal profiles, reminders, or social connections

# CRUD Matrix:

Based on the concepts and operations, you can create a CRUD matrix to identify the individual operations performed by each direct actor on each concept: | Actor/Concept | Personal Profiles || Reminders | Memory Exercises || Social Connections | Resource Library | | --------------------------| ------------------||----------------|| ----------------||--------------------|------------------| | Family Caregivers |C, R, U, D ||C, R, U, D ||R || C, R, U, D | R | Professional Caregivers | C, R, U, D ||C, R, U, D ||R |C, R, U, D |R

| Elderly Individuals |

By identifying the concepts, actors, and operations based on the CAO=S model, you can better understand the interactions between the different components of your application and design a more effective system that meets the needs of your users.

Providing search aids: To enhance the user experience and make it easier for users to find relevant content within the app, you can implement several search aids. Here are some suggestions:

Search bar: Include a search bar prominently in the app's interface, allowing users to enter keywords or phrases to find specific content.

Autocomplete: Implement an autocomplete feature that suggests search terms based on user input, helping users find content more quickly and accurately.

Filter and sort options: Allow users to filter search results based on criteria like date, relevance, category, or content type. Additionally, provide options to sort results, such as alphabetically, by date, or by popularity.

Faceted search: Implement a faceted search system that enables users to narrow down search results by selecting multiple filters simultaneously, such as categories, tags, or content types.

Search suggestions: Offer search suggestions based on popular searches or trending topics within the app to help users discover new content.

Advanced search: Provide an advanced search option for users who want to perform more complex searches using multiple keywords, phrases, or filters.

Search analytics: Analyze search data to identify frequently searched terms or common user queries, and use this information to improve content organization, search functionality, and overall user experience.

# Context

Elderly individuals with memory loss problems and their caregivers (both family members and professionals) are the primary users. Users may access the app on various devices, such as smartphones, tablets, or computers. The app may be used in different environments, including homes, assisted living facilities, or healthcare centers.

# Activities

Managing medications, including scheduling, reminders, and tracking adherence
Engaging in cognitive exercises to help improve memory and cognitive function
Participating in social connections through support groups, forums, and messaging
Accessing resources, such as educational materials, expert advice, and external links
Customizing the app's interface, content, and settings based on individual preferences and needs
Objects

Medication schedules, reminders, and history
Cognitive exercise content, such as games, quizzes, or puzzles
Support groups, forums, and messaging platforms
Educational materials, expert advice, and resource links
User profiles, settings, and personalized content
Structure

Home: Overview of app features and quick access to main sections
Medication Management: Medication list, schedule, reminders, and history
Cognitive Exercises: Memory games, personalized recommendations, and progress tracking
Social Connection: Support groups, forums, direct messaging, and local events
Resources: Educational materials, expert advice, and external resources
Personal Section: User profile, settings, customization options, personalized content, and progress tracking

# Operations
Based on the CRUD model: 
Create Read (view) Update (edit) Delete for each concept(previously defined).
Individual operations performed by individual actors on individual concepts are discovered hrough a table, representing, for each actor, the Cartesian product between the operation types and the concepts. Our only actor is the end user, so we only need to provide one table. 

# COMS W3132 Individual Project

## Author
Kevin Lian
kl3451@columbia.edu

## Project Title
**Soccer Talent Identifier: Leveraging Machine Learning for Optimal Player-Team Fit**

## Project Description
The Soccer Talent Identifier project leverages machine learning to match soccer players with teams where they are most likely to excel. Motivated by the growing complexity and competitive nature of sports analytics, as well as a huge personal passion for the sport, this project seeks to solve the challenge of identifying optimal player-team fits using data-driven insights. By analyzing detailed player statistics from fbref, we aim to develop predictive models that can recommend player signings based on a team's strategic needs and playing style.

Although most high-level soccer teams already have detailed databases for player scouting, these databases are highly confidential. This project seeks to make player scouting and knowledge more accessible to everyday fans and make fans more informed about players and clubs. The main goals for the semester include successfully scraping and processing player data from fbref, developing and testing machine learning models for player-team matching, and creating a user-friendly interface for accessing these insights.

The project holds significant utility and interest for soccer clubs, scouts, and analytics enthusiasts, offering a novel tool for data-informed decision-making in player acquisition and team development. By harnessing the power of machine learning, the Soccer Talent Identifier promises to bring a new level of precision to the art of building winning teams.

## Timeline

*To track progress on the project, we will use the following intermediate milestones for your overall project. Each milestone will be marked with a tag in the git repository, and we will check progress and provide feedback at key milestones.*

| Date               | Milestone                                                                                              | Deliverables                | Git tag    |
|--------------------|--------------------------------------------------------------------------------------------------------|-----------------------------|------------|
| **March&nbsp;29**  | Submit project description                                                                             | README.md                   | proposal   |
| **April&nbsp;5**   | Update project scope/direction based on instructor/TA feedback                                         | README.md                   | approved   |
| **April&nbsp;12**  | Basic project structure with empty functions/classes (incomplete implementation), architecture diagram | Source code, comments, docs | milestone1 |
| **April&nbsp;19**  | Progress on implementation (data successfully mined and into a usable format)                          | Source code, unit tests     | milestone2 |
| **April&nbsp;26**  | Completely (or partially) finished implementation                                                      | Source code, documentation  | milestone3 |
| **May&nbsp;10**    | Final touches (conclusion, documentation, testing, etc.)                                               | Conclusion (README.md)      | conclusion |

*The column Deliverables lists deliverable suggestions, but you can choose your own, depending on the type of your project.*

## Requirements, Features and User Stories

**Feature 1: Data Scraping**

User Story: As a data scientist, I need to automatically extract player statistics and historical performance data from fbref.com, so I can analyze and utilize up-to-date data without manual intervention.

Scenario: The system schedules daily scraping tasks that pull the latest player statistics from fbref.com, ensuring that the dataset is always current and reflects the most recent games.

**Feature 2: Data Preprocessing**

User Story: As a developer, I need tools to clean and preprocess the raw data, transforming it into a structured format, ready for analysis and model training.

Scenario: Once data is scraped, it undergoes preprocessing to remove inconsistencies, handle missing values, and convert text data into numerical values that can be used in machine learning models.

**Feature 3: Player Performance Prediction Model**

User Story: As a team strategist, I want to use historical data to predict future performance of players, so I can make informed decisions about potential signings.

Scenario: A team strategist inputs desired player characteristics, and the system provides predictions and insights on how well players matching these characteristics are expected to perform in the upcoming season.

**Feature 4: Player-Team Fit Analysis**

User Story: As a soccer club scout, I need a tool that can suggest players who fit our team’s style and needs, optimizing our recruitment strategy.

Scenario: The scout specifies the team’s playing style and needs using the system interface. The system then analyzes available players and suggests those whose past performance and skills best match the criteria.

**Feature 5: Interactive Dashboard**

User Story: As a coach, I need an interactive dashboard to visualize player statistics and model outputs, helping me to easily understand data-driven insights.

Scenario: The coach logs into the dashboard to view a visual representation of data on player performance trends, predictions, and recommended signings, with options to drill down into specific aspects like defensive skills or goal scoring.

**Requirements**

_Hardware:_

Computer with high processing power and at least 16GB of RAM to handle large datasets and run complex machine learning models efficiently.

_Software:_

Python 3.11: The core programming language for the project.

Beautiful Soup: For scraping data from web pages.

Pandas and NumPy: For data manipulation and numerical analysis.

Scikit-learn: For implementing machine learning models.

Matplotlib: For data visualization.

_Online Services:_

GitHub: For version control and collaboration.

fbref.com: As the primary data source.

## Technical Specification
*Detail the main algorithms, libraries, and technologies you plan to use. Explain your choice of technology and how it supports your project goals.*

## System or Software Architecture Diagram
![SoccerProject](https://github.com/coms-w3132/final-project-kevinlian2it/assets/52785160/72c01a40-8f64-47ee-8a0d-2ec747b1f6da)


## Development Methodology
*Describe the methodology you'll use to organize and progress your work.*

*First, describe your plan for developing your project. This might include how (or if) you plan to use*
- *GitHub projects board to track progress on tasks and milestones*
- *GitHub issues to keep track of issues or problems*
- *Separate Git branches and/or GitHub pull requests for development*
- *GitHub actions for automated testing or deployment pipelines*
- *GitHub wiki for documentation and notes*

*Please also describe how (if) you plan test and evaluate your project's functionality. Do you plan to test manually or automatically? Any specific testing frameworks or libraries you plan to use?*

## Potential Challenges and Roadblocks
*Identify any potential challenges or roadblocks you anticipate facing during the development of your project. For each challenge, propose strategies or solutions you might use to overcome them, which may include getting help from the TAs/instructor. This could include technical hurdles or learning new technologies.*

## Additional Resources
*Include any additional resources, tutorials, or documentation that will be helpful for this project.*

## Conclusion and Future Work
*Wrap up your project description with any final thoughts, expectations, or goals not covered in the sections above. Also briefly discuss potential future work, i.e., what could be done next to improve the project.*

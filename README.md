# BasketTeamManagement

Student project for the Software Technology course of the Department of Computer Engineering and Informatics at the University of Patras.
The following students collaborated in completing the project alphabetically: Andreas Zafeiropoulos, Nikolaos Lenis, Panagiotis Marakos, Georgios Bisas, Evangelia Potamianou.
The purpose of the project is for each student to experience all phases of software development in practice and to collaborate in teams.

A significant part of the UI was implemented with satisfactory functionality.

-The class TrainingScheduleGenerator was not implemented.

-In the class TeamMembership, redirection to an external payment system was not implemented; instead, a corresponding message is displayed. Additionally, the class is not functional as it is not connected to the other functionalities, nor is the user's chosen license properly secured.

-The class SetTeamStandards creates a team_standard object each time the user enters all data into the application and chooses to save the standard, saving it to a file. The presentation of the saved data has not been implemented, and data validation checks have not been implemented either.

-In the class PlayerGameAnalysis, a preloaded video is loaded, and there are video player capabilities, but it is not functional as neither the extraction of snapshots nor their merging has been implemented.

-The class ManagePlayersInformation creates a player_info object each time the user enters all player characteristics into the application. However, data validation checks have not been implemented, and the presentation of saved players is missing.

-The class ManageExercise creates a training_exercise object and saves it to a file. A system file, category.txt, has been implemented, containing exercise categories for user selection before saving. Messages for importing and saving videos are displayed, but they are not functional.

-In the class GameAnalysis, a preloaded video is loaded, and all video player capabilities are available, but it is not functional as it does not support designing and saving to a table.

-The class ManageTeamSchedule creates a match object with the date and difficulty of the match and saves it to a file. Upon selecting app settings, a corresponding message is displayed. A day off object is created and saved to the appropriate file. Significant dates are displayed in the presentation of saved data.

-In the class ManageTeamMembers, the user enters a username, and the system locates it in the corresponding file. If the name does not exist in the file, an error message is displayed. In case a role is not selected, an error message is displayed. Upon adding a member to the license, relevant files are displayed. For deleting a member from the license, the corresponding line is selected, and a deletion message is displayed.

-In the class MatchStatistics, the user selects a player from a file (no connection to the ManagePlayersInformation class has been made), enters the player's statistics, and creates a match_stats object for the selected player. Connection to the corresponding match has not been implemented. Upon export, a corresponding message is displayed without initiating the retrieval process.

-In the class TrainingStatistics, a training exercise and player are selected from respective files, a value for performing the exercise (without validation) is entered, and a training_info object is created and saved to a file. Upon export, a corresponding message is displayed without initiating the retrieval process.

-In the class TrainingImpact, a time period is selected, a player is chosen, and the player's statistics are displayed (no connection to Match Statistics has been implemented). Upon selecting to display the charts, a success message is displayed, and a chart object is created without being presented in a diagram. Upon export, a corresponding message is displayed without initiating the retrieval process.

Management of the application at the user level has not been implemented. The construction of the application was based on creating independent pieces of code rather than as a whole application. None of the function classes have implemented file export for retrieval, modification, or deletion of saved data, as the latter was mentioned in previous deliverables. Additionally, the classes contain methods not implemented in the class diagram, as they relate to the interface and not the backend part of the application. There are no methods in the class diagram related to saving an object to a file since, in the actual implementation of the application, data is stored in a database.

# Social Network Recommendations
This project implements basic recommendations for a social network system, providing users with friend suggestions and page recommendations based on their connections and liked pages.
📂 Project Structure:
load_data(filename) - Loads JSON data from a specified file.
display_data(data) - Displays users, their connections (friends), and liked pages.
cleanit(data) - Cleans and processes the dataset by removing users with no names, ensuring unique friends, identifying active users, and ensuring unique pages.
people_you_may_know(user_id, data) - Suggests friends of friends for a given user.
page_u_may_like(user_id, data) - Recommends pages that the user may like based on mutual liked pages with other users

🚀 How to Run the Code
Clone or download this repository.
Ensure you have Python 3.x installed on your system.
Place your JSON file (e.g., massive.json or data.json) in the same directory.
Run the code by executing the following command(bash):
python <script_name>.py

🧑‍🤝‍🧑 Key Functions
1. Load Data
This function loads JSON data from a file.

def load_data(filename):
    with open(filename, "r") as f:
        data = json.load(f)
    return data
2. Display Data
This function displays all users, their friends, and their liked pages.

def display_data(data):
    # Code for displaying data
3. Clean Data
Cleans and processes the dataset by removing inactive users, ensuring unique friends and pages.

def cleanit(data):
    # Code for cleaning data
4. Friend Suggestions (People You May Know)
Recommends friends of friends based on a given user's connections.

def people_you_may_know(user_id, data):
    # Code for friend suggestions
5. Page Suggestions (Pages You May Like)
Suggests pages a user may like based on mutual likes with other users.

def page_u_may_like(user_id, data):
    # Code for page suggestions

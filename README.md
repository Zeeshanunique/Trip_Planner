

# Trip Planner CrewAi

## Overview

Trip Planner Crew is a Python program designed to help users plan their trips efficiently. It utilizes a crew of agents and tasks to assist users in creating personalized itineraries based on their preferences.

## Installation

1. Install Python (if not already installed): [Python Installation Guide](https://www.python.org/downloads/)
2. Install required packages using pip:
   ```
   pip install crewai python-dotenv
   ```

## Usage

1. Clone this repository to your local machine.
2. Navigate to the directory containing the cloned repository.
3. Create a `.env` file in the root directory and provide necessary environment variables (if required).
4. Run the script `trip_planner.py`.

   ```
   python trip_planner.py
   ```

5. Follow the prompts to input your trip details:
   - Origin (departure location)
   - Cities you're interested in visiting
   - Date range for your trip
   - Your interests and hobbies

6. After providing the required information, the program will generate a trip plan for you.

## Customization

- **Agents**: Agents are individuals or entities responsible for specific tasks within the trip planning process. You can define custom agents in the `agents.py` file.
- **Tasks**: Tasks represent specific actions performed by agents. You can define custom tasks in the `tasks.py` file.

## File Structure

- `trip_planner.py`: Main script to run the trip planning process.
- `agents.py`: Contains definitions for custom agents.
- `tasks.py`: Contains definitions for custom tasks.
- `.env`: Environment variables file (if required).

## Contributing

Contributions to enhance the functionality or add new features are welcome. Feel free to submit pull requests or open issues for any improvements or bug fixes.

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to adjust the README as needed, including adding any additional sections or information pertinent to your project.

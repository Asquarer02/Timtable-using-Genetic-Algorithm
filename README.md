# University Timetable Generator using Genetic Algorithm

## Overview
This project implements a timetable generation system for university courses using a genetic algorithm. It efficiently creates schedules while adhering to various constraints, optimizing for factors such as professor availability, room capacity, and course timing preferences.

## Features
- Automated generation of university course timetables
- Consideration of multiple constraints:
  - Professor availability
  - Room capacity and type (classroom/lab)
  - Course timing preferences
  - Section-specific requirements
- Genetic algorithm implementation for optimization
- Conflict resolution for overlapping schedules
- Printable timetable output

## Technologies Used
- Python 3.x
- PrettyTable library for formatted output

## Installation
1. Ensure you have Python 3.x installed on your system.
2. Clone this repository:
   ```
   git clone https://github.com/your-username/timetable-generator-genetic-algorithm.git
   ```
3. Navigate to the project directory:
   ```
   cd timetable-generator-genetic-algorithm
   ```
4. Install required dependencies:
   ```
   pip install prettytable
   ```

## Usage
1. Run the main script:
   ```
   python timetable_generator.py
   ```
2. The program will generate a timetable based on the predefined constraints and courses.
3. The best timetable will be displayed in the console.

## How It Works
1. **Initial Population Generation**: Creates a set of random timetables.
2. **Fitness Evaluation**: Assesses each timetable for conflicts and constraint violations.
3. **Selection**: Chooses the best timetables for reproduction.
4. **Crossover**: Combines features from two parent timetables.
5. **Mutation**: Introduces random changes to maintain diversity.
6. **Iteration**: Repeats the process until a satisfactory timetable is found.

## Customization
You can customize the timetable generation by modifying the following in the `timetable_generator.py` file:
- `courses`: Add or modify course details
- `sections`: Adjust section information
- `professors`: Update professor availability
- `rooms`: Change room capacities and types
- Constraints: Modify the fitness function to add or adjust constraints

## Future Improvements
- GUI for easier input of courses, professors, and rooms
- Export functionality for generated timetables (e.g., CSV, PDF)
- Integration with university management systems
- Performance optimization for larger datasets

## Contributing
Contributions to improve the timetable generator are welcome. Please feel free to submit a pull request or open an issue for discussion.

## Contact
Ahmed Abd-ur-Rahman - i210404@nu.edu.pk

Project Link: [https://github.com/Asquarer02/Timtable-using-Genetic-Algorithm](https://github.com/Asquarer02/Timtable-using-Genetic-Algorithm)

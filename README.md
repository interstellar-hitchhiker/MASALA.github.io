# MASALA.github.io
MASALA: IBDP Exam Scheduler
https://interstellar-hitchhiker.github.io/MASALA/
# MASALA: IBDP Exam Scheduler

Welcome to the MASALA: IBDP Exam Scheduler! This tool is designed to help you efficiently schedule and manage your IBDP exams. The scheduler enables you to create a detailed exam schedule, including exam durations, reading times, start times, and accommodations. The schedule can be displayed in a finalized web view or exported to an Excel file for easy sharing, printing, and record-keeping.

## Features

- **Dynamic Exam Schedule Generation**: Enter the number of exams and the tool generates a customizable schedule table.
- **Time Calculations**: Automatically calculates reading periods, 30-minute warnings, 5-minute warnings, and end times based on input durations and start times.
- **Accommodation Adjustments**: Includes functionality to add extra time for students with special needs.
- **Export to Excel**: Download the finalized exam schedule as an Excel file.
- **Live Time Updates**: Displays a live clock and highlights schedule cells based on the current time.

## Potential Changes and Enhancements

- **Color Scheme Update**: Improve the visual appeal by using complementary colors for cell highlighting.
- **Sound Notifications**: Add beep noises to indicate start and end times, and when there are 30 minutes or 5 minutes remaining.
- **Text-to-Speech Announcements**: Implement text-to-speech functionality to announce exam details and time warnings. This feature could be complex when multiple exams are running simultaneously, as it would need to read aloud the exam subject, paper, and levels for each exam. However, this feature is worth exploring.

## How to Use

1. **Set Exam Date**: Select the date for the exams.
2. **Enter Number of Exams**: Specify how many exams are being scheduled for the selected date.
3. **Generate Schedule**: Click on "Create Schedule Table" to generate the schedule table.
4. **Fill in Exam Details**:
   - Enter the subject for each exam.
   - Specify the duration (hours and minutes) for each exam.
   - Allocate reading time if applicable.
   - Set the start time for each exam.
5. **View and Export Schedule**:
   - Click on "Download to Excel" to export the schedule to an Excel file.
   - Click on "Finalized Table Web View" to see a finalized view of the schedule with live updates.

## GitHub Pages Site

You can view and interact with the MASALA: IBDP Exam Scheduler directly here: https://interstellar-hitchhiker.github.io/MASALA/

## Installation

To set up the MASALA: IBDP Exam Scheduler locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/<your-username>/<your-repository>.git
    ```

2. Navigate to the project directory:
    ```bash
    cd <your-repository>
    ```

3. Open `index.html` in your web browser to start using the scheduler.

## Technologies Used

- **HTML**: Structure of the scheduler.
- **CSS**: Styling for a user-friendly interface.
- **JavaScript**: Functionality and interactivity.
- **Bootstrap**: Responsive design framework.
- **Moment.js**: Time manipulation and formatting.
- **SheetJS (xlsx)**: Exporting the schedule to Excel.

## Contributing

We welcome contributions to improve the MASALA: IBDP Exam Scheduler. To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Commit your changes (`git commit -am 'Add a new feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

Special thanks to all contributors and users who provide valuable feedback to help improve this tool.

---

For any questions or support, please open an issue in the repository.

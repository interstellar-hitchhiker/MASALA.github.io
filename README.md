# MASALA.github.io
Exam Schedule Creator and Display 
https://interstellar-hitchhiker.github.io/MASALA/

# Exam Scheduler and Display

Welcome to the Exam Scheduler and Display. This tool is designed to help you efficiently schedule and manage your IBDP exams. The scheduler enables you to create a detailed exam schedule, including exam durations, reading times, start times, and accommodations. The schedule can be displayed in a finalized web view or exported to an Excel file for easy sharing, printing, and record-keeping.

## Features

- **Dynamic Exam Schedule Generation**: Enter the number of exams and the tool generates a customizable schedule table.
- **Time Calculations**: Automatically calculates reading periods, 30-minute warnings, 5-minute warnings, and end times based on input durations and start times.
- **Accommodation Adjustments**: Includes functionality to add extra time for students with special needs.
- **Export to Excel**: Download the finalized exam schedule as an Excel file.
- **Live Time Updates**: Displays a live clock and highlights schedule cells based on the current time.
- **Save and Load Schedule**: Save the current schedule to a JSON file and load a saved schedule from a JSON file.
- **Responsive Design**: Ensures usability across different devices and screen sizes.

## How to Use

1. **Set Exam Date**: Select the date for the exams.
2. **Enter Number of Exams**: Specify how many exams are being scheduled for the selected date.
3. **Generate Schedule**: Click on "Create Schedule Table" to generate the schedule table.
4. **Fill in Exam Details**:
   - Enter the subject for each exam.
   - Specify the duration (hours and minutes) for each exam.
   - Allocate reading time if applicable.
   - Set the start time for each exam.
   - When using accommodations, the accommodation percentage is not displayed; only the finalized end time is shown. The 30- and 5-minute warnings apply to the original exam times, with the accommodation time added at the end. This setup assumes that special needs and non-special needs students are sharing the same room, with the 30- and 5-minute warnings communicated orally to the individual with accommodations. If special needs students use a separate room, create a single column for each student and each exam, entering the specific percentage needed for each student (e.g., English B P1 (Smith) and Chemistry P3 SL (Kim)). This allows individuals to see the original exam durations and times, as well as their updated end time based on their accommodation. Future iterations could update this section to reorder the static column rows so accommodations are above the start time, and automatically update the 30-minute, 5-minute, and end times based on the accommodation percentage.
5. **View and Export Schedule**:
   - Click on "Export to Excel" to export the schedule to an Excel file.
   - Click on "Finalized Table Web View" to see a finalized view of the schedule with live updates.
   - Click on "Save Schedule" to keep an offline .json version of the completed table with subject names and time details to load and display at a later date.
   - Click on "Load Schedule" to upload a saved .json file and display the exam(s) with subject names and time details already to go.

## GitHub Pages Site

You can view and interact with the MASALA: IBDP Exam Scheduler directly here: [https://interstellar-hitchhiker.github.io/MASALA/](https://interstellar-hitchhiker.github.io/MASALA/)

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
- **Flatpickr**: Date and time picker.
- **SheetJS (xlsx)**: Exporting the schedule to Excel.
- **FileSaver.js**: Saving schedules as JSON files.
- **jsPDF**: Generating PDF files.

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

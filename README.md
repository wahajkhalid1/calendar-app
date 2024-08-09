# CalendarApp

CalendarApp is an Angular application designed to help users manage their appointments effectively through a calendar interface. This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.2.

## Project Scope

The CalendarApp allows users to:

- Create, edit, and delete appointments.
- View appointments in a calendar format.
- Drag and drop appointments within the calendar to reschedule them.
- Navigate between different months to view past and future appointments.

### How It Works

- **Appointment Form**: Users can fill out a form to create or edit appointments, specifying details such as title, date, start time, and end time.
- **Calendar View**: The main calendar view displays all the appointments for the selected month. Users can see a visual representation of their schedule.
- **Drag and Drop**: Appointments can be dragged and dropped to different days to quickly reschedule them.
- **Small Calendar Component**: A smaller calendar component allows users to quickly navigate to a specific date.

### Current Limitations

- **Horizontal Scrolling**: There are occasional issues with horizontal scrolling due to layout overflows.
- **Browser Compatibility**: Full functionality is currently optimized and tested on Google Chrome only.
- **Offline Capability**: The application does not support offline usage, since there is no persistent storage.

### Future Improvements

- **Responsive Design**: Improve the responsive design to ensure compatibility across all devices and screen sizes.
- **Browser Compatibility**: Ensure full functionality across all major browsers.
- **Notifications**: Add reminder notifications for upcoming appointments.
- **Recurring Appointments**: Allow users to create and manage recurring appointments.

## Development Server

1. **Ensure Node.js and npm are installed**:

   - For macOS, you can install Node.js and npm via Homebrew:
     ```sh
     brew install node
     ```
   - For Linux, you can install Node.js and npm via apt-get:
     ```sh
     sudo apt-get update
     sudo apt-get install nodejs npm
     ```

2. **Ensure Angular CLI is installed**:

   ```sh
   npm install -g @angular/cli

   ```

3. **Get up and running**:
   - To start the development server,
   ```
    run ng serve
    Navigate to http://localhost:4200/.
   ```
   The application will automatically reload if you change any of the source files.

## Build

To build the project, run `ng build`. The build artifacts will be stored in the `dist/` directory. Use `ng build --prod` for a production build.

## Running Unit Tests

To execute the unit tests, run `ng test`. This will ensure that all unit tests pass and the application behaves as expected. Unit tests are executed via [Karma](https://karma-runner.github.io).

## Running End-to-End Tests

To execute end-to-end tests, run `ng e2e`. Make sure to first add a package that implements end-to-end testing capabilities, such as Protractor or Cypress.

## Further Help

For additional help on Angular CLI, use `ng help` or visit the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

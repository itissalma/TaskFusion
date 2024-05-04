# TaskFusion

The only task manager you will need for Linux.

## Functional Requirements

- The application will be GUI-based and targeting Ubuntu systems. We are targeting new Linux users that might not be familiar with how the terminal operates and their commands.
- The application will be built in Rust in order to ease the backend development, attaining the necessary data, and executing the determined processes. 
- The application will have three main capabilities: 
  - General resource allocation viewing
  - Process management
  - System information viewing
- The resource allocation view shows how much of the CPU, memory, and storage is used.
- The process management view will show all the running processes and allow the user to end them.
- The system information view will display basic system information, namely, model information and distribution.
- The process manager should allow users to filter the process list by process name, user, PID, or other criteria to quickly locate specific processes.
- Color coordinate system outlining the severity of each process.
- Allow the user to change process priority.

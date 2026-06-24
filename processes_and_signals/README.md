# Processes and Signals

- **0-what-is-my-pid**: Displays its own PID
- **1-list_your_processes**: Displays all running processes in a user-oriented format with hierarchy
- **2-show_your_bash_pid**: Displays lines containing the word bash to find the Bash PID
- **3-show_your_bash_pid_made_easy**: Displays the PID and name of bash processes without using ps
- **4-to_infinity_and_beyond**: Displays "To infinity and beyond" indefinitely
- **5-dont_stop_me_now**: Stops the 4-to_infinity_and_beyond process using kill
- **6-stop_me_if_you_can**: Stops the 4-to_infinity_and_beyond process without kill or killall
- **7-highlander**: Runs indefinitely and is immune to SIGTERM
- **67-stop_me_if_you_can**: Tries to stop the 7-highlander process without kill or killall
- **8-beheaded_process**: Kills the 7-highlander process for good
- **10-process_and_pid_file**: Creates a PID file and handles termination signals
- **11-manage_my_process**: Init script that starts, stops, or restarts the manage_my_process daemon
- **manage_my_process**: Daemon script that writes "I am alive!" to /tmp/my_process indefinitely

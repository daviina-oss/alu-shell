# Processes and signals

Bash scripts about processes and signals.
- ⁠ 1-list_your_processes ⁠: displays all running processes in a hierarchy.
- `2-show_your_bash_pid`: displays the lines of the process list containing bash.
- `2-show_your_bash_pid`: displays the lines of the process list containing bash.
- `3-show_your_bash_pid_made_easy`: displays the PID and name of processes containing bash.
- `3-show_your_bash_pid_made_easy`: displays the PID and name of processes containing bash.
- `4-to_infinity_and_beyond`: displays "To infinity and beyond" indefinitely, with a `sleep 2` between each iteration.
- `5-dont_stop_me_now`: stops the 4-to_infinity_and_beyond process using kill.
- `6-stop_me_if_you_can`: stops the 4-to_infinity_and_beyond process without kill or killall.
- `10-process_and_pid_file`: creates `/var/run/myscript.pid`, displays "To infinity and beyond" indefinitely and handles SIGTERM, SIGINT and SIGQUIT.
- `manage_my_process`: indefinitely writes "I am alive!" to `/tmp/my_process`, pausing 2 seconds between messages.
- `11-manage_my_process`: init script that manages `manage_my_process` with `start`, `stop` and `restart`, using the PID file `/var/run/my_process.pid`.

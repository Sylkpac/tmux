## tmux: A Powerful Multi-Pane Terminal 

**Description:** Tmux is a multi-pane terminal that allows you to manage multiple terminal sessions within a single window. It's a valuable tool for cybersecurity professionals due to its features such as detaching and reattaching sessions, creating multiple windows and panes, enhanced security, increased productivity, and collaboration capabilities.

**Installation:**

* **Linux:** Use your package manager (e.g., sudo apt install tmux)

* **macOS:** Use Homebrew (brew install tmux)
  
* **Windows:** Use Windows Linux Subsytem (WSL) 

**Getting Started:**

* Launch tmux: 'tmux'
* Navigate between panes and windows using arrow keys and 'Ctrl+b' combinations.
* Create new windows and panes using 'Ctrl+b' followed by appropriate commands.
* Commands found here: https://tmuxcheatsheet.com/

### Key Features:

* <b>Detach and reattach sessions</b>   
  - Detach from a session: 'Ctrl+b d'     
  - List sessions: 'tmux ls'     
  - Reattach to a session: 'tmux attach-session -t 0' (assuming session 0 is listed).

* **Create multiple windows and panes**
  - Start a new tmux session: 'tmux'
  - Create a new window for a different task: Press 'Ctrl + b' then 'c'
  - In the new window, split the screen horizontally to run two commands simultaneously: Press 'Ctrl + b' then '%'
  - Now split the first pane vertically to create even more workspace: Press 'Ctrl + b' then '"'
  - Navigate between the panes and windows using:   
      Next Window: 'Ctrl + b' then 'n'   
      Previous Window: 'Ctrl + b' then 'p'   
      Pane Navigation: 'Ctrl + b' then use arrow keys
      
* Enhanced security (session locking, password protection)
  - To lock your tmux session, use the following key combination: 'Ctrl + b' then 'x'  
*This will lock the session and prompt for a password to unlock it
  - To unlock a locked session, simply press 'Enter' and you will be prompted to enter your password.
  - To enhance security, set a lock command by executing: ' tmux set-option -g lock-command "gnome-screensaver-command -l" '
  - Press 'Ctrl + b' then 'l' to lock the terminal. You will need to enter your password again to unlock.

* Change layouts and shortcuts
  
  - Split the Pane Horizontally: Press 'Ctrl + b' then '%' to split the current pane horizontally.
  - Split the Pane Vertically: Press 'Ctrl + b' then ' " ' to split the current pane vertically.
  - Change the Layout: Press 'Ctrl + b' then 'space' to cycle through layouts until you find one you like.

**Additional Resources:**

* Video Tutorial:      
https://www.youtube.com/watch?v=nTqu6w2wc68&t=249s   
https://www.youtube.com/watch?v=DzNmUNvnB04&t=227s   
* Refer to the tmux manual for more detailed instructions:  
https://github.com/tmux/tmux/wiki/

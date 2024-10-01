## tmux: A Powerful Multi-Pane Terminal 

**Description:** Tmux is a multi-pane terminal that allows you to manage multiple terminal sessions within a single window. It's a valuable tool for cybersecurity professionals due to its features such as detaching and reattaching sessions, creating multiple windows and panes, enhanced security, increased productivity, and collaboration capabilities.

### Key Features:

* <b>Detach and reattach sessions</b>   
  - Detach from a session: 'Ctrl+b d'     
  - List sessions: 'tmux ls'     
  - Reattach to a session: 'tmux attach-session -t 0' (assuming session 0 is listed).  

* Create multiple windows and panes 

* Enhanced security (session locking, password protection)

* Customizable layouts and shortcuts

* Share sessions with colleagues


**Installation:**

* **Linux:** Use your package manager (e.g., sudo apt install tmux)

* **macOS:** Use Homebrew (brew install tmux)
  
* **Windows:** Use a terminal emulator like Git Bash or Windows Terminal 

**Getting Started:**

* Launch tmux: 'tmux'
* Navigate between panes and windows using arrow keys and 'Ctrl+b' combinations.
* Create new windows and panes using 'Ctrl+b' followed by appropriate commands.
* Commands found here: https://tmuxcheatsheet.com/ 

**Additional Resources:**

* Video Tutorial:   
https://www.youtube.com/watch?v=nTqu6w2wc68&t=249s
https://www.youtube.com/watch?v=DzNmUNvnB04&t=227s
* Refer to the tmux manual for more detailed instructions: https://github.com/tmux/tmux/wiki/

**Example Use Case:**
* Managing multiple SSH sessions: Use tmux to keep multiple SSH connections open and organized in different panes.
VIDEO
* Running long-running tasks: Detach from a tmux session to continue running tasks even if your terminal connection is lost
VIDEO

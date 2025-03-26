# OS
Advanced Disk Scheduling Simulator

Live Demo: [Try It Here](https://rai-kriti.github.io/OS/)

Overview
 The Advanced Disk Scheduling Simulator is a web-based tool designed to visualize and compare different disk scheduling algorithms. It helps users understand how 
 disk scheduling impacts system performance by simulating disk head movements, response times, and seek times in real-time.

-->Features
 Supports Multiple Disk Scheduling Algorithms
 First Come First Serve (FCFS) – Requests are processed in the order they arrive.
 Shortest Seek Time First (SSTF) – The request closest to the current head position is served first.
 SCAN (Elevator Algorithm) – Moves in one direction, then reverses at the end.
 C-SCAN (Circular SCAN) – Moves in one direction and jumps back to the beginning without servicing in reverse.

-->Interactive Simulation
 Enter custom disk request queues and initial head position.
 Visual representation of disk head movement using Chart.js.
 Dynamic performance metrics: Total Seek Time, Average Seek Time, System Throughput.

-->User-Friendly Interface
 Built with HTML, CSS (TailwindCSS), and JavaScript.
 Clean UI with interactive buttons for algorithm selection.

-->Technologies Used
 HTML, CSS (Tailwind CSS), JavaScript
 Chart.js for graphical visualization
 GitHub Pages (Optional: To host the project)

-->Future Enhancements
 Adding more scheduling algorithms: LOOK, C-LOOK, F-SCAN
 Customizable disk size and head movement constraints
 Backend integration for persistent data storage and analytics

Contributors
👨‍💻 Kriti, Nitesh, Pranav


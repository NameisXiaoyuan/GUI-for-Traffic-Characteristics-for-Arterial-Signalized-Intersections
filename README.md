# GUI-for-Traffic-Characteristics-for-Arterial-Signalized-Intersections
a simple GUI to calculate and plot the traffic signal characteristics for one-way or two-way intersections


This project works on designing a simple software to calculate and plot the traffic signal characteristics in python. The idea of the project is to save the repetitive work on cycle length design and drawing flow-density curves and state diagrams for each intersection, which are significant to traffic flow analysis and signal timing design. Currently, there is only a few graph generator available online for free, and it is almost as cumbersome to draw in excel as it is to calculate by hand. Therefore, this project aims to build a GUI with the embedded algorithm to solve the cycle length, plot the input features for specific intersections, and pack it into an executable file. The calculations are derived from traffic flow theory and rearranged mathematically into equations, programmed with the Pandas package's aid. The GUI interface was derived via the Tkinter package and used Pyinstaller to an executable file. As a result, the software runs smoothly without delays and gives good plots as expected. With more modifications, it can serve for real-time traffic data analysis for intersections.

The 'gui' file contains the functions to process calculations. The 'real' file is the real GUI code.

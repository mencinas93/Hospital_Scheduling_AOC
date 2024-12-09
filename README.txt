aoc.ipynd - python file created by me on juptyer notebook

Data was randomly created based on hosptial surgery scheduling. Data represents the mimicking of one day hosptial scheduling based on a small to medium size hospital.

Multiple parameters are ran on aoc.ipynd file. Same data is kept on every parameter run. 

40 surgeries, 8 operating rooms, 12 surgeons
Surgery ID, Duration, Priority, Post Time, Recovery Time
Priority are Emergency, High, Medium and low
Unique duration time for different priority as well weights
Penalites for unscheduled surgeries

Operating rooms and surgeons have avaiable time of being open or being able to work.

My AOC file has multiple functions on first main set of code. Just runs one parameter to test how it functions. Output is best fitness run results (fitness score (with penalities) and percentage), what was scheduled and what was not scheduled for best fitness run. Output further shows why the unscheduled surgery/s was not complete and if rooms or surgeons are needed to complete this. Also set schedule surgery were scheduled for best fitness run as well as what the order of rooms and surgeons were assigned for those surgeries. For extra add on I print out each iteration and run with their unique fitness results. 

Second part of AOC file code was all the unique parameters (243 combinations).
Random the data one time but keep it the same as that first random data for all parameters so its consistent and reliable for testing later.

Now will run every parameter 5 times and average out the parameters (Max fitness, Average Fitness, Minimum Fitness, Fitness percentage, unscheduled surgeries, remaining room time, remaining surgeon time). 

Every unique combination was placed on a csv file called ant_colony_results.csv.
Final code is my output to visualize my unique combinations
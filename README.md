## PHILOSOPHERS
### I never thought philosophy would be so deadly

My Solution for the philosophers problem as part of the core curriculum from 42Berlin.

#### Summary:<br>
In this project, i learned the basics of threading a process.<br>
I learned how to create threads and I discovered how mutexes work.

#### The program takes the following arguments:<br>
number_of_philosophers<br>
time_to_die [time in ms]<br>
time_to_eat [time in ms]<br>
time_to_sleep [time in ms]<br>
number_of_times_each_philosopher_must_eat (optional)<br>
<br>
To build the executable use make.<br>
It will create an executable named philo.<br>

#### Example input:<br>
./a.out 7 400 100 100 (without number of meals)<br>
./aout 7 400 100 100 5 (with number of meals)<br>

#### Result:
input: ./philo 3 400 100 100 2<br>
<br>
1 3 has taken a fork<br>
1 3 has taken a fork<br>
1 3 is eating<br>
1 1 has taken a fork<br>
101 3 is sleeping<br>
101 2 has taken a fork<br>
101 1 has taken a fork<br>
101 1 is eating<br>
201 3 is thinking<br>
201 1 is sleeping<br>
201 2 has taken a fork<br>
201 2 is eating<br>
301 1 is thinking<br>
301 2 is sleeping<br>
301 3 has taken a fork<br>
301 3 has taken a fork<br>
301 3 is eating<br>
302 1 has taken a fork<br>
401 2 is thinking<br>
401 1 has taken a fork
401 1 is eating<br>
401 3 is sleeping<br>
402 2 has taken a fork<br>
501 3 is thinking<br>
501 1 is sleeping<br>
501 2 has taken a fork<br>
501 2 is eating<br>
601 1 is thinking<br>
601 2 is sleeping<br>
601 3 has taken a fork<br>
601 3 has taken a fork<br>
601 3 is eating<br>
602 1 has taken a fork<br>

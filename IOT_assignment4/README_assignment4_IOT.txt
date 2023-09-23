question 2
	Process(A, 0, 30 min, 3),
        Process(B, 00:10, 20 min, 1),
        Process(C, 00:15, 40 min, 4),
        Process(D, 00:20, 15 min, 2)
(NON Preemptive)

FCFS Scheduling:
Process	Waiting Time	Turnaround Time
A	0		30
B	20		40
C	35		75
D	70		85
Average Waiting Time: 31.25
Average Turnaround Time: 57.5

SJF Non-Preemptive Scheduling:
Process	Waiting Time	Turnaround Time
D	0		15
B	25		45
A	55		85
C	70		110
Average Waiting Time: 37.5
Average Turnaround Time: 63.75

Priority Scheduling Non-Preemptive:
Process	Waiting Time	Turnaround Time
B	0		20
D	10		25
A	45		75
C	60		100
Average Waiting Time: 28.75
Average Turnaround Time: 55.0

priority scheduling is best for this question.
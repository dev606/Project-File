                        ----------------------- Scheduling -----------------------



Queue 1 has higher priority than Queue 2

In Queue 1 priority no:- 0 is the highest




Enter no of processes:
Enter Priority for Process [0] : 5
Enter Burst Time for Process [0] : 10
Enter Arrival Time for Process [0] : 0

Enter Priority for Process [1] : 2
Enter Burst Time for Process [1] : 5
Enter Arrival Time for Process [1] : 0

Enter Priority for Process [2] : 1
Enter Burst Time for Process [2] : 3
Enter Arrival Time for Process [2] : 2

Enter Priority for Process [3] : 4
Enter Burst Time for Process [3] : 20
Enter Arrival Time for Process [3] : 5

Enter Priority for Process [4] : 3
Enter Burst Time for Process [4] : 2
Enter Arrival Time for Process [4] : 10


                         -------------- Entered Values are --------------

                        ---------------------------------------------------------------
                        | Process | Priority | Arrival Time | Burst Time | Queue |
                        ---------------------------------------------------------------
                        |  P[0]   |      5     |     0      |    10    |    1    |
                        |  P[1]   |      2     |     0      |    5     |    1    |
                        |  P[2]   |      1     |     2      |    3     |    1    |
                        |  P[3]   |      4     |     5      |    20    |    1    |
                        |  P[4]   |      3     |     10     |    2     |    1    |
                        -------------------------------------------------------------


                        -------------- Entered Values after Sorting according to priority and arrival time are --------------

                        ---------------------------------------------------------------
                        | Process | Priority | Arrival Time | Burst Time | Queue |
                        ---------------------------------------------------------------
                        |  P[1]   |      2     |     0      |    5    |    1    |
                        |  P[0]   |      5     |     0      |    10   |    1    |
                        |  P[2]   |      1     |     2      |    3    |    1    |
                        |  P[3]   |      4     |     5      |    20   |    1    |
                        |  P[4]   |      3     |     10     |    2    |    1    |
                        -------------------------------------------------------------
1


                         -------------- Results are -------------------

                        ---------------------------------------------------------------------------------------------------------------------------------------------
                        | Process | Priority | Arrival Time | Burst Time | Waiting Time | Completion Time | Tournaround Time
                        ---------------------------------------------------------------------------------------------------------------------------------------------
                        |  P[1]   |      2     |     0      |       5      |        0       |       5       |      5      |
                        |  P[0]   |      5     |     0      |       10     |        5       |       15      |      15     |
                        |  P[2]   |      1     |     2      |       3      |        15      |       18      |      16     |
                        |  P[3]   |      4     |     5      |       20     |        18      |       38      |      33     |
                        |  P[4]   |      3     |     10     |       2      |        38      |       40      |      30     |
                        --------------------------------------------------------------------------------------------------------------------------------------------



Average waiting time:15
Average Turn Around Time:19

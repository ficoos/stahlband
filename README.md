## A script to easly follow unix pipes

Stahlband is a helper tool easly find the other end of a pipe.

To see all the exists of a pipe just input a known end of the pipe:
    `stahlband <PID> <FD>`

    $ stahlband 5758 5
    PID: 5758 FD: 5 KIND: r
    PID: 5758 FD: 6 KIND: w
    PID: 5770 FD: 5 KIND: r
    PID: 5770 FD: 6 KIND: w

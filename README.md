# get_next_line_origin
This is a project to working on this function which read content line by line and returns a line, read from afile descriptor, without the newline..
Prototype  : int get_next_line(int fd, char **line);
Parameters : #1.  file descriptor for reading        #2.  The value of what has been read
Return value  :    1 :  A line has been ,  read0 :  EOF has been reached   ,-1 :  An error happened
External functs.: read, malloc, free

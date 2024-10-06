#指定编译器
CC = gcc

#编译选项
CFLAGS = -g -O2 -Wall -Werror
OBJ = hello
OBJS = hello.o add.o mu.o
# TODO
$(OBJ) : $(OBJS)
	$(CC) $(OBJS) -o $(OBJ)
$*.o :$%.c 
	$(CC) -c $^ -o $@
.PHONY:clean
clean:
	$(RM) *.o hello	
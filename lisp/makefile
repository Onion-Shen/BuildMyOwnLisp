MPC_FLAG = mpc.c
C_FLAG = -std=c99 -Wall -g -O3 
READLINE_FLAG = -ledit

build:
	gcc $(C_FLAG) $(MPC_FLAG) $(READLINE_FLAG) main.c -o lisp

clean:
	rm lisp
	rm -r lisp.dSYM
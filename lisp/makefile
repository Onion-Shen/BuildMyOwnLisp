MPC_FLAG = lisp/mpc.c
C_FLAG = -std=c99 -Wall -g
READLINE_FLAG = -ledit

build:
	gcc $(C_FLAG) $(MPC_FLAG) $(READLINE_FLAG) lisp/main.c

clean:
	rm a.out && rm -r a.out.dSYM
MPC_FLAG = lisp/lib/mpc.c
C_FLAG = -std=c99 -Wall -g
READLINE_FLAG = -ledit
ENTRY = lisp/main.c

build:
	gcc $(C_FLAG) $(MPC_FLAG) $(READLINE_FLAG) $(ENTRY)

clean:
	rm a.out && rm -r a.out.dSYM
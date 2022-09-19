info :
	@echo "the only thing you can do here:"
	@echo "make fooprog"
OBJS = foo.o bar.o
CXX = icpc
FLAGS = -g -O2
fooprog : ${OBJS}
	${CXX} -o $@ ${OBJS}
# template compilation rule
%.o : %.cxx 
	${CXX} ${FLAGS} -c $<
${OBJS} : bar.h

clean :
	rm -f *~ fooprog *.o

# C-x 2 vertical 2 panes
# C-x o goto other pane
# C-x 0 remote this pane
# C-x 1 make this the only pane
# ESC % : query replace
# ESC x replace-string : unconditional replace
# ESC x repl<SPACE>st<SPACE>

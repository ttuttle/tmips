CFLAGS = -Wall -Wextra -Wno-unused -ansi

TMIPS_OBJS = config.o core.o core_cp0.o debug.o err.o exc.o filter.o main.o mem.o ram.o readmemh.o serial.o util.o

tmips: $(TMIPS_OBJS)
	$(CC) $^ -o $@

clean:
	rm -f tmips $(TMIPS_OBJS)

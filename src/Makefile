CC = cc
CFLAFS = -Wall -Werror -Wextra
SOURCES=
EXECUTABLE=
all: style stage_name:
	$(CC) $(CFLAGS) $(SOURCES) -o $(EXECUTABLE)

style:
	cp -R ../materials/linters/.clang-format ../src/.clang-format
	clang-format -n *.c *.h
clean:
	rm -r $(EXECUTABLE)

CC = clang 
CFLAGS = -Wall -Wextra -02
TARGET = textstat
SRC = main.c

.PHONY: all clean run

all: $(TARGET)

$(TARGET): $(SRC)
	$(CC) $(CFLAGS) -o $(TARGET) $(SRC)

run: all
	./$(TARGET)

clean:
	rm -rf $(TARGET)

TARGET=main
all:$(TARGET)

$(TARGET):$(TARGET).o
	gcc -o $@ $^

%.o:%.c
	gcc -c $^

clean:
	rm -rf $(TARGET)
	rm -rf *.o

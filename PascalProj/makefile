OBJ =main.o pascal_triangle.o get_input.o
APPNAME = pascal

$(APPNAME) : $(OBJ)
	gcc -o $(APPNAME) $(OBJ)
%.o : %.c		#compiling rule, for each .c file in the folde	
	gcc -g -c -o $@ $<
clean:
	rm $(OBJ) $(APPNAME)


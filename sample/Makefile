all: compile exec

#compile the library
compile:
	g++ -c -o dummy.o dummy.cc

#create the library
exec: dummy.o
	ar rcs dummy.a dummy.o

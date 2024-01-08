# Project: new_interpreter
# Makefile created by Dev-C++ 4.9.9.2

CPP  = gcc
CC   = gcc
WINDRES = windres
RES  =
OBJ  = instructions.o main.o VM_duongnn.o $(RES)
LINKOBJ  = instructions.o main.o VM_duongnn.o $(RES)
LIBS =  -L"C:/Dev-Cpp/lib"
INCS =  -I"C:/Dev-Cpp/include"
CXXINCS =  -I"C:/Dev-Cpp/lib/gcc/mingw32/3.4.2/include"  -I"C:/Dev-Cpp/include/c++/3.4.2/backward"  -I"C:/Dev-Cpp/include/c++/3.4.2/mingw32"  -I"C:/Dev-Cpp/include/c++/3.4.2"  -I"C:/Dev-Cpp/include"
BIN  = new_interpreter
CXXFLAGS = $(CXXINCS)
CFLAGS = $(INCS)
RM = rm -f

.PHONY: all all-before all-after clean clean-custom

all: all-before new_interpreter all-after


clean: clean-custom
	${RM} $(OBJ) $(BIN)

$(BIN): $(OBJ)
	$(CPP) $(LINKOBJ) -o "new_interpreter" $(LIBS)

instructions.o: instructions.c
	$(CPP) -c instructions.c -o instructions.o $(CXXFLAGS)

main.o: main.c
	$(CPP) -c main.c -o main.o $(CXXFLAGS)

VM_duongnn.o: VM_duongnn.c
	$(CPP) -c VM_duongnn.c -o VM_duongnn.o $(CXXFLAGS)

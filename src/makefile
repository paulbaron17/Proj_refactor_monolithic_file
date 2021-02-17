CFLAGS = -Wall


all: fileio.o utils.o proj_refactor_file.o
	g++ -o myexe fileio.o utils.o proj_refactor_file.o
	
	


fileio.o: ../fileio/fileio.cpp ../includes/fileio.h ../includes/constants.h
	g++ $(CFLAGS) -c ../fileio/fileio.cpp
	

utils.o: ../utils/utils.cpp 
	g++ -c ../utils/utils.cpp
	

proj_refactor_file.o: ../src/proj_refactor_file.cpp 
	g++ -c proj_refactor_file.cpp


clean:

	rm *.o myexe

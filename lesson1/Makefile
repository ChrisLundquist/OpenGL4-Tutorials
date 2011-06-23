CC = g++
FRAMEWORKS = -framework GLUT -framework OpenGL
LIBS = /usr/lib/libGLEW.dylib
APP = lesson1

%.o: %.cpp
	$(CC) -c $< 


all: lesson1.o textfile.o
	$(CC) $(FRAMEWORKS) $(LIBS) *.o -o $(APP)

clean:
	rm *.o
	rm $(APP)

test: lesson1.o
	./$(APP)

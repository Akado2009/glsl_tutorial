CXX=g++
LIBS=-lGL -lGLU -lglfw3 -lX11 -lXxf86vm -lXrandr -lpthread -lXi -ldl
GLAD=glad.c
RM=rm -rf
EXECS=hello_window triangle shaders

hellowindow:
	$(CXX) -o hello_window hello_window.cpp $(GLAD) $(LIBS)

triangle:
	$(CXX) -o triangle triangle.cpp $(GLAD) $(LIBS)

shaders:
	$(CXX) -o triangle shaders.cpp $(GLAD) $(LIBS)

clean:
	$(RM) $(EXECS)

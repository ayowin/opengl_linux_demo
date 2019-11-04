
# opengl_linux_demo

opengl_linux_demo project demo base on 'glfw' , 'glad' enviroment.*

## compile
```shell
	g++ *.cpp *.c -o opengl_linux_demo -I./include -L./lib -lglfw3 -lpthread -ldl -lm -lGL -lGLU -lX11
```

## compile main.cpp

```shell
	g++ main.cpp *.c -o opengl_linux_demo -I./include -L./lib -lglfw3 -lpthread -ldl -lm -lGL -lGLU -lX11
```

## compile 01_trangle.cpp

```shell
	g++ 01_trangle.cpp *.c -o opengl_linux_demo -I./include -L./lib -lglfw3 -lpthread -ldl -lm -lGL -lGLU -lX11
```


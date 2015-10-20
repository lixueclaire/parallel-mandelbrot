gcc mandelbrot.c -lglut -lGLU -lGL -o mandelbrot
./mandelbrot

g++ -fopenmp OMP_mandelbrot.cpp -lglut -lGLU -lGL -o omp
./omp
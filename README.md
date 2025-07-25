# readme

Compile the source file into an object file:

    g++ -c main.cpp "C:\SFML\include"

Link the object file to the SFML libraries to create an executable:

    g++ main.o -o main -L C:\SFML\lib -lsfml-graphics -lsfml-window -lsfml-system

Run the executable:

    .\main

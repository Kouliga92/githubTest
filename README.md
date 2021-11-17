////**************************************************************** 
//CSCI 331 - Software Systems - 2021                             *
// Zip Code Group project-1                                      *
//Due date : 10/24/2021                                          *
//This project process a sequential CVS file using a buffer class*
//                                                               *
//This is the main soiurce code file.                            *
//****************************************************************


#include <iostream>
#include <fstream>
#include <string>
#include "buffer.h"
#include "record.h"
using namespace std;

int main()
{
    Buffer buffer;
    buffer.read();
    buffer.vectorAlphabetize(buffer.outer);
    buffer.generateTable(buffer.outer);
}
// This is a C++ file for Ben to mess with as a time waster

#include <iostream>
#include <string>
#include <fstream>

using std::string;

/**
 * User
*/
class User {
    private:
    
    // Basic Info
    string user;
    int age;

    // Nonsensical Logging
    int yearsWorkedAtCgh;
    int timesMigratedToWaterCooler;
    int openedFridge;

    public:
    
    void printName() {
        std::cout << user << std::endl;
    }

    void setName() {
        std::cout << "What is your name?\n";
        std::cin >> user;
        std::cout << "Your name has been successfully set.\n";
    }
};

/**
 * Logger
*/
class Logger {
    private:
    int timeLogged;
    public:
    void inputLog() {
        
    }
};

int main() {
    return 0;
}

[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name: Eugene Song
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>

using namespace std;

class Car {

private:
    string model;
    int year;
    string color;

public:

    void setYear(int y) {
    year = y;
}

    int getYear() const {
    return year;
}
    void setModel(string m) {
        model = m;
}

    string getModel() const {
    return model;
}

    void setColor(string c) {
    color = c;
}

    string getColor() const {
    return color;
}
    
    void displayDetails() {
        cout << "Model: " << getModel() << ", Year: " << getYear() << ", Color: " << getColor() << endl;
    }
};

int main() {
    Car myCar;

    myCar.setModel("Toyota");
    myCar.setYear(2024);
    myCar.setColor("Silver");

    myCar.displayDetails();

    return 0;
}

```

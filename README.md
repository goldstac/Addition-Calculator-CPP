# 🧮 Multiplication Calculator C++
## A Simple Multiplication Calculator Written In C++
```cpp
#include <iostream>
using namespace std;
int main() {
    int first_number;
    int second_number;
    cout << "Enter First Number\n";
    cin >> first_number;
    cout << "Enter Second Number \n";
    cin >> second_number;
    int calculate;
    calculate = first_number * second_number;
    cout << "Total Is" << " " << calculate;
    return 0;
}
```
### To Compile
#### Make Sure You Have GCC/G++ Installed
### In Terminal Type
```bash
g++ -o main main.cpp
```
## Then To Run
#### When You Have The Exe
### Type
```bash
./main
```

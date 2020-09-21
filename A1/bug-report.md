# Bug 1

1. **The incorrect original code or code snippit that you wrote:**

``` cpp
//code with bugs or code snippet with bug goes here

//sample code

// Online C++ compiler to run C++ online.
// Write C++ code in this online editor and run it.

#include <iostream>

int main() {
    std:cout << "Hello World!";
  
  return 0;
}

```

2. **What bug does the original code have?**
Code lines not written in order
  

3. **What misunderstanding of C++ concepts lead you to this incorrect code?**
what is the reason of using iostream

4. **How to correct the bug?**

using dthe correct and appropriate syntax for the code

5. **The corresponding bug-free code or code snippet is:**

#include <iostream>
int main() {
    int speed, time, distance;
    speed=20;
    time=10;

    distance = speed * time;
    cout <<"distance is:"<< distance;
    return 0;
}

6. **What is the take-away message from this bug?**
follow proper order to form the appropriate code

# Bug 2

1. **The incorrect original code or code snippit that you wrote:**

// ConsoleApplication1.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include<iostream>

int main() {


    float force;               
    force = 172.5;         

    float area;                
    area = 27.5;            

    float pressure;           
    pressure = force / area ; 

    cout << "The total pressure is " << pressure << endl;
    return 0;
}

2. **What bug does the original code have?**

  using namespace std is not used.

3. **What misunderstanding of C++ concepts lead you to this incorrect code?**

not knowing the value or use of using namespace std;

4. **How to correct the bug?**
use namespace std after iostream

5. **The corresponding bug-free code or code snippet is:**

```
// ConsoleApplication1.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include<iostream>
using namespace std;

int main() {


    float force;               
    force = 172.5;         

    float area;                
    area = 27.5;            

    float pressure;           
    pressure = force / area ; 

    cout << "The total pressure is " << pressure << endl;
    return 0;
}

```

6. **What is the take-away message from this bug?**
To use namespace std

## Hi there 👋

```cpp
#include <iostream>
#include <vector>

using namespace std;

class JoseCarlosGalvanKamey {
  public:
    string name = "Jose Carlos Galvan Kamey";
    string profession = "Software Developer";
    vector<string> technologies = {"CPP", "Java"}

    void introduction() {
      cout << "Hello, I'm " << name << " 👋\n";
      cout << "I'm a " << profession << " passionate about continuous learning and competitive programming.\n";
    }
};

int main() {
  JoseCarlosGalvanKamey dev;
  dev.introduction;
  return 0;
}
```

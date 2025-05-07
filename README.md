#include <iostream>
using namespace std;
class Pip {
 string name;
public:
 void res()
 {
  cout << "Введите ваше имя:  " << name << endl;
  cin >> name;
  cout << name << endl;
 }
};
int main()
{
 setlocale(LC_ALL, "Russian");
 PIP k;
 k.res();
 
}

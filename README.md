# Lab-11.10
#include <iostream>
using namespace std;

int main() {
  string answer;
  cout << "What is the capital of France? \n";
  cin >> answer;

  while (answer != "Paris") // if this is true and then line 16 is the output
  {
    cout << "Incorrect! Try again.\n"; // if the loop is false then this part is excuted 
    cout << "What is the capital of France? \n"; // test the answer again to see if the input is correct which it then goes to line 16 
    cin >> answer;
  }

  cout << "Correct!\n";
}

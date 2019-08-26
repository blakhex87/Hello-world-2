# Hello-world-2
retry

#include <iostream>
using namespace std;

int hello1Function(string name1);
int hello2Function(string name2);

int main()
{
	string name1="Blake Jones";
	hello1Function(name1);
	string name2="Jawad Ayache";
	hello2Function(name2);
	return 0;
}

int hello1Function(string name1)
{
cout << "hello World " << name1 << endl;
return 0;
}

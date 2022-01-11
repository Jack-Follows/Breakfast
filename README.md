# Breakfast
**For Breakfast I made four pieces of heavily buttered toast, I only had three slices though as my dog had the other one.**
**I also made bowl of cereal and a cup of tea because I was extra hungry**
*You can find more updates over at [My LinkedIn](https://www.linkedin.com/in/jack-lewis-follows-38392a1a2/)*
![Image of Octobi Wan Catnobi](https://i.pinimg.com/564x/dc/ef/3a/dcef3abedf0e0761203aaeb85886a6f3.jpg)
### My Top 5 Favourite Games
1. No Mans Sky
2. Halo 3
3. Call of Duty World at War
4. Left for Dead 2
5. Prototype 2
### To do List (Pro Dev)
- [x] Complete the Breakfast task
- [x] Complete my 1000 word report
- [ ] Submit all my course work for Pro Dev
### Snippet of GEC Code
```javascript
// Program26_ReplacingCharacters.cpp : This file contains the 'main' function. Program execution begins and ends there.
//

#include <iostream>
#include <string>
using namespace std;

string ReplaceAll(string Input, const string& from, const string& to);

int main()
{
	string Input;
	cout << "Please enter a sentance \n";
	getline(cin, Input);
	cout << "Sentance before the Magic happens: \n" << Input << endl;
	cout << "*POOF* Magic has turned all your 'e's to 'x's!: \n";
	cout << ReplaceAll(string(Input), string("e"), string("x")) << endl;
}

string ReplaceAll(string str, const string& from, const string& to)
{
	size_t Pos = 0;
	while ((Pos = str.find(from, Pos)) != string::npos)
	{
		str.replace(Pos, from.length(), to);
		Pos += to.length();
	}
	return str;
}
```
This is a README file brought to you by Jack Follows :sunglasses: :monocle_face: :zany_face:

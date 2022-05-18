# Vladislav Samsonov
### IT Manager
___
### Contact information
Phone: +375 29 9133086  
Email: camconov2000@gmail.com  
Telegram: @b0nexxy
___
### Skills   
* C++  
* PowerPoint  
* Illustrator
* Microsoft Exel  
* Microsoft Word
* Adobe photoshop
* Adobe After Effects
___
### Education
IT Manager, 1 grade, VSU named after P. M. Masherov
___
### English level
B1
___
### Code example
```
#include <iostream>
#include <cstdlib>
using namespace std;
int main(int argc, char* argv[]) {
	int x, y;
	if (argc==2) {
		char* number= argv[1];
		switch(*number){
		case 'A': {
			cout << "Selected the first task\n";
			cout << "Enter the beginning of the segment: \n";
			cin >> x;
			cout << "Enter the end of the segment:\n";
			cin >> y;
			if (x = y) {
				cout << "The coordinates of the segment cannot match!\n";
				cerr << "The coordinates of the segment cannot match!\n";
			}
			else {
				cout << "The length of the segment is:" << y - x << "\n";
			}
		}
				break;
		case 'B': {
			cout << "Selected the second task\n";
			cout << "Enter the value of the middle line\n";
			cin >> x;
			cout << "Enter the trapezoid height:\n ";
			cin >> y;
			if (x <= 0 || y <= 0) {
				cout << "The middle line and height cannot take negative values!\n";
				cerr << "The middle line and height cannot take negative values!\n";
			}
			else {
				cout << "The trapezoid area is:" << x * y << "\n";
			}
		}
				break;
		case 'C': {
			cout << "Selected the third task\n";
			cout << "Enter the lenght of the first side:\n";
			cin >> x;
			cout << "Enter the lenght of the second side:\n";
			cin >> y;
			if (x <= 0 || y <= 0) {
				cout << "The lenght of the side cannot take negative values!\n";
				cerr << "The lenght of the side cannot take negative values!\n";
			}
			else {
				cout << "The rectangle area is:" << x * y << "\n";
			}
		}
				break;
		default: {
			cout << "No tasks\n";
			cerr << "No tasks\n";
			break;
		}
		}
	}
	else {
		cout << "Program need parametr\n";
		cerr << "Program need parametr\n";
	}
	system("pause");
	return 0;
}


```

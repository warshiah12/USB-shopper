# USB-shopper
#6 usb sticks
#include <iostream>
using namespace std;

int main()
{
    int usb = 6, rem; //declaring variable with datatype integer
    int money = 50, buy;
    buy = money / usb; //calculating how many usb sticks she can buy for 50
    cout << "The amount of USB sticks you can buy are " << buy << endl;
    rem = money - usb * 8;  //calculating remaining money
    cout << "Remaining money: " << rem << endl;

    return 0;
}

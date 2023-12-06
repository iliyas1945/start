#include <iostream>

using namespace std;

int main()
{
    int a, x, y;
    a = 0;
    cout << "укажите диапазон: \n";
    cin >> x >> y;
    cout << "Сумма нечетных чисел диапазона: \n";
    for (int i = x; i <= y; i++)
    {
        if (i % 2 != 0)
        {
            a += i;
        }
    }
    cout << a << endl;
}

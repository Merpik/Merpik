#include <iostream>
#include <cmath>

int main() {
    // Задані значення a, b та x
    double a = 0.001;
    double b = 5.8;
    double x = 1.77;

    // Обчислення значення s
    double s = std::pow(x, 3) * std::tan(std::pow(x + b, 2)) + a / std::sqrt(x + b);

    // Обчислення значення d
    double d = b * std::pow(x, 2) - a / std::exp(a * x) - 1;

    // Вивід результатів
    std::cout << "Для a = " << a << ", b = " << b << ", x = " << x << ", s = " << s << ", d = " << d << std::endl;

    return 0;
}

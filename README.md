# Quadratic-Formula

#include <iostream>
#include <cmath>

int main() {
  double a;
  double b;
  double c;

std::cout << "enter a: \n";
std::cin >> a;

std::cout << "enter b: \n";
std::cin >> b;

std::cout << "enter c: \n";
std::cin >> c;
  
  double root1= (-b + std::sqrt(b*b - 4*a*c)) / (2*a);
 std::cout << "Root 1: " << root1 << "\n";

  double root2 =(-b - std::sqrt(b*b-  4*a*c)) / (2*a);
  std::cout << "Root 2: " << root2 << "\n";

}

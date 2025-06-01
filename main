#include <cmath>
#include <iostream>
// Get values
double getvalues() {
  std::cout << "Enter value: ";
  double input{};
  std::cin >> input;
  return input;
}
// cylinder module //
int findcylinder() {
  std::cout << "Type {1} to solve for volume, {2} for height, {3} for radius: ";
  int choice;
  std::cin >> choice;

  if (choice == 1) {
    // Solve for volume
    std::cout << "To find the volume of cylinder: " << "\n";
    std::cout << "Type radius first, height second." << "\n";
    double radius{getvalues()};
    double height{getvalues()};

    // Formula: V = π * r² * h
    double volume = M_PI * radius * radius * height;
    double volume2 = radius * radius * height;
    std::cout << "The volume is: " << volume << "\n";
    std::cout << "The volume without pi is: " << volume2 << "\n";
  } else if (choice == 2) {
    // Solve for height
    std::cout << "To find the height of cylinder: " << "\n";
    std::cout << "Type radius first, volume second." << "\n";
    double radius{getvalues()};
    double volume{getvalues()};

    // Formula: h = V / (π * r²)
    double height = volume / (M_PI * radius * radius);
    double height2 = volume / (radius * radius);
    std::cout << "The height is: " << height << "\n";
    std::cout << "The height without pi is: " << height2 << "\n";
  } else if (choice == 3) {
    // Find Radius
    std::cout << "To find the radius of cylinder: " << "\n";
    std::cout << "Type height first, volume second." << "\n";
    double height{getvalues()};
    double volume{getvalues()};

    // Formula: r = sqrt(V / (π * h))
    double radius = sqrt(volume / (M_PI * height));
    double radius2 = sqrt(volume / height);
    std::cout << "The radius is: " << radius << "\n";
    std::cout << "The radius without pi is: " << radius2 << "\n";
  } else {
    std::cout << "Invalid choice. Please enter 1, 2, or 3." << "\n";
  }
  return 0;
}
// sphere module
int findsphere() {
  std::cout << "Type {1} to solve for volume, {2} diameter, {3} for radius: ";
  int choice;
  std::cin >> choice;

  if (choice == 1) {
    std::cout << "To find the volume of Sphere: " << "\n";
    std::cout << "Type radius." << "\n";
    double getradius{getvalues()};
    //  V = (4/3) * π * r³
    double volume = (4.0 / 3.0) * M_PI * getradius * getradius * getradius;
    double volume2 = (4.0 / 3.0) * getradius * getradius * getradius;
    std::cout << "The volume is: " << volume << "\n";
    std::cout << "The volume without pi is: " << volume2 << "\n";
  } else if (choice == 2) {
    std::cout << "To find the diameter of Sphere: " << "\n";
    std::cout << "Type radius." << "\n";
    double getradius = getvalues();
    double diameter = 2 * getradius;
    std::cout << "The diameter is: " << diameter << "\n";
  } else if (choice == 3) {
    std::cout << "To find the radius of Sphere: " << "\n";
    std::cout << "Type volume." << "\n";
    double getvolume = getvalues();
    double volume = (3 * getvolume) / (4 * M_PI);
    double volume2 = ((3 * getvolume) / (4));
    std::cout << "The volume is: " << volume << "\n";
    std::cout << "The volume without pi is: " << volume2 << "\n";
  } else {
    std::cout << "Invalid choice. Please enter 1, 2, or 3." << "\n";
  }

  return 0;
}
// cone module
int findcone() {
  std::cout << "Type {1} to solve for volume, {2} for height, {3} for radius: ";
  int choice;
  std::cin >> choice;

  if (choice == 1) {
    std::cout << "To find the volume of cone: " << "\n";
    std::cout << "Type radius first, height second." << "\n";
    double radius{getvalues()};
    double height{getvalues()};

    // Formula: V = (1/3) * π * r² * h
    double volume = ((1.0 / 3.0) * M_PI * radius * radius * height);
    double volume2 = ((1.0 / 3.0) * radius * radius * height);
    std::cout << "The volume is: " << volume << "\n";
    std::cout << "The volume without pi is: " << volume2 << "\n";
    return 0;

  } else if (choice == 2) {
    std::cout << "To find the height of cone: " << "\n";
    std::cout << "Type volume first, radius second." << "\n";
    double volume{getvalues()};
    double radius{getvalues()};

    // Solving for h: h = (3 * V) / (π * r²)
    double height = (3.0 * volume) / (M_PI * radius * radius);
    double height2 = (3.0 * volume) / (radius * radius);  // without pi

    std::cout << "The height is: " << height << "\n";
    std::cout << "The height without pi is: " << height2 << "\n";

    return 0;
  } else if (choice == 3) {
    std::cout << "To find the radius of cone: " << "\n";
    std::cout << "Type volume first, height second." << "\n";
    double volume{getvalues()};
    double height{getvalues()};

    // Solving for r: r = √((3 * V) / (π * h))
    double radius_squared = (3.0 * volume) / (M_PI * height);
    double radius = sqrt(radius_squared);

    double radius_squared2 = (3.0 * volume) / height;  // without pi
    double radius2 = sqrt(radius_squared2);

    std::cout << "The radius is: " << radius << "\n";
    std::cout << "The radius without pi is: " << radius2 << "\n";
  } else {
    std::cout << "Invalid choice. Please enter 1, 2, or 3." << "\n";
  }

  return 0;
}
// pyramid module
int findpyramid() {
  std::cout
      << "Type {1} to solve for volume, {2} for height, {3} for base area: ";
  int choice;
  std::cin >> choice;

  if (choice == 1) {
    std::cout << "To find the volume of pyramid: " << "\n";
    std::cout << "Type base area first, height second." << "\n";
    double base_area{getvalues()};
    double height{getvalues()};

    // Formula: V = (1/3) * base_area * height
    double volume = ((1.0 / 3.0) * base_area * height);
    std::cout << "The volume is: " << volume << "\n";
    return 0;

  } else if (choice == 2) {
    std::cout << "To find the height of pyramid: " << "\n";
    std::cout << "Type volume first, base area second." << "\n";
    double volume{getvalues()};
    double base_area{getvalues()};

    // Solving for h: h = (3 * V) / base_area
    double height = (3.0 * volume) / base_area;

    std::cout << "The height is: " << height << "\n";

    return 0;
  } else if (choice == 3) {
    std::cout << "To find the base area of pyramid: " << "\n";
    std::cout << "Type volume first, height second." << "\n";
    double volume{getvalues()};
    double height{getvalues()};

    // Solving for base_area: base_area = (3 * V) / h
    double base_area = (3.0 * volume) / height;

    std::cout << "The base area is: " << base_area << "\n";
  } else {
    std::cout << "Invalid choice. Please enter 1, 2, or 3." << "\n";
  }

  return 0;
}
int main() {
  std::cout << "Hello, welcome to the shape calculator. Please select a shape."
            << ".\n";
  std::cout << "{1} Cylinder. {2} Sphere. {3} Cone. {4} Pyramid." << ".\n";
  int choice;
  std::cin >> choice;
  if (choice == 1) {
    findcylinder();
  } else if (choice == 2) {
    findsphere();
  } else if (choice == 3) {
    findcone();
  } else if (choice == 4) {
    findpyramid();
  } else {
    std::cout << "Invalid choice. Please enter 1, 2, or 3." << "\n";
  }
  return 0;
}

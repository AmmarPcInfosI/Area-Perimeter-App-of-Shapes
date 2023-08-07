# Area and Perimeter Calculation App

This project is a simple Java application that allows the user to calculate the area and perimeter of different shapes. The project is authored by Ammar Al Hasani and was developed as a task given by Code Academy Oman.

## Getting Started

To use this application, you need to have Java installed on your computer. If you don't have it installed, you can download it from the official Java website (https://www.java.com/).

## How to Use

1. Run the Main.java file, which contains the main method, to start the application.
2. You will be prompted with a welcome message and asked to choose a shape to calculate its area and perimeter.
3. Enter the corresponding number for the shape you want to calculate: 1 for Rectangle, 2 for Triangle, and 3 for Circle.
4. Depending on your choice, you will be asked to provide the required dimensions of the shape.
5. After providing the necessary inputs, the application will display the calculated area and perimeter of the selected shape.
6. You will then be asked if you want to calculate another shape. Enter 'y' for yes and 'n' for no.
7. If you choose 'y', you can repeat the process for another shape; otherwise, the application will end with a thank you message.

## Supported Shapes

### 1. Rectangle
- To calculate the area and perimeter of a rectangle, you need to provide the width and height.

### 2. Triangle
- To calculate the area and perimeter of a triangle, you need to provide the base, adjacent sides, and height.

### 3. Circle
- To calculate the area and perimeter of a circle, you need to provide the radius.

## Shape Class Hierarchy

The project uses an abstract class named `Shape`, which serves as the base class for `Rectangle`, `Triangle`, and `Circle` classes. Each shape class extends the `Shape` class and implements the `calcArea()` and `calcPerimeter()` methods to calculate the area and perimeter, respectively.

## Contributing

This project is for educational purposes and was authored by Ammar Al Hasani. Contributions and improvements to the code are welcome. If you find any issues or have suggestions for improvement, feel free to create an issue or submit a pull request.

## Author

- **Ammar Al Hasani** (GitHub: @AmmarPcInfosI)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
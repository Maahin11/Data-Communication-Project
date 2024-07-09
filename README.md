Here's a README file for your project:

---

# Data_Com Application

## Author
**Md. Jubayerul Hasan Mahin**  
**ID: 213902127**

## Package
`Data_Comes`

## Description
The `Data_Com` application is a Java Swing-based GUI tool for performing various data communication operations such as Hamming Distance calculation, Parity Check, Bit Stuffing, Bit Destuffing, Character Stuffing, and Character Destuffing.

## Features
- **Hamming Distance**: Computes the Hamming distance between two binary strings of equal length.
- **Parity Check**: Determines if a binary number has even or odd parity.
- **Bit Stuffing**: Adds a '0' after five consecutive '1's in the input binary string to ensure bit synchronization.
- **Bit Destuffing**: Removes the stuffed '0' bits from the binary string.
- **Character Stuffing**: Inserts a specific character after a flag sequence in the input data.
- **Character Destuffing**: Removes the stuffed characters from the input data (to be implemented in a future update).

## Prerequisites
- Java Development Kit (JDK) 8 or higher
- Java Swing

## Usage
1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/Data_Com.git
    ```
2. **Navigate to the project directory**:
    ```sh
    cd Data_Com
    ```
3. **Compile the project**:
    ```sh
    javac -d bin src/Data_Comes/*.java
    ```
4. **Run the application**:
    ```sh
    java -cp bin Data_Comes.Data_Com
    ```

## GUI Components
- **Input Fields**: Enter the required data in the provided text fields.
- **ComboBox**: Select the desired operation (e.g., Hamming Distance, Parity Check, etc.) from the dropdown menu.
- **Buttons**:
  - `RESET`: Clears all input and output fields.
  - `CALCULATE`: Performs the selected operation and displays the result.
  - Operation-specific buttons (e.g., `Hamming Dist`, `Parity Check`, `Bit Stuffing`): Perform the corresponding operation when clicked.
- **Output Fields**: Display the results of the operations.

## Screenshots
![GUI Screenshot](path_to_your_screenshot.png)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Java Swing for GUI components.
- The developers and contributors to the project.

---

Replace `path_to_your_screenshot.png` with the actual path to the screenshot of your GUI. Make sure to include any necessary images or files in the repository for a complete user experience.

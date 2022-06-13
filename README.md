# PROGRAM KALKULATOR SCIENTIFIC

### Table of content
  1. [Author](https://github.com/HafiedHA/tugas_kalkulator/#created-by)
  2. [How the program work?](https://github.com/HafiedHA/tugas_kalkulator/#how-the-program-work)
  3. [Flowchart](https://github.com/HafiedHA/tugas_kalkulator/#flowchart)
  4. [Division by zero](https://github.com/HafiedHA/tugas_kalkulator/#division-by-zero)
  5. [Out of range](https://github.com/HafiedHA/tugas_kalkulator/#out-of-range)

### Created by
  1. Zenix Fajar Luthfiansyah 17/413531/TK/45971 - [GitHub](https://github.com/zenyxfajar)
     -  Create public object and method
     -  Error handling
     -  Checking code
  2. Reyhan Ihza Reangga 17/413918/TK/46358 - [GitHub](https://github.com/reyhanihza)
     -  Adding trigonometry function
     -  Cheking code
  3. Contributor 3
     -  Do what

### About project

  - This Scientific Calculator Program Project created for Pemrograman Dasar Lecture Assignement. 
  - Program written in `C++` containing 15 menu of calculation including basic operation, exponential, trigonometry and logarithm.
  - For standar operation and trigonometri, output formatted to display a decimal with four significant digit.

### How the program work?

  - Program mostly in CLI
  - To start using the program, user will have run the program first
  - Then it will show the main menu of the program, containing 15 choice of calculation menu
  
  ![Halaman awal](https://user-images.githubusercontent.com/101339523/173419165-b048f2b4-b5ca-4aba-af6d-47b61f07e2fb.jpg) 
  
  - Valid input is an integer number between `1` to `15`, if user give `0` to the `input`, it will `exit` the program
  - Once user select a menu, the program will ask whether the user pick the correct menu
  
  ![opsi dipilih](https://user-images.githubusercontent.com/101339523/173419879-7094b94b-0d50-4eac-aa9b-2244d4515515.jpg)
  
  - If user say `Yes` or `Y` the program then will continue and user can start input number to be calculated
  - After calculation is done, it will ask the user if they want to continue or not, by giving input `Y` program will continue and ended if input is `N`
  
  ![calcuklation done](https://user-images.githubusercontent.com/101339523/173420301-6e34f0ba-8908-461f-9cad-1ecf992cd051.jpg)
  
  - If input is `Y` it will erase last calculation result and display the main menu
 
  ![continued](https://user-images.githubusercontent.com/101339523/173420661-26e2b60d-591b-425a-aff6-f416115602eb.jpg)
  
  - If input is `N` it will exit the program
  
  ![program end](https://user-images.githubusercontent.com/101339523/173421015-9d4d42f9-3040-47fc-97f6-760a1be4c418.jpg)

### Flowchart
  - The flow of the program can be seen in below flowchart
  
  ![Untitled Diagram (6)](https://user-images.githubusercontent.com/101339523/173421208-164851dc-8189-478f-8d06-5cb4985583bd.jpg)
  
 ### Division by zero
  - Division by zero will throw an `Math ERROR:` message.
  - The user then will be asked to input the new denominator
  
  ![division by zero](https://user-images.githubusercontent.com/101339523/173422578-7817be49-b365-4102-9540-14e39999f11a.jpg)
  
 ### Out of range
  - The inverse of sine and cosine input are defined in radian which have range between `-1 to 1` as stated in the `C++` documentation.
  - If input is `input > 1 ` or `input < -1` program will throw `MATH ERROR:` message.
  - The user will need to input a new number
  
  ![out of range](https://user-images.githubusercontent.com/101339523/173423447-a1910dc9-0493-4fd4-bce8-16622b14a8c7.jpg)



# ft_printf: A Simple printf Recreation for Exam Rank 3 at 42

## Project Overview

`ft_printf` is a programming project aimed at recreating a simple version of the `printf` function from the C Standard Library. This project is specifically designed as part of the preparation for the Exam Rank 3 at the 42 programming school. It seeks to deepen understanding of variadic functions in C, string manipulation, and basic I/O operations. The main goal is to mimic the basic functionality of the original `printf` function, including handling various format specifiers like `%s`, `%d`, and `%x`.

This implementation serves as practical exercise and a solution approach for one of the typical tasks set during the Rank 3 Exam. It is intended for students and learners at the 42 school who are preparing for this exam and want to deepen their knowledge in C programming.

## Features

- Supports printing strings (`%s`), decimal integers (`%d`), and hexadecimal integers (`%x`).
- Implements basic error handling for null string pointers by displaying `(null)`.
- Offers precision handling for negative numbers and edge cases such as `INT_MIN`.

## Installation

To use `ft_printf` for your exam preparation and beyond, please follow these steps:

1. Clone this repository to your local machine:
git clone https://github.com/EhabElasam/Rank3_ft_printf_42.git

css
Copy code

## Usage

Use `ft_printf` similarly to the standard `printf` function to format and display your output:


    ft_printf("Hello, %s!", "World");
    ft_printf("This is a number: %d and a hex: %x", 42, 42);
    For more examples and details, refer to the comments within the ft_printf.c file.

## Contributing
Your contributions are especially valuable in extending the functionality and improving error handling, ultimately benefiting all students at the 42 school preparing for the Rank 3 Exam. If you would like to contribute, please follow these steps:

 1. Fork the repository.
 2. Create a new branch for your feature (git checkout -b feature/YourGreatFeature).
 3. Commit your changes (git commit -am 'Add some YourGreatFeature').
 4. Push to the branch (git push origin feature/YourGreatFeature).
 5. Create a Pull Request.

## Acknowledgments
This project was inspired by the printf function of the C Standard Library and serves as an important resource for preparing for the Rank 3 Exam at the 42 school. It offers an excellent opportunity to dive deep into C programming and develop practical skills that are useful in the exam and beyond.

Thank you for your interest in this project.
Your support and feedback are highly appreciated and contribute to the further development of this educational tool.

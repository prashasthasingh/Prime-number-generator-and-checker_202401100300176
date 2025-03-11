# Prime-number-generator-and-checker_202401100300176

Prime Number Checker and Generator

This project contains two efficient algorithms for prime number operations:

Prime Checker — To determine if a given number is prime.

Prime Generator (using the Sieve of Eratosthenes) — To generate all prime numbers up to a specified limit.

Features

✅ Efficient prime checking using the square root method.
✅ Optimized prime generation with the Sieve of Eratosthenes.
✅ Clean, modular code with clear comments for readability.✅ Suitable for small and large-scale prime number computations.

Installation

Clone this repository:

git clone https://github.com/your-username/prime-number-toolkit.git
cd prime-number-toolkit

Ensure you have Python 3 installed. If not, install it via:

sudo apt-get install python3  # For Linux
brew install python3          # For macOS

Run the program directly:

python3 prime_checker.py

Usage

Prime Checker

To check if a number is prime, use the following:

from prime_checker import is_prime

number = 29
print(f"Is {number} prime? {is_prime(number)}")

Output: Is 29 prime? True

Prime Generator (Using Sieve of Eratosthenes)

To generate all prime numbers up to a specified limit:

from prime_checker import sieve_of_eratosthenes

limit = 50
print(f"Prime numbers up to {limit}: {sieve_of_eratosthenes(limit)}")

Output: [2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47]

Code Overview

is_prime() Function

Efficiently checks if a number is prime by testing divisibility up to sqrt(n).

Skips even numbers for improved performance.

sieve_of_eratosthenes() Function

Efficiently generates primes using the sieve algorithm with O(n log log n) complexity.

Marks non-primes efficiently, making it ideal for large limits.

Examples

Check Prime Status: is_prime(31) → True

Generate Primes Up to 100: sieve_of_eratosthenes(100) → [2, 3, 5, 7, ..., 97]

Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request with improvements or bug fixes.

Fork the project

Create your feature branch (git checkout -b feature/your-feature)

Commit your changes (git commit -m 'Add new feature')

Push to the branch (git push origin feature/your-feature)

Open a Pull Request

License

This project is licensed under the MIT License. Feel free to use, modify, and distribute the code with proper attribution.


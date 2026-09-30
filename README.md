# Binary Search Algorithm with Mypy, Docker and GitHub Actions

## 1. Project Title

**Binary Search Algorithm – Python DevOps Project**

## 2. Aim

To implement the Binary Search algorithm in Python and configure
Mypy, Docker, and GitHub Actions CI/CD to perform type checking,
testing, and automated validation.

## 3. Description

This project implements a simple Binary Search algorithm to find a
target element in a sorted list.

The project also demonstrates basic software engineering practices:

- Python type checking using Mypy
- Automated testing using Pytest
- Containerization using Docker
- Continuous Integration using GitHub Actions

## 4. Algorithm Used

### Binary Search

Binary Search works by repeatedly dividing a sorted list into two
parts.

### Steps

1. Start with the first and last positions.
2. Find the middle element.
3. Compare the middle element with the target.
4. If they are equal, return the position.
5. If the target is greater, search the right half.
6. If the target is smaller, search the left half.
7. Repeat until the target is found or the search range becomes empty.

## 5. Input Data

```text
Data = [10, 20, 30, 40, 50, 60, 70]
Target = 40

# Author-Book Relationship Example in C#

This repository contains a simple C# example demonstrating how to model relationships between authors and books using classes, lists, and LINQ.

## Table of Contents

- [Introduction](#introduction)
- [Classes](#classes)
- [Data Initialization](#data-initialization)
- [LINQ Query](#linq-query)
- [How to Run](#how-to-run)
- [Output](#output)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project provides a basic example of how to model a one-to-many relationship between authors and books in C#. It includes classes for `Author` and `Book`, initializes these classes with data, and then demonstrates how to join the data using a LINQ query.

## Classes

### Author

```csharp
public class Author
{
    public int AuthorId { get; set; }
    public string Name { get; set; }
}

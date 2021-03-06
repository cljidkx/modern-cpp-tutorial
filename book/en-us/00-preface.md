---
title: Preface
type: book-en-us
order: 0
---

# Preface

[TOC]

## Introduction

C++ user group is fairly large. From the advent of C++98 to the official finalization of C++11, it has accumulated over a decade. C++14/17 is an important complement and optimization for C++11, and C++20 brings this language to the door of modernization. The extended features of all these new standards are given to the C++ language. Infused with new vitality.
C++ programmers, who are still using **traditional C++** (this book refers to C++98 and its previous C++ standards as traditional C++), may even amazed by the fact that they are not using the same language while reading modern C++ code.

**Modern C++** (this book refers to C++11/14/17/20) introduces a lot of features into traditional C++, which makes the whole C++ become language that modernized. Modern C++ not only enhances the usability of the C++ language itself, but the modification of the `auto` keyword semantics gives us more confidence in manipulating extremely complex template types. At the same time, a lot of enhancements have been made to the language runtime. The emergence of Lambda expressions has made C++ have the "closure" feature of "anonymous functions", which is almost in modern programming languages ββ(such as Python/Swift/.. It has become commonplace, and the emergence of rvalue references has solved the problem of temporary object efficiency that C++ has long been criticized.

C++17 is the direction that has been promoted by the C++ community in the past three years. It also points out an important development direction of **modern C++** programming. Although it does not appear as much as C++11, it contains a large number of small and beautiful languages ββand features (such as structured binding), and the appearance of these features once again corrects our programming paradigm in C++.

Modern C++ also adds a lot of tools and methods to its own standard library, such as `std::thread` at the level of the language itself, which supports concurrent programming and no longer depends on the underlying system on different platforms. The API implements cross-platform support at the language level; `std::regex` provides full regular expression support and more. C++98 has been proven to be a very successful "paradigm", and the emergence of modern C++ further promotes this paradigm, making C++ a better language for system programming and library development. Concepts provide verification on the compile-time of template parameters, further enhancing the usability of the language.

In conclusion, as an advocate and practitioner of C++, we always maintain an open mind to accept new things, and we can promote the development of C++ faster, making this old and novel language more vibrant.

## Targets

- This book assumes that readers are already familiar with traditional C++ (i.e. C++98 or earlier), at least they do not have any difficulty in reading traditional C++ code. In other words, those who have long experience in traditional C++ and people who desire to quickly understand the features of modern C++ in a short period of time are well suited to read the book;

- This book introduces to a certain extent of the dark magic of modern C++. However, these magics are very limited, they are not suitable for readers who want to learn advanced C++. The purpose of this book is offering a quick start for modern C++. Of course, advanced readers can also use this book to review and examine themselves on modern C++.

## Purpose

The book claims "On the Fly". Its intent is to provide a comprehensive introduction to the relevant features regarding modern C++ (before 2020s).
Readers can choose interesting content according to the following table of content to learn and quickly familiarize the new features you would like to learn.
Readers should aware that all of these features are not required. It should be learnt when you really need it.

At the same time, instead of grammar-only, the book introduces the historical background as simple as possible of its technical requirements, which provides great help in understanding why these features comes out.

In addition, The author would like to encourage that readers should be able to use modern C++ directly in their new projects and  migrate their old projects to modern C++ gradually after read the book.

## Code

Each chapter of this book has a lot of code. If you encounter problems when writing your own code with the introductory features of the book, you might as well read the source code attached to the book. You can find the book [here](../../code). All the code organized by chapter, the folder name is the chapter number.

## Exercises

There are few exercises At the end of each chapter of the book. It is for testing whether you can use the knowledge points in the current chapter. You can find the possible answer to the problem from [here](../../exercise). The folder name is the chapter number.

[Table of Content](./toc.md) | [Next Chapter: Towards Modern C++](./01-intro.md)

## Licenses

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br />This work was written by [Ou Changkun](https://changkun.de) and licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License</a>. The code of this repository is open sourced under the [MIT license](../../LICENSE).
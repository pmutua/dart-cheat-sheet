# dart-cheat-sheet
A curated list of awesome stuff needed to get started with your flutter development journey
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ![Branch master](https://img.shields.io/badge/branch-master-brightgreen.svg?style=flat-square)
 [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/temidtech/dart-cheat-sheet/master/LICENSE)

 ## Table of Contents

- [String interpolation](#string-interpolation)
- [Functions](#functions)
- [Parsing](#parsing)
- [List(Arrays)](#list-arrays)
- [Lambda Functions](#lambda-functions)
- [Null-aware Operators](#null-aware-operators)
- [Collections Literals](#collections-literals)
- [Arrow Syntax](#arrow-syntax)
- [Iterations](#iterations)
- [Map](#map)
- [Variables](#variables)
- [Class](#class)
- [Properties](#properties)
- [Getters and Setters](#getters-setters)
- [Optional Positional Parameters](#postional-parameters)
- [Redirecting Constructors](#redirecting-constructors)



## String interpolation

Every language has it's own way of interpolating two ore more words or characters. In dart, you can put value of an expression inside a string as follows:

###  Example

 ```dart
    int x=6;
    int y=2;
    String sum = '${x+y}';          // result is 8
    String subtraction = '${x-y}';  // result is 4
    String upperCase = '${"hello".toUpperCase()}'; // result is HELLO
    String concatXY = '$x$y'; // result is '62'
 ```
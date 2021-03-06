﻿EasyCSVNet 1.0.1

A free and easy CSV importing and exporting library with XML definition support written in VB.Net

Please see sources, samples & documentation at: https://github.com/ADeBuen/EasyCSVNet

Written by Alex de Buen Lapena (alex.debuen@gmail.com) - Sep 8th, 2017
GNU General Public License version 3 (https://opensource.org/licenses/GPL-3.0)

EasyCSVNet is a simple and lightweight solution written entirely in VB.Net to deal with CSV-like ('comma-separated-value' plain text) files in a comfortable way.
It allows to import CSV files into high level business layer objects' lists without effort, as the OCM ('Object-to-CSV' Mapping) schemata are defined in separated XML files.
All type casting and field-to-attribute mapping work involved underneath is carried away transparently by the library by means of reflection. 
Also, clear and detailed error messages are thrown inside runtime exceptions during CSV parsing whenever a syntactic flaw is found in importing an eventually malformed CSV file. Really useful when typically working with many lines CSV files! 
More over, simple exporting classes are provided, which allow an easy implementation of the reverse-way exportation process from object to CSV if needed.
In sum, a minimally invasive and more 'aseptic' alternative approach to more conventional boilerplate line-by-line parsing strategies, created to save time and effort to developers, who can then concentrate on other parts of their projects involving real business logic.

Library binaries in package form are also available to download/install from NuGet at https://www.nuget.org/packages/easycsvnet
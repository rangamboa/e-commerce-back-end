# e-Commerce Back End 📊

This application is a mock-up of an e-commerce site back end, combining an Express.js API with Sequelize to interact with a MySQL database and tested with Insomnia.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

  1. [Description](#description)
  2. [License](#license)
  3. [Installation](#installation)
  4. [Usage](#usage)
  5. [Contribution](#contribution)
  6. [Testing](#testing)
  7. [Questions](#questions)
  8. [License](#license)
  
## Description

e-Commerce Back End is a robust inventory tracking application launched by the command-line that integrates an API generated by Express.js, which manages a database created by Sequelize and tested in Insomnia through user input in JSON format.

## Walkthrough

Here is a link to a [walkthrough video on YouTube](https://youtu.be/c6b4eGJRLBk) to show the application functionality in both VS Code and Insomnia.

## Installation

This project uses MySQL, sequelize, node Express and npm. Install these packages if you do not have them on your local machine. 

## Usage

``schema.sql`` must be sourced through the MySQL prompt prior to launching the application. Use ``npm run seed`` to then seed the generated database in the command line, then  ``node .\index.js`` to launch this application. I used [Insomnia](https://insomnia.rest/) to visualize, test and troubleshoot the API routes I built.

## Contribution

Pleae feel free to contribute and always follow the [Contributor Covenant](http://contributor-covenant.org/version/1/3/0/):

* Fork the reposition
* Create a new branch (``git checkout -b improve-feature``)
* Make, add and commit the appropriate changes in the files
* Push to the branch (``git push origin improve-feature``)
* Create a Pull Request

Thanks!

## Testing

Testing of code was mostly conducted in Insomnia; error messages were parsed there and in the VS Code command line. My main problem has been trying to debug the "update product" route; the database does not update with the new values I pass through in the PUT. I also need to continue to work on the product tag functionality; as seen in the walkthrough video those were not filled out.

## Questions

Please don't hesitate to reach out to me via GitHub or email if you've got any questions! Thank you for checking out my code.

* [GitHub Profile](https://github.com/rangamboa) 

* [Email](mailto:rangamboa@gmail.com)

## License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

---
@2021 Ran Gamboa - ``thanks for reading!``

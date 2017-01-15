## Synopsis

This is a command line helper to create React components.

## Code Example

### Command Line
    node app.js -c ComponentName

### Output
Creates a file in the working directory:

    ComponentName.js



    import React from 'react'

    var ComponentName = React.createClass({
      render: function(){
       return (
          <div >
            <h1>ComponentName</h1>
          </div>
        )
      }
    })

    export default ComponentName


## Motivation

I created this while learning react because I became frustrated typing the same boilerplate for every component, often introducing typos as well.

I searched for a similar command line generator for React but could not find one, so I started coding.

Trot saves on repeated keystrokes, simplify project development and reduce the time required for creating a working app.
By using this command line interface I was able to think about coding rather than think about syntax and versions (ES5 vs ES6). '

I am still relatively new to JavaScript, Node and React development.  I'm still learning ES6. if you have suggestions for improvements, features or note any errors or corrections, please submit an issue or fork the repo and submit a pull request. 

## Installation

    npm install trot


## Contributors

Contributions to this project are welcome and will be recognized here,
feel free to create an issue with suggestions for templates or command line flags to include,
additional functionality to speed React development.

Open an issue or fork the rep here [Trot on Github](https://github.com/AdventureBear/trot "Trot on Github")


## License

A short snippet describing the license (MIT, Apache, etc.)
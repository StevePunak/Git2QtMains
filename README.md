# libgit2qt

## Description
This library provides C++/Qt language bindings to libgit2. 
In large part, it is a port of the [libgit2sharp](https://github.com/libgit2/libgit2sharp) which provided a nice OO object model to work from.

## Building

**NOTE:** This project requires Qt 6.

### Just The Library

Get the code: 

    `git clone https://github.com/StevePunak/libgit2qt.git` 

1. Start Qt Creator
2. Open the CMakeLists.txt in the root folder. 
3. Select a kit to build.
4. Build the library

### The Library and a Program With Examples
There is a submodules project which includes the library and a program with some examples. 
This is probably the best way to get started for most people as there is currently no documentation (working on it).

1. Get the code:

    `git clone https://github.com/StevePunak/Git2QtMains.git` 
    
2. Get the test repository:

    `git clone https://github.com/StevePunak/GitTesting.git` 

3. Start Qt Creator
4. Open the CMakeLists.txt in the root folder. 
5. Select a kit to build.
6. Build the project
7. Run the example program with the following parameters    

    `auto --local-path /path/to/test-repository/GitTesting`
    
![To run in the debugger](/assets/ss-run-config.png)
    




## Usage
Use examples liberally, and show the expected output if you can. It's helpful to have inline the smallest example of usage that you can demonstrate, while providing links to more sophisticated examples if they are too long to reasonably include in the README.

## Support
Tell people where they can go to for help. It can be any combination of an issue tracker, a chat room, an email address, etc.

## Roadmap
If you have ideas for releases in the future, it is a good idea to list them in the README.

## Contributing
State if you are open to contributions and what your requirements are for accepting them.

For people who want to make changes to your project, it's helpful to have some documentation on how to get started. Perhaps there is a script that they should run or some environment variables that they need to set. Make these steps explicit. These instructions could also be useful to your future self.

You can also document commands to lint the code or run tests. These steps help to ensure high code quality and reduce the likelihood that the changes inadvertently break something. Having instructions for running tests is especially helpful if it requires external setup, such as starting a Selenium server for testing in a browser.

## Authors and acknowledgment
Show your appreciation to those who have contributed to the project.

## License
For open source projects, say how it is licensed.

## Project status
If you have run out of energy or time for your project, put a note at the top of the README saying that development has slowed down or stopped completely. Someone may choose to fork your project or volunteer to step in as a maintainer or owner, allowing your project to keep going. You can also make an explicit request for maintainers.

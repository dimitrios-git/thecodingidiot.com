# tci-ircserv
A simple IRC server written in C++.

IRC, which stands for Internet Relay Chat, is a form of real-time text messaging
or synchronous conferencing. It's primarily used for group communication in
discussion forums, called channels, but also allows one-on-one communication via
private messages as well as chat and data transfers via Direct Client-to-Client
connections. More information about IRC can be found on
[Wikipedia](https://en.wikipedia.org/wiki/Internet_Relay_Chat).

## Usage
To start the server, you need to compile the source code and run the executable.

### Compilation
To compile the source code, you need to have a C++ compiler installed on your
system. The server uses the C++98 standard to ensure compatibility with older
systems.

#### Linux
On Linux, you can use the GNU Compiler Collection (GCC) to compile the source
code. To do so, navigate to the root directory of the project and run the
following command in your terminal:

```bash
g++ -std=c++98 -o tci-ircserv src/*.cpp
```

This will compile the source code and create an executable called `tci-ircserv`
in the root directory of the project.

#### Windows
On Windows, you can use the MinGW-w64 project to compile the source code. You can
download the MinGW-w64 installer from the
[official website](https://sourceforge.net/projects/mingw-w64/).

After installing MinGW-w64, you can use the `g++` command to compile the source
code. To do so, navigate to the root directory of the project and run the
following command in your Command Prompt:

```cmd
g++ -std=c++98 -o tci-ircserv src\*.cpp
```

This will compile the source code and create an executable called `tci-ircserv`
in the root directory of the project.

### macOS
On macOS, you can use the Clang compiler to compile the source code. To do so,
navigate to the root directory of the project and run the following command in
your terminal:

```bash
clang++ -std=c++98 -o tci-ircserv src/*.cpp
```

This will compile the source code and create an executable called `tci-ircserv`
in the root directory of the project.

### Running the server
To run the server, you need to execute the compiled executable. To do so,
navigate to the root directory of the project and run the following command in
your terminal:

```bash
./tci-ircserv
```

This will start the server and listen for incoming connections on the default
IRC port (6667).

## Contributing
If you want to contribute to the project, you can fork the repository and submit
a pull request with your changes. Please make sure to follow the
[Contribution Guidelines](CONTRIBUTING.md) when submitting your pull request.

## License
This project is licensed under the MIT License. For more information, please
refer to the [LICENSE](LICENSE) file.


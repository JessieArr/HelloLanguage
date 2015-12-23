Downloaded Rust Stable 1.5 from here: https://www.rust-lang.org/downloads.html#win-foot

Chose the MSVC ABI which uses the Visual Studio linker (link.exe) to do compile-time linking.

Be sure you have the Visual C++ Components installed for Visual Studio or you will get the error:
"could not exec the linker 'link.exe' "

After installing them, things worked fine. Rust lang's bin folder is automatically added to the 
PATH when installed, too, so rustc works everywhere.
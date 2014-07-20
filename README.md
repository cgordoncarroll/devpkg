What is devpkg?
====
Devpkg is a simple C program that installs other software. I made it specifically for this book as a way to teach you how a real software project is structured, and also how to reuse other people's libraries. It uses a portability library called The Apache Portable Runtime (APR) that has many handy C functions which work on tons of platforms, including Windows. Other than that, it just grabs code from the internet (or local files) and does the usual ./configure ; make ; make install every programmer does.

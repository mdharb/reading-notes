# FUNCTIONAL PROGRAMMING

## Functional Programming Concepts

***

1. **What is functional programming?**
   * A programming paradigm a style of building the structure and elements of computer programs that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.

2. **What is a pure function and how do we know if something is a pure function?**
   * It returns the same result if given the same arguments (it is also referred as deterministic).
   * It does not cause any observable side effects.

3. **What are the benefits of a pure function?**
   * The code’s definitely easier to test. We don’t need to mock anything.

4. **What is immutability?**
   * When data is immutable, its state cannot change after it’s created.

5. **What is Referential transparency?**
   * A function consistently yields the same result for the same input.

## Node JS - Modules and require()

***

1. **What is a module?**
   * a simple or complex functionality organized in single or multiple JavaScript files which can be reused throughout the Node. js application

2. **What does the word ‘require’ do?**
   * is the easiest way to include modules that exist in separate files. It reads a JavaScript file, executes the file, and then proceeds to return the exports object.

3. **How do we bring another module into the file the we are working in?**
   * To include functions defined in another file in Node.js, we need to import the module. we will use the require keyword at the top of the file.

4. **What do we have to do to make a module available?**
   * Publish the module to NPM (Node Package Manager).

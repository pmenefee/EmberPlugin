## Rules
1. Always Add #pragma once as the first line header file.
2. C++ loves semi coolons and the end of code statements
3. A C++ class contains access modifiers (public, protected, private)
4. C++ needs two types of file - a header (.hpp) and a source file (.cpp)
5. To expose out class to the editor, inherit from a godot class
6. Always use the GDCLASS macro in the class you want to expose to Godot
7. Use "protected: static void_bind_methods()"
8. Use "ClassDB::bind_method()" to expose methods
9. Register your class inside "register_types.cpp"
10. Use ADD_PROPERTY macro to expose properties to Godot engine.


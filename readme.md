# glslang-format

`glslang-format` is a code formatter for GLSL and HLSL programs, it changes the appearance of a GLSL/HLSL program by inserting or deleting whitespace. 

`glslang-format` is totally based on the KhronosGroup's glslang project to fit the GLSL/HLSL syntax well, and `glslang-format` only understand the syntax of shader languages. 

If you apply `glslang-format` twice on the same file, the file should stay unchanged at the second time, and the AST generated from the original program and the formatted program should be same. 
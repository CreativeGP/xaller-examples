# xaller-examples
The web application examples written in Xaller.

There are two web application examples, calculator and unit converter.

## Directory Structure
- calc
  - Calculator written in Xaller
- unicon
  - Unit converter written in Xaller
- lib
  - Libraries used in the two applications and library itself.
  
## Explanation of unknown files and procedure of Xaller compilation

The compilation of Xaller follows a procedure as follws:
- Pre-compile the source file and output a .pcp.
- Transpile the .pcp file with Xaller transpiler and output a .js and a .html which loads the .js file inside.

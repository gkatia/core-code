## core-code
Core Code Bootcamp

Tuesday 11/01
1. Compilation and interpretation
2. Interpreted. The Java source code first compiled into a binary byte code using Java compiler, then this byte code runs on the JVM (Java Virtual Machine), which is a software based interpreter. So Java is considered as both interpreted and compiled.
3. X
4. X
5. It helps solving problems and it doesn´t have strict syntax and rigid coding patterns, it´s similar to the human language so we can understand it faster.
6. X
7. X
8. Flowcharts are important because they help us to study and understand difficult problems when we see them in simple diagrams
9. X

Wednesday
1. X
2. Binary: 11111001110 / hexadecimal: 7ce / decimal: 1998
3. Binary: 1100101011111110 / hexadecimal: cafe
4. X
5.

3rd Week
Thursday 27/01

3. function list(names){
    var result;
    if (names.length === 0) { result= ''; }
    else if(names.length === 1) { result = names.map(p=>p.name).join(); }
    else {
      result = names.map(p=>p.name);
      result = result.slice (0, names.length-1).join(', ')+' & '+names[names.length-1].name;
    }
    return result;
  }

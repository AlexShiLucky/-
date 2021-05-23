# 指令instruction、伪指令pseudo-instruction、伪操作directive区别

- 指令instruction

  机器指令,简称指令,最终在CPU上执行的指令,一条指令通过汇编器汇编后还是指令本身;

- 伪指令pseudo-instruction

  汇编器伪指令,简称伪指令,一条伪指令通过汇编器编译后对应一条或多条机器指令;

- 伪操作directive

  汇编器伪操作,简称伪操作,汇编伪操作通过汇编器编译后不产生CPU指令,主要用于指导汇编器工作.

**指令(instruction)与汇编伪指令(pseudo-instruction)的区别在于:**
    1条instruction与1条机器指令对应,而编译器会把1条pseudo-instruction编译为1条或多条机器指令.

**汇编伪操作(directive)与汇编伪指令(pseudo-instruction)的区别在于:**
    注意:千万别把汇编伪操作(directive)与汇编伪指令(pseudo-instruction)弄混了,directive不会被编译器编译为机器指令,但pseudo-instruction会被编译成1条或多条机器指令.


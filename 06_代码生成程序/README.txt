第六次作业，代码生成。可以生成中间代码（如四元式），也可以生成目标代码。时间关系，当时做时，目标代码生成还未写完，所以提交的版本是生成中间代码。

在编译原理的书上，语义分析与代码生成是两个模块，但是实际做时，这两部分是一个东西，因为光做语义分析不生成代码就等于什么也没做。这里说的“代码生成”是指生成中间代码。

没有直接写成生成目标代码，而是先生成中间代码，是为了以后编译优化。但是我的目标代码生成程序一直在 Debug，以至于我到后来没有时间写编译优化了，只做了个临时寄存器池。这也算是一个小遗憾吧。
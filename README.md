# ECMAScript 2015 规格

**所有数据取自ECMA官方规格, 地址:**
[http://www.ecma-international.org/ecma-262/6.0/#sec-scope](http://www.ecma-international.org/ecma-262/6.0/#sec-scope)

本人英语学渣, 翻译可能不够标准, 所以贴了原文在下方

## 1. Scope 规范
本标准定义了ECMAScript 2015通用编程语言。
> This Standard defines the ECMAScript 2015 general purpose programming language.

## 2. Conformance 一致性
如果你想使用ECMAScript规范, 必须
- 提供和支持本规格中描述的所有类型，值，对象，属性，函数和程序语法和语义。  
- 与Unicode标准、版本5.1.0或更高版本和ISO/IEC 10646一致的源文本输入。如果未采用所指定的ISO/IEC 10646-1子集，则假定为Unicode ，ISO/IEC 10646。
- 提供了一个应用程序接口，它支持需要适应不同人类语言和国家使用的语言和文化约定的程序，必须实现由EMA-402的最新版本定义的接口。
- 可以提供超出本规格描述的附加类型、值、对象、属性和函数。尤其是ECMAScript的一致实现可以提供本规范中未描述的属性，以及在本规范中描述的对象的那些属性的值。
- 可以支持本规范中未描述的程序和正则表达式语法。尤其是ECMAScript的一致性实现可以支持程序语法，该程序语法使用本规范的 11.2.2.2 中列出的“未来保留字”。
- 禁止使用第16.1条中被列为禁止扩展的任何扩展。

> A conforming implementation of ECMAScript must provide and support all the types, values, objects, properties, functions, and program syntax and semantics described in this specification.   
> A conforming implementation of ECMAScript must interpret source text input in conformance with the Unicode Standard, Version 5.1.0 or later and ISO/IEC 10646. If the adopted ISO/IEC 10646-1 subset is not otherwise specified, it is presumed to be the Unicode set, collection 10646.  
> A conforming implementation of ECMAScript that provides an application programming interface that supports programs that need to adapt to the linguistic and cultural conventions used by different human languages and countries must implement the interface defined by the most recent edition of ECMA-402 that is compatible with this specification.   
> A conforming implementation of ECMAScript may provide additional types, values, objects, properties, and functions beyond those described in this specification. In particular, a conforming implementation of ECMAScript may provide properties not described in this specification, and values for those properties, for objects that are described in this specification.    
> A conforming implementation of ECMAScript may support program and regular expression syntax not described in this specification. In particular, a conforming implementation of ECMAScript may support program syntax that makes use of the “future reserved words” listed in subclause 11.6.2.2 of this specification.    
> A conforming implementation of ECMAScript must not implement any extension that is listed as a Forbidden Extension in subclause 16.1.

## 3. Normative references 规范参考文献
以下参考文件对于本规范的应用是必不可少的(必须实现)。 凡是注日期的引用文件，仅注明引用的版本。 凡是不注日期的引用文件，其最新版本（包括所有修改单）适用于本文件。

ISO/IEC 10646:2003: 信息技术 - 通用多字节编码字符集（UCS）及修正案1：2005，修订版2：2006，修订版3：2008和修订版4：2008，以及其他修订和更正或后续修订

ECMA-402，ECMAScript 2015国际化API规范。
http://www.ecma-international.org/publications/standards/Ecma-402.htm

ECMA-404，JSON数据交换格式。
http://www.ecma-international.org/publications/standards/Ecma-404.htm


> The following referenced documents are indispensable for the application of this document. For dated references, only the edition cited applies. For undated references, the latest edition of the referenced document (including any amendments) applies.      
> ISO/IEC 10646:2003: Information Technology – Universal Multiple-Octet Coded Character Set (UCS) plus Amendment 1:2005, Amendment 2:2006, Amendment 3:2008, and Amendment 4:2008, plus additional amendments and corrigenda, or successor        
> ECMA-402, ECMAScript 2015 Internationalization API Specification.
http://www.ecma-international.org/publications/standards/Ecma-402.htm   
> ECMA-404, The JSON Data Interchange Format.
http://www.ecma-international.org/publications/standards/Ecma-404.htm

## [4. Overview](./Overview/README.md)

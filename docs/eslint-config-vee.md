# 团队eslint配置

## 默认规则

```json
{
    // Possible Errors
    "for-direction": 2,
    "getter-return": 2,
    "no-async-promise-executor": 2,
    "no-compare-neg-zero": 2,
    "no-case-declarations": 2,
    "no-class-assign": 2,
    "no-cond-assign": 2,
    "no-constant-condition": 1,
    "no-control-regex": 2,
    "no-debugger": 0,
    "no-dupe-args": 2,
    "no-dupe-keys": 2,
    "no-duplicate-case": 2,
    "no-empty": 2,
    "no-empty-character-class": 0,
    "no-ex-assign": 2,
    "no-extra-boolean-cast": 0,
    "no-extra-semi": 1,
    "no-func-assign": 1,
    "no-inner-declarations": 2,
    "no-invalid-regexp": 2,
    "no-irregular-whitespace": 1,
    "no-misleading-character-class": 0,
    "no-obj-calls": 2,
    "no-prototype-builtins": 0,
    "no-regex-spaces": 1,
    "no-sparse-arrays": 1,

    // Best Practices
    "no-empty-pattern": 1,
    "no-fallthrough": 2,
    "no-global-assign": 2,
    "no-octal": 0,
    "no-redeclare": 2,
    "no-self-assign": 0,
    "no-unexpected-multiline": 1,
    "no-unreachable": 2,
    "no-unsafe-finally": 1,
    "no-unsafe-negation": 0,
    "no-unused-labels": 0,
    "no-useless-catch": 0,
    "no-useless-escape": 0,
    "no-with": 2,
    "use-isnan": 2,
    "valid-typeof": 0,
    
    // Variables
    "no-delete-var": 0,
    "no-shadow-restricted-names": 2,
    "no-undef": 2,
    "no-unused-vars": 2,

    // Stylistic Issues
    "no-mixed-spaces-and-tabs": 0,

    // ECMAScript 6
    "constructor-super": 1,
    "no-const-assign": 2,
    "no-dupe-class-members": 2,
    "no-new-symbol": 0,
    "no-this-before-super": 2,
    "require-yield": 2
}
```

| 规则名称        | 错误级别           | 说明  |
| :------------- |:-------------| :-----|
| [for-direction](https://eslint.org/docs/rules/for-direction) | error | for 循环的方向要求必须正确 |
| [getter-return](https://eslint.org/docs/rules/getter-return)      | error | getter必须有返回值 |
| [no-async-promise-executor](https://eslint.org/docs/rules/no-async-promise-executor)| error | 禁止使用异步函数作为 Promise executor |
| [no-compare-neg-zero](https://eslint.org/docs/rules/no-compare-neg-zero) | error | 禁止与 -0 进行比较 |
| [no-class-assign](https://eslint.org/docs/rules/no-class-assign) | error | 禁止修改类声明的变量 |
| [no-cond-assign](https://eslint.org/docs/rules/no-cond-assign) | error | 禁止条件表达式中出现赋值操作符 |
| [no-constant-condition](https://eslint.org/docs/rules/no-constant-condition) | warn | 不建议在条件中使用常量表达式 |
| [no-control-regex](https://eslint.org/docs/rules/no-control-regex) | error |  |
| [no-debugger](https://eslint.org/docs/rules/no-debugger) | off | 允许使用debugger |
| [no-dupe-args](https://eslint.org/docs/rules/no-dupe-args) | error | 禁止 function 定义中出现重名参数 |
| [no-dupe-keys](https://eslint.org/docs/rules/no-dupe-keys) | error | 禁止对象字面量中出现重复的 key |
| [no-duplicate-case](https://eslint.org/docs/rules/no-duplicate-case) | error | 禁止出现重复的 case 标签 |
| [no-empty](https://eslint.org/docs/rules/no-empty) | error | 禁止出现空语句块 |
| [no-empty-character-class](https://eslint.org/docs/rules/no-empty-character-class) | off | 允许在正则表达式中使用空字符集 |
| [no-ex-assig](https://eslint.org/docs/rules/no-ex-assig) | error | 禁止对 catch 子句的参数重新赋值 |
| [no-extra-boolean-cast](https://eslint.org/docs/rules/no-extra-boolean-cast) | off | 允许显式布尔转换 |
| [no-extra-semi](https://eslint.org/docs/rules/no-extra-semi) | warn | 警告不必要的分号 |
| [no-func-assign](https://eslint.org/docs/rules/no-func-assign) | warn | 不建议对 function 声明重新赋值 |
| [no-inner-declarations](https://eslint.org/docs/rules/no-inner-declarations) | error | 禁止对 function 声明重新赋值 |
| [no-invalid-regexp](https://eslint.org/docs/rules/no-invalid-regexp) | error | 禁止 RegExp 构造函数中存在无效的正则表达式字符串 |
| [no-irregular-whitespace](https://eslint.org/docs/rules/no-irregular-whitespace) | warn | 提示不规则的空白 |
| [no-misleading-character-class](https://eslint.org/docs/rules/no-misleading-character-class) | off | 允许在字符类语法中出现由多个代码点组成的字符 |
| [no-obj-calls](https://eslint.org/docs/rules/no-obj-calls) | error | 禁止把全局对象作为函数调用 |
| [no-prototype-builtins](https://eslint.org/docs/rules/no-prototype-builtins) | off | 允许直接调用 Object.prototypes 的内置属性 |
| [no-regex-spaces](https://eslint.org/docs/rules/no-regex-spaces) | warn | 提示正则表达式字面量中出现多个空格 |
| [no-sparse-arrays](https://eslint.org/docs/rules/no-sparse-arrays) | warn | 不建议使用稀疏数组 |
| [no-empty-pattern](https://eslint.org/docs/rules/no-empty-pattern) | warn | 不建议使用空解构模式 |
| [no-fallthrough](https://eslint.org/docs/rules/no-fallthrough) | error | 禁止 case 语句落空 |
| [no-global-assign](https://eslint.org/docs/rules/no-global-assign) | error | 禁止对原生对象或只读的全局对象进行赋值 |
| [no-octal](https://eslint.org/docs/rules/no-octal) | off | 允许八进制字面量 |
| [no-redeclare](https://eslint.org/docs/rules/no-redeclare) | error | 禁止多次声明同一变量 |
| [no-self-assign](https://eslint.org/docs/rules/no-self-assign) | off | 允许自我赋值 |
| [no-unexpected-multiline](https://eslint.org/docs/rules/no-unexpected-multiline) | warn | 提示令人困惑的多行表达式 |
| [no-unreachable](https://eslint.org/docs/rules/no-unreachable) | error | 禁止在 return、throw、continue 和 break 语句之后出现不可达代码 |
| [no-unsafe-finally](https://eslint.org/docs/rules/no-unsafe-finally) | error | 提示在 finally 语句块中出现 return、throw、break 和 continue 语句 |
| [no-unsafe-negation](https://eslint.org/docs/rules/no-unsafe-negation) | off | 允许对关系运算符的左操作数使用否定操作符 |
| [no-unused-labels](https://eslint.org/docs/rules/no-unused-labels) | off | 允许出现未使用过的标签 |
| [no-useless-catch](https://eslint.org/docs/rules/no-useless-catch) | off | 允许不必要的 catch 子句 |
| [no-useless-escape](https://eslint.org/docs/rules/no-useless-escape) | off | 允许不必要的转义字符 |
| [no-with](https://eslint.org/docs/rules/no-with) | error | 禁用 with 语句 |
| [use-isnan](https://eslint.org/docs/rules/use-isnan) | error | 检测NaN必须使用isNaN |
| [valid-typeof](https://eslint.org/docs/rules/valid-typeof) | off | 关闭 typeof 表达式与有效的字符串进行比较 |
| [no-delete-var](https://eslint.org/docs/rules/no-delete-var) | off | 允许删除变量 |
| [no-shadow-restricted-names](https://eslint.org/docs/rules/no-shadow-restricted-names) | error | 禁止将标识符定义为受限的名字 |
| [no-undef](https://eslint.org/docs/rules/no-undef) | error | 禁用未声明的变量，除非它们在 /*global */ 注释中被提到 |
| [no-unused-vars](https://eslint.org/docs/rules/no-unused-vars) | error | 禁止出现未使用过的变量 |
| [no-mixed-spaces-and-tabs](https://eslint.org/docs/rules/no-mixed-spaces-and-tabs) | off | 允许空格和 tab 的混合缩进 |
| [constructor-super](https://eslint.org/docs/rules/constructor-super) | warn | 建议在构造函数中有 super() 的调用 |
| [no-const-assign](https://eslint.org/docs/rules/no-const-assign) | error | 禁止修改 const 声明的变量 |
| [no-dupe-class-members](https://eslint.org/docs/rules/no-dupe-class-members) | error | 禁止类成员中出现重复的名称 |
| [no-new-symbol](https://eslint.org/docs/rules/no-new-symbol) | off | 允许 Symbolnew 操作符和 new 一起使用 |
| [no-this-before-super](https://eslint.org/docs/rules/no-this-before-super) | error | 禁止在构造函数中，在调用 super() 之前使用 this 或 super |
| [require-yield](https://eslint.org/docs/rules/require-yield) | error | 要求 generator 函数内有 yield |
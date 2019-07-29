# tslint-config-ivweb 规则

## 规则列表

### TypeScript 相关

<table>
    <thead>
        <tr>
            <th>名称</th>
            <th>错误级别</th>
            <th>描述</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/array-type/">array-type</a></td>
            <td>off</td>
            <td>限制<strong style="color:#267fd9; font-weight:600;">必须</strong>使用 <code>T[]</code> 或 <code>Array&lt;T&gt;</code> 之中的一种来定义数组的类型</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/ordered-imports/">ordered-imports</a></td>
            <td>off</td>
            <td><code>import</code> <strong style="color:#267fd9; font-weight:600;">必须</strong>排序</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/eofline/">eofline</a></td>
            <td>off</td>
            <td>文件最后一行<strong style="color:#267fd9; font-weight:600;">必须</strong>有一个空行</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-console/">no-console</a></td>
            <td>off</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用 <code>console</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/interface-name/">interface-name</a></td>
            <td>off</td>
            <td>接口名称<strong style="color:#267fd9; font-weight:600;">必须</strong>已 <code>I</code> 开头</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/object-literal-sort-keys/">object-literal-sort-keys</a></td>
            <td>off</td>
            <td>对象字面量<strong style="color:#267fd9; font-weight:600;">必须</strong>按 <code>key</code> 排序</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-var-keyword/">no-var-keyword</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用 <code>var</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/align/">align</a></td>
            <td>error</td>
            <td>变量定义需要竖向对其</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/class-name/">class-name</a></td>
            <td>error</td>
            <td>类名与接口名<strong style="color:#267fd9; font-weight:600;">必须</strong>为驼峰式</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/comment-format/">comment-format</a></td>
            <td>error</td>
            <td>限制单行注释的规则, 注释符号后面需要加空格</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/curly/">curly</a></td>
            <td>error</td>
            <td><code>if</code> 后面<strong style="color:#267fd9; font-weight:600;">必须</strong>有 <code>{</code>，除非是单行 <code>if</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/forin/">forin</a></td>
            <td>off</td>
            <td><code>for in</code> 内部<strong style="color:#267fd9; font-weight:600;">必须</strong>有 <code>hasOwnProperty</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/indent/">indent</a></td>
            <td>error</td>
            <td>一个缩进<strong style="color:#267fd9; font-weight:600;">必须</strong>用四个空格替代</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/jsdoc-format/">jsdoc-format</a></td>
            <td>off</td>
            <td>注释<strong style="color:#267fd9; font-weight:600;">必须</strong>符合 JSDoc 规范</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/label-position/">label-position</a></td>
            <td>off</td>
            <td>只允许在 <code>do</code>, <code>for</code>, <code>while</code> 或 <code>switch</code> 中使用 <code>label</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/max-line-length/">max-line-length</a></td>
            <td>error</td>
            <td>限制每行字符数(150)</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/member-ordering/">member-ordering</a></td>
            <td>error</td>
            <td>指定类成员的排序规则(目前只需要static优先)</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/new-parens/">new-parens</a></td>
            <td>error</td>
            <td><code>new</code> 后面只<strong style="color:#267fd9; font-weight:600;">必须</strong>有一个空格</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-any/">no-any</a></td>
            <td>off</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用 <code>any</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-arg/">no-arg</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用 <code>arguments.callee</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-bitwise/">no-bitwise</a></td>
            <td>off</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用位运算</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-conditional-assignment/">no-conditional-assignment</a></td>
            <td>true</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>在分支条件判断中有赋值操作</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-consecutive-blank-lines/">no-consecutive-blank-lines</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>连续超过三行空行</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-construct/">no-construct</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用 <code>new</code> 来生成 <code>String</code>, <code>Number</code> 或 <code>Boolean</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-debugger/">no-debugger</a></td>
            <td>off</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用 <code>debugger</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-duplicate-variable/">no-duplicate-variable</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>出现重复的变量定义或函数参数名</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-empty-interface/">no-empty-interface</a></td>
            <td>off</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>定义空的接口</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-eval/">no-eval</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用 <code>eval</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-internal-module/">no-internal-module</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用 <code>module</code> 来定义命名空间</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-namespace/">no-namespace</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用 <code>namespace</code> 来定义命名空间,允许使用 declare namespace ... {} 来定义外部命名空间</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-reference/">no-reference</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用三斜线引入模块 <code>/// &lt;reference path="foo" /&gt;</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-shadowed-variable/">no-shadowed-variable</a></td>
            <td>off</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>变量名与上层作用域内的定义过的变量重复</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-string-literal/">no-string-literal</a></td>
            <td>off</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>出现 <code>foo['bar']</code>，<strong style="color:#267fd9; font-weight:600;">必须</strong>写成 <code>foo.bar</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-switch-case-fall-through/">no-switch-case-fall-through</a></td>
            <td>error</td>
            <td><code>switch</code> 的 <code>case</code> <strong style="color:#267fd9; font-weight:600;">必须</strong> <code>return</code> 或 <code>break</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-trailing-whitespace/">no-trailing-whitespace</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>行尾有空格</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-unused-expression/">no-unused-expression</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>无用的表达式</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-use-before-declare/">no-use-before-declare</a></td>
            <td>off</td>
            <td>变量<strong style="color:#267fd9; font-weight:600;">必须</strong>先定义后使用</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-var-requires/">no-var-requires</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用 <code>require</code> 来引入模块</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/one-line/">one-line</a></td>
            <td>error</td>
            <td><code>if catch else finally</code> 后的 <code>{</code> <strong style="color:#db5757; font-weight:600;">禁止</strong>换行</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/one-variable-per-declaration/">one-variable-per-declaration</a></td>
            <td>error</td>
            <td>变量申明<strong style="color:#267fd9; font-weight:600;">必须</strong>每行一个，<code>for</code> 循环的初始条件中除外</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/quotemark/">quotemark</a></td>
            <td>error</td>
            <td><strong style="color:#267fd9; font-weight:600;">必须</strong>使用单引号，jsx 中<strong style="color:#267fd9; font-weight:600;">必须</strong>使用双引号</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/radix/">radix</a></td>
            <td>error</td>
            <td><code>parseInt</code> <strong style="color:#267fd9; font-weight:600;">必须</strong>传入第二个参数</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/semicolon/">semicolon</a></td>
            <td>error</td>
            <td>行尾<strong style="color:#267fd9; font-weight:600;">必须</strong>有分号</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/switch-default/">switch-default</a></td>
            <td>error</td>
            <td><code>switch</code> 语句<strong style="color:#267fd9; font-weight:600;">必须</strong>有 <code>default</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/triple-equals/">triple-equals</a></td>
            <td>error</td>
            <td><strong style="color:#267fd9; font-weight:600;">必须</strong>使用 <code>===</code> 或 <code>!==</code>，<strong style="color:#db5757; font-weight:600;">禁止</strong>使用 <code>==</code> 或 <code>!=</code>,null除外</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/typedef/">typedef</a></td>
            <td>off</td>
            <td>变量、函数返回值、函数参数等<strong style="color:#267fd9; font-weight:600;">必须</strong>要有类型定义</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/typedef-whitespace/">typedef-whitespace</a></td>
            <td>error</td>
            <td>类型定义的冒号前面<strong style="color:#267fd9; font-weight:600;">必须</strong>没有空格，后面<strong style="color:#267fd9; font-weight:600;">必须</strong>有一个空格</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/use-isnan/">use-isnan</a></td>
            <td>off</td>
            <td><strong style="color:#267fd9; font-weight:600;">必须</strong>使用 <code>isNaN(foo)</code> 而不是 <code>foo === NaN</code></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/variable-name/">variable-name</a></td>
            <td>off</td>
            <td>限制变量命名规则</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-irregular-whitespace/">no-irregular-whitespace</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>使用特殊空白符（比如全角空格）</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/member-access/">member-access</a></td>
            <td>off</td>
            <td><strong style="color:#267fd9; font-weight:600;">必须</strong>设置类的成员的可访问性</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-implicit-dependencies/">no-implicit-dependencies</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">禁止</strong>引入 <code>package.json</code> 中不存在的模块</td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-implicit-dependencies/">jsx-no-lambda</a></td>
            <td>error</td>
            <td><strong style="color:#db5757; font-weight:600;">jsx中禁止使用箭头函数</strong></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-implicit-dependencies/">jsx-no-string-ref</a></td>
            <td>off</td>
            <td><strong style="color:#db5757; font-weight:600;">jsx中不可以使用ref字符串</strong></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-implicit-dependencies/">jsx-boolean-value</a></td>
            <td>off</td>
            <td><strong style="color:#db5757; font-weight:600;">jsx中不可以boolean</strong></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-implicit-dependencies/">jsx-wrap-multiline</a></td>
            <td>off</td>
            <td><strong style="color:#db5757; font-weight:600;">jsx中必须要多行</strong></td>
        </tr>
        <tr>
            <td><a href="https://palantir.github.io/tslint/rules/no-implicit-dependencies/">jsx-no-bind</a></td>
            <td>off</td>
            <td><strong style="color:#db5757; font-weight:600;">jsx中不允许使用bind</strong></td>
        </tr>
    </tbody>
</table>
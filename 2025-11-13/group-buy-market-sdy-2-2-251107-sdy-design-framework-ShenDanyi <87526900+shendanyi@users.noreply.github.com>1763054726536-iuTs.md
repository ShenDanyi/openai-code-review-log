根据git diff记录，代码的主要变化如下：

1. 在第6行，将push事件的branches从"2-2-251107-sdy-design-framework-close"修改为"2-2-251107-sdy-design-framework"。
2. 在第9行，将pull_request事件的branches从"2-2-251107-sdy-design-framework-close"修改为"2-2-251107-sdy-design-framework"。

根据这些变化来看，代码中主要是对事件的触发分支进行了调整，将原本带有"-close"后缀的分支改为不带后缀的分支。整体上来说，这些修改看起来符合逻辑，可以被接受。
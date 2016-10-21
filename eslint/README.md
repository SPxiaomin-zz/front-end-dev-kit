# eslint 学习笔记

## 导航

- [学习总结](#学习总结)

- [资料](#资料)

## 学习总结

- 全局安装 eslint:

    - `cnpm i -g eslint`

- 使用:

    - 在每个 project 下执行如下命令就可以在 atom（安装了 linter-eslint） 中正常代码检测了:

        - `eslint --init`

    - 添加 .eslintignore 文件，可以忽略不想 lint 的文件；

    - specifying globals

        - inside file: `/* global var1:true, var2:false */`

        - inside configuration file:

                {
                    "globals": {
                        "var1": true,
                        "var2": false
                    }
                }

## 资料

<http://eslint.org/>

# taro-issue-12505-sample
taro-issue-12505-sample

# 问题

执行 `npm run build:rn`

提示

```
> taro-issue-12505-sample@1.0.0 build:rn
> taro build --type rn

👽 Taro v3.5.5

                    Welcome to Metro!
              Fast - Scalable - Integrated


/Users/lmw/git/taro-issue-12505-sample/node_modules/metro-hermes-compiler/src/emhermesc.js:77
          throw ex;
          ^

RuntimeError: abort(Error: Unable to resolve module @tarojs/components-rn/dist/components/View from /Users/lmw/git/taro-issue-12505-sample/src/pages/index/index.tsx: @tarojs/components-rn/dist/components/View could not be found within the project or in these directories:
  node_modules
> 1 | import { Component, PropsWithChildren } from 'react'
  2 | import { View, Text } from '@tarojs/components'
  3 | import './index.scss'
  4 |). Build with -s ASSERTIONS=1 for more info.
    at process.abort (/Users/lmw/git/taro-issue-12505-sample/node_modules/metro-hermes-compiler/src/emhermesc.js:402:15)
    at process.emit (node:events:525:35)
    at emit (node:internal/process/promises:149:20)
    at processPromiseRejections (node:internal/process/promises:283:27)
    at processTicksAndRejections (node:internal/process/task_queues:96:32)

Node.js v18.7.0
```
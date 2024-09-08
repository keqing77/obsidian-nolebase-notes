## URL 处理

以往我们对地址栏的 URL 需要手动进行字符串分析处理, 比如字符串分割,正则匹配等, 但是现在有了 URL 对象, 可以方便的进行 URL 的解析和处理. 主要会用到这两个API接口: `URL` 和 `URLSearchParams`.

### URL()

获取 s 的值

`new URL('https://www.example.com/about/?s=url').searchParams.get('s');`

### URLSearchParams()

# isosize

> 显示一个 ISO 文件的大小.
> 更多信息: <https://linux.die.net/man/8/isosize>.

- 显示一个 ISO 文件的大小:

`isosize {{path/to/file.iso}}`

- 显示一个 ISO 文件的块数量和块大小:

`isosize --sectors {{path/to/file.iso}}`

- 显示一个 ISO 文件的大小除以给定的数字（仅在未指定 --sectors 时可用）:

`isosize --divisor={{number}} {{path/to/file.iso}}`

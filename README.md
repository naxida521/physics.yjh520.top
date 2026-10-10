# 物理沙盒 · Physics Sandbox

一个**单文件**的网页物理沙盒。在画布上画线、画形状，画出来的东西会变成真正的刚体；再把物理符号（`m` `g` `v` `a` `q` `t` …）拖到一起拼成公式（`mg`、`mv²/2`、`GMm/r²` …），公式就会真的作用到物体上。

- **在线运行**：<https://physics.yjh520.top/>
- **全部内容就是一个 `index.html`**：HTML、CSS、JavaScript（含内联的 Matter.js v0.20.0）都在里面。下载下来双击用浏览器打开即可**离线**运行，不用安装、不用联网。

## 文件

| 文件 | 说明 |
|---|---|
| `index.html` | 全部内容。单文件、离线可跑 |

## 第三方

`index.html` 内联了 [Matter.js](http://brm.io/matter-js/) v0.20.0（MIT License，(c) Liam Brummitt / brm.io），用于绘制体（画出来的墨迹与形状）的刚体物理。

## 许可证

MIT License，见 [LICENSE](LICENSE)。
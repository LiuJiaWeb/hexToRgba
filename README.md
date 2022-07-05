# hexToRgba
hex转为rgba

### github地址：https://github.com/LiuJiaWeb/hexToRgba

### npm地址：https://www.npmjs.com/package/@liujiaweb/hextorgba

### 个人博客：https://liujiaweb.cn/

### 说明
将HEX色值转为rgba形式
#### 安装
npm i @liujiaweb/hextorgba
#### 项目中引入
import hextorgba from '@liujiaweb/hextorgba'
#### 使用
如 const result = hextorgba('#fff') //输出的result值为 'rgba(255,255,255,1)'
传入的参数有两个，第一个参数为hex值，第二个参数为透明度，不传的情况下默认为1
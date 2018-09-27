# img-log
一个简单的将图片转化为base64然后渲染到console.log上的小插件
##### 转化过程
image ---> blob ----> base64 ----> console.log

##### 使用方式
````
npm i img-log -S
````
````
import imgLog from 'img-log';
imgLog('your img path', fontSize); // fontSize决定了图片的大小
````
or
````
var imgLog = require('img-log');
imgLog('your img path', fontSize);
````

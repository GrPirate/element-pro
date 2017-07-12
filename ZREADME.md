# 引入ElementUI

### 安装
	npm install element-ui -S

### 使用 在main.js文件中引入
	import ElementUI from 'element-ui'
	import 'element-ui/lib/theme-default/index.css'
	
	Vue.use(ElementUI)
	...
### 或者
	// or 
	import {
	  Select,
	  Button
	  // ... 
	} from 'element-ui'
	 
	Vue.component(Select.name, Select)
	Vue.component(Button.name, Button)

# 引入less

### 安装less和less-loader
	npm install less -D
	npm install --save-dev less-loader less
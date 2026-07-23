### 一、文本塊
```css
{
	overflow-x: auto;
}
```

### 二、img
```css
{
	max-width: 100%;
	height: auto;
}
```

### 三、table  
在 table 外包一層元素，讓父元素可滾動    
```html
<div class="scrollable"><table>...</table></div>
```

```css
.scrollable {
	overflow-x: auto;
}	
```

### 四、超長單詞   
1. 在單詞中添加 `<wbr>` 
2. 在單詞中添加 ``&shy;``  
3. 使用 css: 
```css
p {
	word-break: break-word;
	overflow-wrap: anywhere;
}
```


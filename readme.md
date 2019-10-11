API

属性  
  
|属性|说明|类型|默认值|  
|---|--|--|--|
|v-model|双向绑定的值，数组中的值需要为String类型|Array|[]|
|placeholder|占位文本|String|-|
|ready-only|给定的初始值仅可读，不能修改或删除|Boolean|false|
|allow-duplicates|是否允许出现重复的值，如果重复则无法添加|Boolean|true|
|before-change|可以用于数据添加前的钩子函数，返回添加的value和index，该函数应该返回true或false，表示是否应用添加。当删除元素的时候，value值为undefined。注意，若需要自定义判断相同元素的时候，就不要设置``allow-duplicates``属性|Function|-|  


方法 

|方法名|说明|返回值|
|--|--|--|
|change|数据改变时触发|操作的值value、下标index、当前值data|  

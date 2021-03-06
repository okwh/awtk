## tab\_button\_t
### 概述
 标签按钮控件。
![image](images/tab_button_t_0.png)

### 函数
<p id="tab_button_t_methods">

| 函数名称 | 说明 | 
| -------- | ------------ | 
| <a href="#tab_button_t_tab_button_cast">tab\_button\_cast</a> |  转换tab_button对象(供脚本语言使用)。 |
| <a href="#tab_button_t_tab_button_create">tab\_button\_create</a> |  创建tab_button对象 |
| <a href="#tab_button_t_tab_button_set_active_icon">tab\_button\_set\_active\_icon</a> |  设置控件的active图标。 |
| <a href="#tab_button_t_tab_button_set_icon">tab\_button\_set\_icon</a> |  设置控件的图标。 |
| <a href="#tab_button_t_tab_button_set_value">tab\_button\_set\_value</a> |  设置控件的值。 |
### 属性
<p id="tab_button_t_properties">

| 名属性称 | 类型 | 说明 | 
| -------- | ----- | ------------ | 
| <a href="#tab_button_t_active_icon">active\_icon</a> | char* |  当前项的图标的名称。 |
| <a href="#tab_button_t_icon">icon</a> | char* |  非当前项的图标的名称。 |
| <a href="#tab_button_t_value">value</a> | bool_t |  值。 |
### 事件
<p id="tab_button_t_events">

| 事件名称 | 类型  | 说明 | 
| -------- | ----- | ------- | 
| EVT\_VALUE\_WILL\_CHANGE | event\_t | 值(激活状态)即将改变事件。 |
| EVT\_VALUE\_CHANGED | event\_t | 值(激活状态)改变事件。 |
#### tab\_button\_cast 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | widget\_t* | tab\_button对象。 |
| widget | widget\_t* | tab\_button对象。 |
<p id="tab_button_t_tab_button_cast"> 转换tab_button对象(供脚本语言使用)。



#### tab\_button\_create 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | widget\_t* | 对象。 |
| parent | widget\_t* | 父控件 |
| x | xy\_t | x坐标 |
| y | xy\_t | y坐标 |
| w | wh\_t | 宽度 |
| h | wh\_t | 高度 |
<p id="tab_button_t_tab_button_create"> 创建tab_button对象



#### tab\_button\_set\_active\_icon 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| widget | widget\_t* | tab\_button对象。 |
| name | char* | 当前项的图标。 |
<p id="tab_button_t_tab_button_set_active_icon"> 设置控件的active图标。



#### tab\_button\_set\_icon 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| widget | widget\_t* | tab\_button对象。 |
| name | char* | 当前项的图标。 |
<p id="tab_button_t_tab_button_set_icon"> 设置控件的图标。



#### tab\_button\_set\_value 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| widget | widget\_t* | tab\_button对象。 |
| value | uint32\_t | 值 |
<p id="tab_button_t_tab_button_set_value"> 设置控件的值。



#### active\_icon 属性
-----------------------
<p id="tab_button_t_active_icon"> 当前项的图标的名称。


* 类型：char*

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 是 |
| 可脚本化   | 是 |
| 可在IDE中设置 | 是 |
| 可在XML中设置 | 是 |
| 支通过widget_get_prop读取 | 是 |
| 支通过widget_set_prop修改 | 是 |
#### icon 属性
-----------------------
<p id="tab_button_t_icon"> 非当前项的图标的名称。


* 类型：char*

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 是 |
| 可脚本化   | 是 |
| 可在IDE中设置 | 是 |
| 可在XML中设置 | 是 |
| 支通过widget_get_prop读取 | 是 |
| 支通过widget_set_prop修改 | 是 |
#### value 属性
-----------------------
<p id="tab_button_t_value"> 值。


* 类型：bool\_t

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 是 |
| 可脚本化   | 是 |
| 可在IDE中设置 | 是 |
| 可在XML中设置 | 是 |
| 支通过widget_get_prop读取 | 是 |
| 支通过widget_set_prop修改 | 是 |

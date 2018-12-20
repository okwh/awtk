## tokenizer\_t
### 概述
 从字符串中解析出一个一个的token。

### 函数
<p id="tokenizer_t_methods">

| 函数名称 | 说明 | 
| -------- | ------------ | 
| <a href="#tokenizer_t_tokenizer_deinit">tokenizer\_deinit</a> |  重置tokenizer。 |
| <a href="#tokenizer_t_tokenizer_has_more">tokenizer\_has\_more</a> |  是否还有下一个token。 |
| <a href="#tokenizer_t_tokenizer_init">tokenizer\_init</a> |  初始化tokenizer对象。 |
| <a href="#tokenizer_t_tokenizer_next">tokenizer\_next</a> |  获取下一个token。 |
| <a href="#tokenizer_t_tokenizer_next_float">tokenizer\_next\_float</a> |  获取下一个token，并转换成float。 |
| <a href="#tokenizer_t_tokenizer_next_int">tokenizer\_next\_int</a> |  获取下一个token，并转换成int。 |
### 属性
<p id="tokenizer_t_properties">

| 名属性称 | 类型 | 说明 | 
| -------- | ----- | ------------ | 
| <a href="#tokenizer_t_cursor">cursor</a> | uint32_t |  当前位置。 |
| <a href="#tokenizer_t_separtor">separtor</a> | char* |  字符串。 |
| <a href="#tokenizer_t_size">size</a> | uint32_t |  字符串的长度。 |
| <a href="#tokenizer_t_str">str</a> | char* |  字符串。 |
### 事件
<p id="tokenizer_t_events">

| 事件名称 | 类型  | 说明 | 
| -------- | ----- | ------- | 
#### tokenizer\_deinit 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | ret\_t | 返回RET\_OK表示成功，否则表示失败。 |
| tokenizer | tokenizer\_t* | tokenizer对象。 |
<p id="tokenizer_t_tokenizer_deinit"> 重置tokenizer。




#### tokenizer\_has\_more 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | bool\_t | 还有下一个token返回TRUE，否则返回FALSE。 |
| tokenizer | tokenizer\_t* | tokenizer对象。 |
<p id="tokenizer_t_tokenizer_has_more"> 是否还有下一个token。




#### tokenizer\_init 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | tokenizer\_t* | tokenizer对象本身。 |
| tokenizer | tokenizer\_t* | tokenizer对象。 |
| str | char* | 要解析的字符串。 |
| size | uint32\_t | 字符串长度。 |
| separtor | char* | 分隔字符。 |
<p id="tokenizer_t_tokenizer_init"> 初始化tokenizer对象。




#### tokenizer\_next 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | char* | 成功返回token，失败返回NULL。 |
| tokenizer | tokenizer\_t* | tokenizer对象。 |
<p id="tokenizer_t_tokenizer_next"> 获取下一个token。




#### tokenizer\_next\_float 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | char* | 成功返回token的float值，失败返回缺省值。 |
| tokenizer | tokenizer\_t* | tokenizer对象。 |
| defval | float | 缺省值。 |
<p id="tokenizer_t_tokenizer_next_float"> 获取下一个token，并转换成float。




#### tokenizer\_next\_int 函数
-----------------------

| 参数 | 类型 | 说明 |
| -------- | ----- | --------- |
| 返回值 | char* | 成功返回token的int值，失败返回缺省值。 |
| tokenizer | tokenizer\_t* | tokenizer对象。 |
| defval | int | 缺省值。 |
<p id="tokenizer_t_tokenizer_next_int"> 获取下一个token，并转换成int。




#### cursor 属性
-----------------------
<p id="tokenizer_t_cursor"> 当前位置。



* 类型：uint32\_t

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 否 |
| 可脚本化   | 否 |
| 可在IDE中设置 | 否 |
| 可在XML中设置 | 否 |
| 支通过widget_get_prop读取 | 否 |
| 支通过widget_set_prop修改 | 否 |
#### separtor 属性
-----------------------
<p id="tokenizer_t_separtor"> 字符串。



* 类型：char*

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 否 |
| 可脚本化   | 否 |
| 可在IDE中设置 | 否 |
| 可在XML中设置 | 否 |
| 支通过widget_get_prop读取 | 否 |
| 支通过widget_set_prop修改 | 否 |
#### size 属性
-----------------------
<p id="tokenizer_t_size"> 字符串的长度。



* 类型：uint32\_t

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 否 |
| 可脚本化   | 否 |
| 可在IDE中设置 | 否 |
| 可在XML中设置 | 否 |
| 支通过widget_get_prop读取 | 否 |
| 支通过widget_set_prop修改 | 否 |
#### str 属性
-----------------------
<p id="tokenizer_t_str"> 字符串。



* 类型：char*

| 特性 | 是否支持 |
| -------- | ----- |
| 可直接读取 | 是 |
| 可直接修改 | 否 |
| 可持久化   | 否 |
| 可脚本化   | 否 |
| 可在IDE中设置 | 否 |
| 可在XML中设置 | 否 |
| 支通过widget_get_prop读取 | 否 |
| 支通过widget_set_prop修改 | 否 |
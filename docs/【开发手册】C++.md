## string::npos

`string::npos` 参数 —— npos 是一个常数，用来表示不存在的位置

例如，判断 `a` 字符串是否包含 `b` 字符串

```cpp
//如果字符串不存在包含关系，那么返回值就一定是npos
if(a.find(b)!=string::npos){
	cout<<"yes"<<endl;
}else{
	cout<<"no"<<endl;
}
```


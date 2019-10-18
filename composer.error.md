## Execute the command at the below

> composer require vendor-name/packageName

Then there is an alter as the below.

```

Deprecation warning: Your package name dxsys is invalid, it should have a vendor name, a forward slash, and a package name. 
The vendor and package name can be words separated by -, . or _. 
The complete name should match "[a-z0-9]([_.-]?[a-z0-9]+)*/[a-z0-9]([_.-]?[a-z0-9]+)*". 
Make sure you fix this as Composer 2.0 will error.

```

翻译：

失效声明：你的包名 dxsys 是无效的，它要有一个 vendor 名，一个正斜杠(\)，和一个包名。
。。。。

解决办法：将包名，改为 vendorName\packageName.

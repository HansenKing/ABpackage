 # ABpackage

一，AssetBundle是什么？

明显，我们从字面上就能理解：资源包。

二，为什么要使用AssetBundle？

至少，我们不希望我们的安装包大到让客户没有安装的动力。当然，这是玩笑话，AssetBundle主要是要解决开发中对资源动态下载与动态加载的痛点。是不是很痛，就要看项目的需求了。

三，AssetBundle的工作流程是怎么样的？

很简单，就跟现在我们下载网络上的资源一样样的。开发者将资源放在某个服务器地址上，客户端通过一个地址（URL）来访问服务器，下载对应的资源，客户端下载到资源再根据需求进行加载展现。


四，我们要怎么使用这个AssetBundle呢？

 打包完毕后，我们要实现的是，如何下载这个资源，并且实现加载。

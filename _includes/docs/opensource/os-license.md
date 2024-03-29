* TOC
{:toc}


### 开源许可证

开源许可协议是指开源社区为了维护作者和贡献者的合法权利，保证软件不被一些商业机构或个人窃取，影响软件的发展而开发的协议。

所谓软件许可证，就是随软件一起发布，对软件的使用、修改和分享及其他相关事宜作出规定的条款。开源许可证，就是开源软件使用的许可证。

**常用的开源许可证有：**

- MIT许可证
- BSD许可证
- Apache许可证
- LGPL许可证
- GPL许可证

MIT、BSD 许可证都源自大学，体现了简单、开放和包容的特点。

MIT、BSD、Apache 三者都支持闭源的后续开发。

GPL、LGPL 传染性开源，编译的代码里用了这里的代码，都必须开源。





### MIT协议

MIT 是十分宽松的许可协议，来源于大学，可以说是史上最为简洁和慷慨（permissive）的开源协议之一。

- 用户可以拿自己的代码做任何想做的事情；
- 用户在项目副本中要包含版权声明和许可声明；
- 用户无需承担任何责任。

作者只想保留版权，而无任何其他限制。也就是说，无论是以二进制发布的还是以源代码发布的，都必须在发行版里包含原许可协议的声明，。采用MIT协议的应用案例有JQuery、Rails 等。





### BSD协议

BSD 协议也很宽松，给予了使用者很大自由，基本上允许用户“为所欲为”：用户可以使用、修改和重新发布遵循该许可的软件，并且可以将软件作为商业软件发布和销售。前提是需要满足下面三个条件：

- 如果再发布的软件中包含源代码，则源代码必须继续遵循 BSD 许可协议。
- 如果再发布的只是二进制类库/软件，则需要在类库/软件的文档和版权声明中包含原来代码中的BSD协议。
- 不允许用原始开源代码软件的名称、作者名字或机构名称进行市场推广。

BSD代码鼓励代码共享，但需要尊重代码作者的著作权。BSD由于允许使用者修改和重新发布代码，也允许使用或在BSD代码上开发商业软件发布和销售，因此是对商业集成很友好的协议，很受大公司的欢迎，因为可以完全控制这些第三方的代码，甚至在必要的时候可以修改或者二次开发。





### Apache协议

Apache Licence是著名的非盈利开源组织Apache采用的协议。该协议和BSD类似，同样适用于商业软件，鼓励代码共享和尊重原作者的著作权，同样允许代码修改，但它更重视专利权。

- 如果修改了程序源代码，需要在文档中进行声明；
- 若软件是基于他人的源代码编写而成的，则需要保留原始代码的协议、商标、专利声明及其他原作者声明的内容信息；
- 如果再发布的软件中有声明文件，则需在此文件中标注 Apache 许可协议及其他许可协议。

Apache Licence也是对商业应用友好的许可。使用者也可以在需要的时候修改代码来满足需要并作为开源或商业产品发布/销售。现在热门的 Hadoop、Apache 家族、SVN、MongoDB 等项目都是基于该许可协议研发的。





### GPL协议

GPL协议来源自由软件联盟GNU，GPL/LGPL都侧重于代码及衍生代码的开源与免费使用。GPL是传染性开源，只要软件中包含了遵循 GPL 协议的产品或代码，该软件就必须也遵循 GPL 许可协议，也就是必须开源免费，不能闭源收费，因此这个协议并不适合商用软件。

- 复制自由：允许把软件复制到任何人的电脑中，并且不限制复制的数量。
- 传播自由：允许软件以各种形式进行传播。收费传播允许在各种媒介上出售该软件，但必须提前让买家知道这个软件是可以免费获得的；因此，一般来讲，开源软件都是通过为用户提供有偿服务的形式来盈利的。
- 修改自由：允许开发人员增加或删除软件的功能，但软件修改后必须依然基于GPL许可协议授权。

遵循 GPL 协议的开源软件数量极其庞大，包括 Linux 系统在内的大多数的开源软件都是基于这个协议的。





### LGPL开源协议

LGPL 是 GPL 的一个衍生版本，也被称为 GPL V2，该协议主要是为类库设计的开源协议，同样来源于自由软件联盟GNU，可以翻译为更宽松的GPL协议，也属于传染性开源。

- 用户如果只是对LGPL软件的程序库的程序进行调用而不是包含其源代码时，相关的源程序无需开源。

LGPL允许商业软件通过类库引用(link)方式使用LGPL 类库而不需要开源商业软件的代码。这使得采用LGPL协议的开源代码可以被商业软件作为类库引用并发布和销售。GPL/LGPL都保障原作者的知识产权，避免有人利用开源代码复制并开发类似的产品。




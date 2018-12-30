## **W3C的主要规范**

到目前为止，W3C已开发了超过50个规范\(草案\)。这些规范\(草案\)包括人们早已、耳熟能详的HTML、HTTP、URIs、XML等，也包括针对语义Web的RDF、OWL等。

* HTML/XHTML：HTML是Web的基础之一，基于HTML，Web上开始出现丰富多彩的页面，蕴涵了各种信息。基于HTML，Web以一种简便易用的方式走出了象牙塔，成为全社会的公共资源和财富。W3C先后推出了多个HTML版本，分别是1997年12月的首个版本、1998年4月的更新、1999年12月推出HTML 4.01版。XHTML是对HTML 4.01的扩展，在其中可以使用XML的语义功能。XHTML 1.0已于2000年1月作为推荐标准发布；XHTML Basic是对XHTML1.0的独立于设备\(如手机、PDA等\)的扩展，于2000年12月发布；随后，2001年5月推出了XHTML的模块化版本——XHTML1.1。

* CSS：CSS负责为网页设计人员提供丰富的款式空间来设计网页。CSS所提供的网页结构内容与表现形式的分离机制，大大简化了网站的管理，提高了开发网站的工作效率。CSS可用于控制任何HTML和XML内容的表现形式。CSS1.0于1996年12月推出，1998年5月CSS2.0发布。

* XML:1998年2月发布的XML 1.0是W3C最具前瞻性和最有影响的标准之一。XML作为下一代Web的第一块重要基石，为分布式的、异构的数据交换提供了强大的功能，并且将数据本身和数据的表现分离，同时，就数据本身而言，数据的值和语义也是适当分离的。事实上，XML已经发展为一族技术，包括2001年5月发布的XML Schema、1999年1月发布的XML Namespaces、1999年11月发布的用于处理XML转换的XSLT和用于在XML文档中定位的XPath，以及2001年6月发布的XLink和XML Base等。此外，XML的出现为程序能够自动地处理Web数据和信息，以及Web服务\(WSDL、SOAP、UDDI规范\)提供了一种公共基础。

* DOM：DOM为HTML、XML等数据载体和信息载体在内存中的处理提供了一种基本的对象模型，可提供连接到文件的结构、格式、事件等。由于不依赖于任何程序设计语言和网页描述语言，它为有效处理HTML和XML数据提供了一种标准的、独立的接口。DOM先后经历了3个版本，分别是1998年10月发布的DOM Level 1、2000年11月发布的DOM Level 2和2003年发布的DOM Level 3



**W3C标准使用实例**

      当顶部为：  
&lt;!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN"&gt;  
      需注意以下情况，所用前提都是在顶部为是一句基础上而言！

      1、所有标签用小写。  
      建议养成好习惯把ul span li div 都用小写，当然当顶部申明为上面所示，则不严格区分大小写的。

      2、头文件meta、link标签。  
      错误：&lt;meta http-equiv="Content-Type" content="text/html; charset=gb2312" /&gt;  
      正确：&lt;meta http-equiv="Content-Type" content="text/html; charset=gb2312"&gt;  
      错误：&lt;link href="/wl\_pic/CSS.css" type="text/css" rel="stylesheet" /&gt;  
      正确：&lt;link href="/wl\_pic/CSS.css" type="text/css" rel="stylesheet"&gt;  
      正确：&lt;meta http-equiv="Content-Language" content="zh-CN" &gt;

      3、JS调用。  
      错误：&lt;script src="/wl\_inc/main.js" &gt;&lt;/script&gt;  
      错误：&lt;script src="/wl\_inc/main.js" language="javascript"&gt;&lt;/script&gt;  
      正确：&lt;script src="/wl\_inc/main.js" type="text/javascript"&gt;&lt;/script&gt;  
      正确：&lt;script src="/wl\_inc/main.js" type="text/javascript" &gt;&lt;/script&gt;

      4、表格&lt;table&gt;高度  
      不要使用如height="101"  
      正确：&lt;table width="970" style="height:101px;" border="0" align="center" cellpadding="0" cellspacing="0"&gt;

      5、正确使用alt、title  
&lt;a href="/"&gt;&lt;img src="/wl\_pic/logo.gif" border="0" alt="南宁大家教" &gt;&lt;/a&gt;  
&lt;a href="/NoticeHTML/?2.htm" class="bt" title="南宁大家教"&gt;南宁大家教&lt;/a&gt;  
      凡是没有带加链接的图片必须加上alt=""如：  
&lt;img height="11" src="/wl\_pic/tu.gif" width="11" alt=""&gt;

      6、在声明文件为前面说的情况下，可省略双引号或单引号。  
      如：&lt;div id=navpart&gt; 或者 &lt;div id="navpart"&gt; 都通过w3c标准的。


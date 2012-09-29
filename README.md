实现一个通用的bean copy工具
<ol>
	<li>支持pojo和map之间的互相拷贝；</li>
 	<li>支持pojo和pojo之间的互相拷贝；</li>
	<li>支持枚举和自定义枚举解析方法；</li>
	<li>支持date、timestamp与string、long之间的转换；</li>
	<li>支持基本类型和封装类之间的转换；</li>
	<li>支持数值型之间以及数值型与string之间的转换；</li>
	<li>支持数组的转换；</li>
	<li>可扩展其他自定义字段映射；</li>
	<li>不支持嵌套类的拷贝；</li>
	<li>单个字段无法拷贝不抛异常且不影响其他字段；</li>
	<li>基于预编译实现，比较BeanUtils性能好很多，功能上又较cglib的beanCopier工具类强；</li>
</ol>

=============

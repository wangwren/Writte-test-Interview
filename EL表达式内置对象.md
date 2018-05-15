## EL表达式的11个内置对象
- EL是JSP内置的表达式语言
- JSP2.0开始，不让再使用Java脚本，而是使用EL表达式和动态标签来代替Java脚本。EL替代的是`<%=...%>`，也就是说EL只能做输出。
- EL可以输出的东西都在11个内置对象中，11个内置对象，其中10个是Map，只有pageContext不是Map，它就是PageContext类型，EL所有内置对象如下。
### 11个内置对象
- pageScope:获取pageContext域属性，相当于`pageContext.getAttribute("xxx")`
- requestScope:获取request域属性,相当于`request.getAttribute("xxx")`
- sessionScope:获取session域属性，相当于`session.getAttribute("xxx")`
- applicationScope:获取application域属性，相当于`application.getAttribute("xxx")`
- param:对应参数，它是一个Map，其中key是参数，value是参数值，适用于单值的参数，相当于`request.getParameter("xxx")`
- paramValues:对应参数，它是一个Map，其中key是参数，value是多个参数值，适用于多值得参数，相当于`request.getParameterValues("xxx")`
- header:对应请求头，它是一个Map，其中key表示头名称，value是单个头值，适用于单值的请求头，相当于`request.getHeaders("xxx")`
- headValues:对应请求头，它是一个Map，其中key表示头名称，value是多个头值，适用于多值得请求头，相当于`request.getHeaders("xxx")`
- initParam:获取web.xml中`<context-param>`内的参数，`${initParam.xxx}`,xxx就是`<param-name>`标签内的值，进而得到`<param-value>`中的值。
- cookie:用于获取cookie，Map<String,Cookie>,其中key是cookie的name，value是cookie对象，例如`${cookie.JSEESSION.value}`就是获取sessionId
- pageContext:可以获取JSP九大内置对象，相当于使用该对象调用调用getxxx()方法，例如`pageContext.getRequest()`可以写为`${pageContext.request}`
### 使用
EL表达式在获取Map的值或Bean的属性值时，可以使用”点“的方法，也可以使用”下标“的方法。  
`${initParam.a}`与`${initParam['a']}`，它们完成的东西相同。但是，如果Map的键或Bean的属性名中包含下划线或横杠时，那么就必须使用“下标”方法，例如:`${initParam['a_a']}`
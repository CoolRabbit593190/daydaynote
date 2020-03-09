# daydaynote
记录每天技术研究的小发现
> 2022-02-20
1.  java集合的removeAll方法会移除入参中集合出现过的元素相同的所有元素，无数量限制
```
A=[1,2,2,3]
B=[2]
A.removeAll(B)后
A=[1,3]
```
> 2022-02-28
1.  java的Scanner.nextLine()函数会接收回车及空格及tab等特殊字符作为输入，在其它输入回车的输入操作之后试用，可能会出现跳过nextLine函数没执行的假象

>2022-03-10
1.  mybatis映射xml文件，存在目录必须是mapper，否则接口绑定失败
2.  Spring注解@Controller需和注解@ResponseBody配合使用，建议用@RestController注解
3.  mapstruct框架使用时，target和source中有相同名称字段A和B，且B字段需映射C字段。请ignore字段A

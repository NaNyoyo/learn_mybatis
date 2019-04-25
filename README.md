# 《MyBatis应用分析与最佳实践》课后作业
## 课01作业
### 1.resultType（属性）和resultMap（标签引用）的区别？
    resultType和resultMap都是结果集映射成POJO的，2个不能同时使用。
    resultType:返回的期望类型的类的完全限定名或别名。
    resultMap:外部resultMap的命名引用，可以映射更为复杂的情形。


### 2.collection和association的区别？
    association和collection都是resultMap元素的子元素。
    association处理的是一对一的问题。
    collection处理的是一对多的问题。
    

### 3.Statement和PreparedStatement的区别？
    PreparedStatement是预编译，可以防止SQL注入问题。

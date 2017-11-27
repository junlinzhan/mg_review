1. @Autowired与@Resource的区别
  + Autowired 是默认按类型装配，默认装配的bean不能为空，需使用Qualifier实现按名称装配，required设置装配的bean可以为空
  + Resource 是默认按名称装配，注解在字段名上 默认取字段名进行名称查询装配，注解在setter上默认按属性名进行名称查询装配，不指定名称 如果按名称找不到bean 则会按类型再进行查找，指定了name则只会按照名称进行查询
2. 

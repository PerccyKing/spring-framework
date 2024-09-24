# spring生命周期

- bean对象解析
  - xml定义的bean解析**XmlBeanDefinitionReader**
  - 注解定义的bean解析
  - > 不同的bean定义可以使用不同的BeanDefinitionReader来获取bean定义信息
- 通过bean的定义信息创建bean
  - 实例化
    - 通过反射选取构造器进行实例化
  - 初始化
    - 属性赋值
    - 增强
  - 使用
  - 销毁

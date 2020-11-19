# AssociatedObjectDemo
iOS开发·runtime原理与实践: 关联对象篇(Associated Object)(应用场景：为分类添加“属性”，为UI控件关联事件Block体)

# 摘要

编程，只了解原理不行，必须实战才能知道应用场景。本系列尝试阐述runtime相关理论的同时介绍一些实战场景，而本文则是本系列的**关联对象**篇。**本文中**，第一节将介绍关联对象及如何关联对象，第二节将介绍关联对象最常用的一个实战场景：为分类添加属性，第三节将介绍关联对象另一个很重要的实战场景：为UI控件（比如，UIAlertView以及UIButton等等）关联事件Block体。

# 简书对应地址

[iOS开发·runtime原理与实践: 关联对象篇(Associated Object)(应用场景：为分类添加“属性”，为UI控件关联事件Block体)](https://www.jianshu.com/p/916aef6f7ab1)

# 参数
 /*
      关联对象 void objc_setAssociatedObject(id object, const void *key, id value, objc_AssociationPolicy policy)

      其中的参数

      id object：被关联的对象
      const void *key：关联的key，要求唯一
      id value：关联的对象
      objc_AssociationPolicy policy：内存管理的策略
      */

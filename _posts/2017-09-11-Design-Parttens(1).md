---
layout: post
title: 设计模式丨
date: 2017-09-12
categories: blog
tags: [设计模式],[学习]
description: 设计模式学习过程记录 。

---

<h4>设计模式(Design Patterns)</h4>
<p>设计模式是一套被反复使用的、多数人知晓的、经过分类编目的、代码设计经验的总结。使用设计模式是为了重用代码、让代码更容易被他人理解、保证代码可靠性。</p>
<br/>
四人合著出版了一本名为Design Patterns - Elements of Reusable Object-Oriented Software(设计模式-可复用的面向对象软件元素)
主要基于以下面向对象设计原则。
*  对接口编程而不是对实现编程。
*  优先使用对象组合而不是继承。
<br/>

<table border="1" align="center">
    <th colspan="2">设计模式的类型</th>
    <th></th>
    <tr>
        <td><b>创建型模式</b><br/>提供了一种在创建对象的同时隐藏创建逻辑的方式，而不是使用新的运算符直接实例化对象。这使得程序在判断针对某个给定示例需要创建哪些对象时更加灵活。</td>
        <td>工厂模式 | 抽象工厂模式 | 单例模式</td>
    </tr>
    <tr>
        <td><b>结构型模式</b><br/>这些设计模式关注类和对象的组合。继承的概念被用来组合借口和定义组合对象获得新功能的方式。</td>
        <td>适配器模式 | 代理模式</td>
    </tr>
    <tr>
        <td><b>行为型模式</b><br/>这些设计模式特别关注对象之间的通信。</td>
        <td>模板模式</td>
    </tr>
    <tr>
        <td><b>J2EE模式</b><br/>这些设计模式特别关注表示层。这些模式是由Sun Java Center鉴定的。</td>
        <td>MVC模式</td>
    </tr>
</table>
<br/>
<h4>设计模式六大原则</h4>
<h5>1.开闭原则(Open Close Principle)</h5>
开闭原则的意思是：对扩展开放，对修改关闭。为了使程序的扩展性好，易于维护和升级，为了达到这样的效果，需要使用接口和抽象类。

<h5>2.里氏代换原则(Liskov Substitution Principle)</h5>
里氏代换原则是面向对象设计的基本原则之一。任何基类可以出现的地方，子类一定可以出现。它是开闭原则的补充，是实现抽象化的具体步骤的规范。

<h5>3.依赖倒转原则(Dependence Inversion Principle)</h5>
这个原则是开闭原则的基础，具体内容：针对对接口编程，依赖于抽象而不依赖于具体。

<h5>4.接口隔离原则(Interface Segregation Principle)</h5>
使用多个隔离的接口，降低依赖，降低耦合。

<h5>5.迪米特法则，又称最少知道原则(Demeter Principle)</h5>
一个实体应当尽量少地与其他实体之间发生相互作用，使得系统功能模块相对独立。

<h5>6.合成复用原则(Composite Reuse Principle)</h5><br/>
原则：尽量使用合成/聚合的方式，而不是使用继承。



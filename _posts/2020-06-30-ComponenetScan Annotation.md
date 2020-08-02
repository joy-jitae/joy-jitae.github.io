---
title: ComponentScan Annotation 대하여
description: ComponentScan Annotation에 대해
categories:
 - SpringBoot
 - Annotation
tags: ['Spring', 'SpringBoot', 'Annotation']
---

<!-- more -->

>Bean 이 등록이 되지 않아, 왜 그런지 검색해보면서 ComponentScan 과 Component Annotation 에 대해서 검색해보게 되었다.

# ComponentScan Annotation
 
> @ComponentScan이 붙어있는 클래스가 있는 패키지에서부터 모든 하위 패키지의 모든 클래스를 훑어보며 @Component 애노테이션(또는 @Component 애노테이션을 사용하는 다른 애노테이션)이 붙은 클래스를 찾는다.


-   ComponentScan Annotation은 제일 최상단의 Class 에 붙여준다.
-   ComponentScan Annotation을 붙여주면 어디서부터 컴포넌트를 찾아볼 것인지 알려주는 역할을 한다.
-   Spring이 IoC 컨테이너를 만들때, 위와 같은 과정을 거쳐 Bean 으로 등록해준다. 






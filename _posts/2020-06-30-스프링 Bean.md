---
title: Semantic UI 사용
description: Semantic UI 사용
categories:
 - Semantic-UI
tags: ['jQuery','semantic-ui']
---


<!-- more -->

## Semantic UI 란

# UI 란 
사용자가 시스템을 조작하는데 사용하는 장치들을 의미합니다.

# Semantic UI
semantic UI는 UI Library의 카테고리에 속하는 제품입니다. 이 도구는 잘 만들어진 기본 부품(component)를 제공합니다. 이 부품들을 활용해서 빠르게 서비스를 구현할 수 있고, 필요에 따라서는 개조해서 사용할수도 있습니다.

semantic-ui-vue 와 semantic-ui 가 서로 다른 형태로 사용됩니다. 

- semantic-ui-vue 는 vue 안에서 사용할 수 있도록 만들어진 플러그인 입니다. vue에서 사용할땐, 아래와 같이 사용합니다.
````
<template>
  <div>
    <sui-tab>
      <sui-tab-pane title="HTML">
        <h3>HTML</h3>
        <p>
          HTML (HyperText Markup Language) is the most basic building block of
          the Web. It describes and defines the content of a webpage along with
        </p>
        <a href="https://developer.mozilla.org/en-US/docs/Web/HTML"
          >developer.mozilla.org</a
        >
      </sui-tab-pane>
    </sui-tab>
  </div>
</template>
````

- semantic-ui 는 javascript 등 사용하기 위해서 아래와 같이 사용됩니다.

````
<div class="ui top attached tabular menu">
  <a class="active item" data-tab="first">First</a>
  <a class="item" data-tab="second">Second</a>
  <a class="item" data-tab="third">Third</a>
</div>
<div class="ui bottom attached active tab segment" data-tab="first">
  First
</div>
<div class="ui bottom attached tab segment" data-tab="second">
  Second
</div>
<div class="ui bottom attached tab segment" data-tab="third">
  Third
</div>
````

semantic-ui-vue 나 semantic-ui 나 같은거인 줄 알았는데, 그게 아니였습니다.

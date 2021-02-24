# ConnectionComponent
基于canvas的连线组件，连线，connection，连线题


# 使用方式

```
import Connec from 'LianXian'
      <connect
        :line-prop="LineProp"
        :top-data="topData"
        :bottom-data="bottomData"
        @onResult="onResult"
        @onStartCanvas="onStartCanvas"
      />
```


* line-prop:连线属性，颜色，粗细
* top-data:上面数据
* bottom-data:下面数据

支持图文连线、图图连线、文文连线，全部自适应，只需把组件放到一个容器里面即可

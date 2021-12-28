## changelog

## 最新的代码(lastest) v0.7.2
1. fix: scrollTo row unusual

## v0.7.1
1. fix: scrollTo fault.
2. Fix the error caused by less data when the tree table is changed

## v0.7.0
1. fix: #51
2. new option 'resetTopWhenDataChange'

## v0.6.5-beta.2
1. fix: scrollTop is not reset when data change on same data length
2. optimized relate code on data change

## v0.6.5-beta.0
1. fix: sometimes data is not complete in hot update when debugging

## v0.6.4
1. fix #48
## v0.6.3
1. fix: 树形表格看不全数据的问题. (fix tree table bug of incomplete data)
2. fix: fix offsetStart bug that multiple rows become 0 rows
3. fix: 处理notRrefresh报错问题.
4. add eslint

## v0.6.2
1. fix: 树形表格最后行有很多子数据的时候, 滚动会出现问题. (fix tree table bug)
## v0.6.1
1. 去掉start的判断. (remove the judgment of the variable start)
## v0.6.0
1. fix: 处理存在多个虚拟表格的时候, 全局属性会覆盖的问题. (fix bug that global attr is overridden when exist different virtual tables)
## v0.5.8
1. fix: 处理滚动条滚到最后面的时候 会出现抖动的问题 & 删除无用代码. (fix bug that data shake when scroll on final)

## v0.5.7
1. VRow向外暴露ref. (can do this like VRow(props, ref))

## v0.5.6
1. 向外暴露onScroll. (export onscroll)
2. 去掉多余的10padding. (remove excess 10 padding)

## v0.5.5
1. feat: 支持scrollTo的导出. (support scrollTo)

## v0.5.4
1. feat: 扩展onReachEnd, 支持无限加载. (support load more data on a page.)

## v0.5.3
1. (发布错误)

## v0.5.2
1. 将样式文件的width: inherit 改为 100%.

## v0.5.1 
1. update rep info.

## v0.5.0
1. update && adjust npm package.

## v0.4.9
1. 将ISC协议改为MIT.

## v0.4.8
1. fix: 在length为0的时候, 没有更新totalLen的问题. (fix data length is 0, not update totalLen.)

## v0.4.8-beta
1. feat: support #10.

## v0.4.7
1. fix: #8 处理rc-table v7.8.2的改动. 同时兼容上一个版本. (deal rc-table v7.8.2 change)

## v0.4.6
1. fix: #7 处理antd 4.3.5 边框不显示的问题. (fix bug: no border)

## v0.4.5
1. fix: 当scroll值有x: max-content且列数很少的时候, 会出现表头和内容行补齐的样式问题. (fix when scroll={x: 'max-content'} and little columns, content unable to align header.)

reappear: (https://codesandbox.io/s/festive-worker-wc5wp for v0.4.4)

already fix: (https://codesandbox.io/s/festive-worker-wc5wp for v0.4.5)

## v0.4.4
1. revert 0.4.3.

## v0.4.3 & v0.4.3-beta.0
1. 内部代码不再将scrollY的值作为全局变量, 考虑到可能有一个页面有多个虚拟列表的情况。

## v0.4.2
1. 还是采用导入的样式文件的方式, 取代掉VCell的内联样式. (performance question) 

## v0.4.1
1. fix: 处理因样式问题导致 antd fixed表格 阴影失效的问题. (fix antd box-shadow not work)
2. 新增了VCell, 会替代components的body cell. 每个td下会有一个div包裹. 

## v0.4.0
1. fix: 处理css样式失效的问题. (fix internal css not work)

## v0.3.3
1. revert v0.3.2

## v0.3.2
1. fix: 处理因样式问题导致 antd fixed表格 阴影失效的问题.  (fix antd box-shadow not work)

## v0.3.1
1. fix: 处理使用calc()下的高度问题.

## v0.3.0
1. feat: 更新支持antd4的Table.

## v0.2.8
1. 去掉了多余且不灵活的字体设置, 让table字体可自定义.

## v0.2.7
1. 处理tableScrollY <= 0的情况.

## v0.2.7beta1
1. 压缩发布包的代码, 大小变为17k

## v0.2.5 & v0.2.6
1. 去掉一些多余的rollup配置. 文件大小160多k变为50多K. 

## v0.2.4
1. 修复在页面空间足够的时候却还出现滚动条的问题.
2. 清除滚动到最后的空白.

## v0.2.3
1. 修复在tableHeight < tableScrollY的时候 数据会抖动的情况

## v0.2.2 (此版本后都支持分页)
1. 修复tableScrollY变化的时候 会出现表格不全的问题.

## v0.2.1
1. 支持scrollY设置为calc()
2. 调整节流时间为100ms

====================================================

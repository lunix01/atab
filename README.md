# atab
tab，jquery片段代码，暂时就这样，看看就好，慎重使用。

##使用示例
html:
```
<nav>
    <div data-groupname="tab" data-tab="item" class="active">1</div>
    <div data-groupname="tab" data-tab="item">2</div>
</nav>
<section data-groupname="tab" data-tab="content">1 content</section>
<section data-groupname="tab" data-tab="content">2 content</section>
```

js:
$(function() {
  tab('tab', 'mouseover');
});

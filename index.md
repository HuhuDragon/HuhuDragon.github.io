---
layout: default
---

<!-- Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project. -->


<table border="0">
  <tr>
    <td width="75%">
      <h1>呼呼龙</h1>
      <p><b>硕士研究生</b></p>
      <p><b>中国原子能科学研究院核物理研究所</b></p>
      <p><b>邮箱：isaackejtin@qq.com</b></p>
      <p><b>QQ：774218389</b></p>
    </td>
    <td width="25%">
      <img src="/huhudragon.jpg" width="100%">     
    </td>
  </tr>
</table>



# 个人信息

简略版：呼呼龙者，乃前朝佞臣，本无懿德。败坏纪法，祸乱朝纲。概多进食于先帝，深得帝心。官拜弼猫温，追谥鱼干大将军。

详细版：呼呼龙，英文名Huhu Dragon，又名Isaac Kejtin，本科四川大学物理系，硕士及博士就读于中国原子能科学研究院核物理研究所，方向为核天体物理，硕士期间主要研究Mg-Al循环中的质子俘获反应。实验水平凑合，编程能力一般，但还挺喜欢科研的（虽然天赋全点文学上了），这辈子大概会一直干下去。这个博客就当个大杂烩吧，会放现在的工作，也会放一些以前的诗词（已经基本封笔了）、短篇小说及翻译作品，未来说不定也会放一些碎碎念（笑）。



# 发表论文

基于串列加速器Q3D磁谱仪与质子转移反应的27Al能级信息研究，原子能科学技术


# 最新博文

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h2>
        <a href="{{ post.url | relative_url }}">
          {{ post.title }}
        </a>
      </h2>
      <div class="post-meta">
        <time>{{ post.date | date: "%Y-%m-%d" }}</time>
        {% if post.categories %}
          <span> • {{ post.categories | join: ", " }}</span>
        {% endif %}
      </div>

    </li>
  {% endfor %}
</ul>


<!-- ## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
``` -->

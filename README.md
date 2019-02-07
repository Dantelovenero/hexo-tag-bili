# hexo-tag-bili
Embed bilibili video in Hexo posts/pages [中文文档](https://github.com/honjun/hexo-tag-bili/blob/master/README-zh_cn.md)

## Syntax:
{% bili video_id %} or {% bili video_id page %}

## Usage
In Hexo blog run
```cmd
npm i hexo-tag-bili --save
```
In Hexo posts/pages
```markdown
{% bili video_id %} or {% bili video_id page %}
```
## Example: 
https://www.bilibili.com/video/av24897960

{% bili 24897960 %}

-----------

https://www.bilibili.com/video/av24897960/?p=2

{% bili 24897960 2 %}


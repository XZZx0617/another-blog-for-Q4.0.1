##[点我查看中文说明/Click here for Chinese instructions](https://github.com/bit-ranger/blog/blob/gh-pages/README_zh_CN.md)

# Blog Address

<https://bit-ranger.github.io/blog/>


# Must Modify

## 1.Swiftype

This service provides the on-site search function.

Service address： <https://swiftype.com/>.

After the setup is complete， you need to modify the `swiftype.searchId` in `_config.yml`.

In your swiftype engine, go to `Setup and integration` -> `Install Search`, you could find the `swiftype.searchId`.

```html
<script type="text/javascript">
...
...
  _st('install','swiftype.searchId','2.0.0');
</script>
```

## 2.Gitment

This service provides the comment function.

Service address： <https://github.com/imsun/gitment>.

After the setup is complete， you need to modify the `gitment`  in `_config.yml`.

## remind to change README

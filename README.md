# hatenablog-calm

Blog theme for [Hatena Blog](https://hatenablog.com/) named Calm.

You can install this theme from [the theme store](https://blog.hatena.ne.jp/-/store/theme/26006613602845758) and use it.

## Classes

You can style the content using the following CSS classes.

#### `button`

Change the link element to look like a button.

```
<a href="#" class="button">Text</a>
```

#### `border`

Enclose the element with this class in a frame. Unlike ordinary border, it is applied so that it overlaps the inside of an element. It is supposed to be used mainly when attaching a frame to an image.

```
<p class="border">[f:id:murata_s:20191002134857j:plain]</p>
```

## Development

Setup:

```
yarn install
```

Start monitoring and compiling Sass:

```
yarn develop
```

Set up the CSS for “Design CSS” of Hatena blog:

```
@import 'http://localhost:1234/calm/calm.css';
```

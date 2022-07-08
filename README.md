# webfonts-for-safari

Due to the security features of the safari browser, there is a problem that the font you add manually does not display properly when you apply it to the stylesheet. You can use google api for typical open source typefaces, but if you can't get them that way, you have to convert them directly to woff2 format, post them on the web, and apply them to the stylesheet in the form of src url.

```
@font-face {
    font-family: 'Malgun Gothic Semilight';
    src: url('https://raw.githubusercontent.com/darkbrow/webfonts-for-safari/main/woff2/MalgunGothic-Semilight.woff2') format('woff2');
    font-weight: 300;
    font-style: normal;
    font-display: swap;
}
```

## fonts under woff2 directory

- malgun gothic
- monaco
- noto serif kr
- nanum myeongjo

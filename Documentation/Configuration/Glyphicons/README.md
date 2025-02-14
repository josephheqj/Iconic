# Iconic Configuration: Glyphicons

*[If you have successfully configured Glyphicons, please consider contributing to this doc!]*

The Bootstrap CSS framework includes a subset of free Glyphicons, or there are pro versions available.


## Known issues with Glyphicons
If you try to use Glyphicons as part of the Bootstrap package, you will realise that the whole css file will be loaded on your backoffice. This might break some of the backoffice functionality, i.e. buttons or the grid editor. To avoid this you should export the Glyphicons classes into their own separate file. You can do this from [this link](https://getbootstrap.com/docs/3.3/customize/) and select only Glyphicons from the **Components** section.

![CSS files](cssfiles.png)

Your Bootstrap.css and .min.css will contain your Glyphicons classes. You can rename this to something else to differentiate them from the actual Bootstrap classes if you're using them.

## Bootstrap Glyphicons

[Bootstrap Glyphicons Icons Reference](https://getbootstrap.com/docs/3.3/components/)

1. Obtain the [Icon files](https://getbootstrap.com/docs/3.3/getting-started/).  
2. When [creating the DataType](../), start with the **Pre-configured option** "Glyphicons".
3. Set the **CSS file** to "glyphicons.css" .
4. Set the **Rules source file** to *glyph* .



## Pro Glyphicons

[Glyphicons Site](https://www.glyphicons.com/)





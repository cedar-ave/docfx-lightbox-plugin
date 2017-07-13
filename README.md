# docfx-lightbox-plugin
A small repository containing a template for DocFx to add lightbox effect for all images. 

## Featherlight
The first version of this template uses the jQuery [Featherlight](https://noelboss.github.io/featherlight/) plugin. Therefore, there is a dependencies on both of these libraries.  
It is using the default template from `docfx` as a base template. 
jQuery and the featherlight libraries are loaded from the public CDN.

### Usage
To use this template, you need to add it to your repository in the `templates` folder, and add the following to your `docfx.json` file:

```json
   "template": [
      "default",
      "templates/lightbox-featherlight"
    ]
```

### Demo
A sample can be found in the `demo` folder. It uses a relative path to the `templates` folder. 

## Bootstrap modal
The second version of this plugin uses the Bootstrap Modal window, and is created by implementing `IPostProcessor`.  


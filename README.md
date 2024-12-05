# PrimeFaces theme template
This is an unofficial template to create your own custom primefaces theme
without having to essentially fork all of PrimeFaces `.scss` sources,
allowing you to customize only what you need while being able to easily update.

## Usage
The themes live in the `themes/` folder, you'll find an example theme there that
you can modify/rename as you see fit. Note this theme was simply copied from [here](https://github.com/primefaces/primefaces/tree/master/primefaces-themes/themes/primefaces-mytheme).

Include the built theme into your application dependencies:
```xml
    <dependency>
        <groupId>org.example</groupId>
        <artifactId>primefaces-mytheme</artifactId>
        <version>1.0.0-SNAPSHOT</version>
    </dependency>
```

And use your theme, see [PrimeFaces documentation](https://primefaces.github.io/primefaces/15_0_0/#/core/themes)

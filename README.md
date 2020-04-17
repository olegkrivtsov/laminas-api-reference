# Laminas API Reference

This project's goal is to provide a reference of Laminas Framework 
components and their PHP classes (API). The latest published version 
of the reference can be found on the [Laminas API Reference Website](https://olegkrivtsov.github.io/laminas-api-reference/html/index.html). 

This reference is integrated with my free book, [Using Laminas Framework](https://github.com/olegkrivtsov/using-Laminas-framework-book), 
so you can take a look at it, too.

# Generating Yourself

If you want to generate this API reference yourself (for example, to contribute on GitHub), 
you need the [php-api-doc-maker](https://github.com/olegkrivtsov/php-api-doc-maker) tool.

Before you install the tool, you need to have PHP installed.

The tool needs the source code of Laminas components to generate the class reference. 
Install Laminas components with the following command:

```
php composer.phar update
```

Generate the reference in HTML format with the following command:

```
php php-api-doc-maker.php /path/to/api/reference/dir 
```

If everything is OK, you should find HTML files inside the 
`/path/to/api/reference/dir/html` subdirectory.

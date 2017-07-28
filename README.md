# Liferay IPC for Vaadin 8

## Download release

Official releases of this add-on are available at Vaadin Directory. For Maven instructions, download and reviews, go to http://vaadin.com/addon/liferayipc

## Building and running demo

```
git clone https://github.com/vaadin/liferayipc.git
mvn clean install
cd liferayipc-demo
mvn liferay:deploy
```

Note that you need Liferay 6.2 and set up Maven to find the Liferay
installation as described in https://web.liferay.com/web/matti/blog/-/blogs/using-self-contained-approach-to-package-vaadin-portlets

To see the demo, start Liferay and add the portlets to a page


# README
This is a pages examples.  It's a great way for developers to share static sites.   

View here [https://blog.chrisguest.dev/](https://blog.chrisguest.dev/)

The base github pages is located at [https://chrisguest75.github.io/pages_example/](https://chrisguest75.github.io/pages_example/)

## Update the build
```sh
cd ./pages_example
rm -rf *   
cp -R ../hugo_examples/quickstart/public/* . 
git checkout head -- README.md 
git checkout head -- CNAME
```

## Update the build from release package.
```sh
cd ./pages_example
rm -rf *   
# in the hugo_examples directory
cd ../hugo_examples
gh release download -D ../pages_example -p blog-package.zip
# in the pages_example directory
cd ../pages_example
unzip ./blog-package 
git checkout head -- README.md 
git checkout head -- CNAME
```


# Resources
* https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages
* https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/troubleshooting-custom-domains-and-github-pages


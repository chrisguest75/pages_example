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

# Resources
* https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/about-custom-domains-and-github-pages
* https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/troubleshooting-custom-domains-and-github-pages


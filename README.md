# README
This is a pages examples.  It's a great way for developers to share static sites.   

View here [https://chrisguest75.github.io/pages_example/](https://chrisguest75.github.io/pages_example/)


## Update the build
```sh
cd ./pages_example
rm -rf *   
cp -R ../hugo_examples/quickstart/public/* . 
git checkout head -- README.md 
git checkout head -- CNAME
```


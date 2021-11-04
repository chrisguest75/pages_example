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

https://project-awesome.org/sdras/awesome-actions

https://www.weave.works/blog/how-to-create-gitops-pipelines-with-github-actions-and-weave-cloud

https://rusyasoft.github.io/github,%20gitops,%20devops,%20argocd/2020/11/15/how-to-gitops-with-github-actions/


https://zwischenzugs.com/2021/07/31/a-hello-world-gitops-example-walkthrough/

https://blog.marcnuri.com/triggering-github-actions-across-different-repositories

https://github.com/marketplace/actions/create-pull-request
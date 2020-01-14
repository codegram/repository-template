# What is this?

This is a starter repository with some niceries like templates or default actions. We use it at Codegram to speed up our repositories and for consistency.

# How do I add this to my repository?

Just execute this nice one-liner on the root path of your project. Just trust us.

```bash
$ wget -q -O repository-template.zip https://github.com/codegram/repository-template/archive/master.zip &&
    unzip repository-template.zip -x "repository-template-master/Readme.md" &&
    rm repository-template.zip && cd repository-template-master &&
    cp -r . .. && cd .. && rm -fR repository-template-master
```

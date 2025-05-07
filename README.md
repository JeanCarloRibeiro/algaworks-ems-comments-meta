# **_Comments meta_**

**References:** _AlgaWorks EMS Training_


It will group all microservices using git module strategy.



### Commands git submodules
download all submodules
```bash
 git pull --recurse-submodules
```

add project as submodule (example: git submodule add <url> <path>)
```bash
git submodule add git@github.com:JeanCarloRibeiro/algaworks-ems-comments-comment-service.git microservices/comment-service
```

clone all submodules (example: git clone --recurse-submodules <url>)

params: -j8: number of jobs to run in parallel
```bash 
git clone --recuse-submodules -j8 git@github.com:JeanCarloRibeiro/algaworks-ems-comments-meta.git comments-meta
```
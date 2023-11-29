# CICD + Github Action Tutorial
[소스 레포](https://github.com/Link-/ci-cd-intro)
링크를 기반으로 제작되었습니다.

쿠버네티스코리아 커뮤니티 기술 세미나 2023/11/29

Github action 과 ArgoCD 를 활용해서 로컬 쿠버네티스 클러스터에 CICD 구현해보기

### 레포 구조

- [cicd-tut-source](https://github.com/protess/cicd-tut-source) : Github action 과 소스레포
- [gitops-tutorial](https://github.com/protess/gitops-tutorial/tree/main) : Gitops, ArgoCD, 로컬 k8s 클러스터

### 디렉토리 구조
```
.
├── LICENSE
├── README.md
└── web
    ├── .dockerignore
    ├── .elasticbeanstalk
    │   └── config.yml
    ├── .gitignore
    ├── Dockerfile
    ├── Procfile
    ├── README.md
    ├── app.js
    ├── bin
    │   └── www
    ├── compose.yaml
    ├── package-lock.json
    ├── package.json
    ├── public
    │   └── stylesheets
    │       └── style.css
    ├── routes
    │   ├── index.js
    │   └── users.js
    ├── tests
    │   ├── app.test.js
    │   └── routes.test.js
    └── views
        ├── error.jade
        ├── index.jade
        └── layout.jade

9 directories, 21 files
```


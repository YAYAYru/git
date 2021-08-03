# git
## GitHub and git [`link`](https://git-scm.com)
- Create repo in GitHub and git remote  [`YouTube`](https://youtu.be/kLKBcPonMYw?t=675)
- Как выложить свой проект на github [`YouTube`](https://youtu.be/CUDgSbaYGx4)
- Introduction to GitHub Project Boards [`YouTube`](https://youtu.be/idZyqNIrt84) YAYAY:Different Project Boards types
- Как перетащить папку с проектом в гитхаб [`YouTube`](https://youtu.be/mGLVGBBmqIc)
- GitHub: tasks, labels & milestones [`YouTube`](https://youtu.be/ukYSRu4k0gs)
- Github Project Management 1 [`YouTube`](https://youtu.be/RXEy6CFu9Hk) YAYAY: Simple and wow - tasks, labels & milestones
- Бесплатный хостинг GitHub Pages. Загрузка верстки на сервер. Работа с FTP [`YouTube`](https://youtu.be/84cyW2R9WWo)
- How Github Automated Kanban Made My Life Easier [`YouTube`](https://youtu.be/qRdht9CS_No) YAYAY:Вот был с Гришей
- git-hands-on [`GitHub`](https://github.com/dahlbyk/git-hands-on)
+ По рекомендации Хворостова В.А. A successful Git branching model [`nvie.com`](https://nvie.com/posts/a-successful-git-branching-model/) [`Хабр`](https://habr.com/ru/post/106912/) - это вот относится к работе в рамках одного репозитария. а если работать на github, то там есть еще возможность делать fork. это ветвление самих репозитариев целиком, а не только веток внутри. с помощью форков можно как раз сделать так, чтобы был один основной репозитарий у тебя, а, например, у Вадима репозитарий-черновик, связанный с основным. Тогда Вадим может в своем репозитарии создавать какие угодно ветки - это не будет засорять основной репозитарий, а в основной репозитарий изменения будут попадать через pull-request'ы из веток репозитария Вадима, так как его репозитарий будет связан. подробнее см. например [`git-scm.com`](https://git-scm.com/book/ru/v2/GitHub-Внесение-собственного-вклада-в-проекты) , но но в нашем случае дело немного осложняется тем, что у Вадима уже есть репозитарий, в котором он работает, а у тебя - нет. если ты создашь своей репозитарий, то его уже никак не связать с репозитарием Вадима. это можно решить парой способов:
  1. сделать трансфер с одного гитхаб-аккаунта (Вадима) на другой (твой) существующего репозитария, а потом, уже после того как репозитарий сменит аккаунт, Вадим создаст форк от него для себя. репозитарий тогда сохранит всю существующую историю коммитов/веток.
  2. если история коммитов не нужна или код из репозитария Вадима не нравится, то можно просто забыть про существующий репозитарий и создавать новый на твоем аккаунте с нуля, добавлять в него правильный код, а Вадим потом сделат от него форк и будет делать новые доработки
- GitHub Review • Exploring Workflows [`YouTube`](https://youtu.be/EwWZbyjDs9c)
- Русский справочник [`training.github.com`](https://training.github.com/downloads/ru/github-git-cheat-sheet/)
- Gitflow Workflow [`atlassian.com`](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
GitHub flow
- Understanding the GitHub flow [GitHub](https://guides.github.com/introduction/flow/) [pdf](https://guides.github.com/pdfs/githubflow-online.pdf)
- Understanding the GitHub flow [other paper with video](https://blog.sashido.io/the-github-flow-tips-and-tricks/)
- 

## ReadMe
- Awesome GitHub Profile README [`GitHub`](https://github.com/abhisheknaiidu/awesome-github-profile-readme)

## dvc [`link`](https://www.dvc.org)
- Install for Windows 
  - Download dvc-1.8.1.exe from [`offical site`](https://dvc.org/)
  - Install
  - Check `dvc version` in cmd that should output:
    - DVC version: 1.8.1 (exe)  
      Platform: Python 3.7.9 on Windows-10-10.0.18362-SP0  
      Supports: azure, gdrive, gs, hdfs, http, https, s3, oss, webdav, webdavs
- get-started [`Katacoda`](https://katacoda.com/dvc/courses/get-started) | [`dvc`](https://dvc.org/doc/start)
  - Initialize [`Katacoda`](https://katacoda.com/dvc/courses/get-started) | [`dvc`](https://dvc.org/doc/start)
  - Data Versioning [`katacoda`](https://katacoda.com/dvc/courses/get-started/versioning) | [`dvc`](https://dvc.org/doc/start/data-versioning)
- User Guide
  - Large Dataset Optimization [`dvc`](https://dvc.org/doc/user-guide/large-dataset-optimization)
- Command Reference
  - remote [`dvc`](https://dvc.org/doc/command-reference/remote)
    - remote add [`dvc`](https://dvc.org/doc/command-reference/remote/add)
- mnist [`Katacoda`](https://katacoda.com/dvc/courses/tutorials/mnist)
- MLOps Tutorials [`youtube`](https://www.youtube.com/playlist?list=PL7WG7YrwYcnDBDuCkFbcyjnZQrdskFsBz)
- Job: Senior Python Dev for Open Source Dev Tools [`StackOverFlow`](https://stackoverflow.com/jobs/446359/senior-python-dev-for-open-source-dev-tools-iterative-inc)
- Versioning Data with DVC (Hands-On Tutorial!) [`YouTube`](https://youtu.be/kLKBcPonMYw)
- MLOps Tutorial #2: When data is too big for Git [`YouTube`](https://youtu.be/kZKAuShWF0s) 
- MLOps Tutorial #3: Track ML models with Git & GitHub Actions [`YouTube`](https://youtu.be/xPncjKH6SPk)
- Why Git and Git-LFS is not enough to solve the Machine Learning Reproducibility crisis [`tds`](https://towardsdatascience.com/why-git-and-git-lfs-is-not-enough-to-solve-the-machine-learning-reproducibility-crisis-f733b49e96e8)
- How to Track your Development Process with DVC by Mark Keinhoerster and Tim Sabsch [`GitHub`](https://youtu.be/oF0qk3Q7g4E)
- Data versioning in machine learning projects - Dmitry Petrov [`YouTube`](https://youtu.be/BneW7jgB298)
- Course: Machine Learning experiments and engineering with DVC [`Udemy`](https://www.udemy.com/course/machine-learning-experiments-and-engineering-with-dvc/)
  - Tutorial: Versioning Data and Model [`GitHub`](https://github.com/mlrepa/dvc-2-data-versioning/blob/master/dvc-2-data-versioning.ipynb)
  - Tutorial: Automate DVC experiments [`GitHub`](https://github.com/mlrepa/dvc-3-automate-experiments)
  - Tutorial: CI/CD and MLOps with DVC [`GitLab`](https://gitlab.com/mlrepa/course-dvc-mlops/dvc-4-ci-mlops)
 

## Semantic Versioning
+ Семантическое Версионирование 2.0.0 на русском [`semver`](https://semver.org/lang/ru/)

## colab
Import custom .py module in Google Colab from GitHub URLs [`GitHub`](https://changhsinlee.com/colab-import-python/)

## Other
- Fullstack open source DevRel [`YouTube`](https://www.youtube.com/c/eddiejaoude/videos)

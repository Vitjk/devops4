## 13-14. Uzdevums
```sh
PS D:\PhpStormProjects\devops4> git ls-tree -r e7d3d1f2
100644 blob 4ee8e5c624cf5b923cd1e5093decfb154ebcf7b6    README.md
100644 blob c59743fe8a9f58dfe486281283938e2901374e78    module_1/README.md
100644 blob cd188f08029c6e482b3c1682df13553ac983fd69    module_1/github_logo.png
100644 blob e69de29bb2d1d6434b8b29ae775ad8c2e48c5391    module_2/README.md
100644 blob cd188f08029c6e482b3c1682df13553ac983fd69    module_2/github_logo.png

```
 
**hashes are similar** 

## 16. Uzdevums

```shell
 git log --since=2.weeks
```
```shell
 git log --since=2022-04-13
```

## 17. Uzdevums

```shell
 git log --author="Laura Pacilio"
```

## 18. Uzdevums
```shell
 git log --author="Laura Pacilio" --since=2021-09-01 --until=2021-09-30
```

## 19. Uzdevums
```shell
 git log --author="Laura Pacilio" --since=yesterday
```

## *
> commit f8493bf5cd78bc2a723f5ddc6f6bceb0e08813ea on Apr 21, 2021 => parent d351d712c44e15ac9698027dde0ca8c776697166
> 
> commit d351d712c44e15ac9698027dde0ca8c776697166 on Apr 16, 2021 

```shell
git commit-tree f8493bf -m "update hcl" -p d351d7
```

**Šķiet, ka tika izmantota commit-tree metode**
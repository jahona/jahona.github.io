---
layout: default
author: jill
---

# Jekyll Install 시 Error 시 해결방법

```
$ gem install bundler jekyll
$ jekyll new my-awesome-site
$ cd my-awesome-site
~/my-awesome-site $ bundle exec jekyll serve
```

Mac 에서 Ruby 의 패키지 매니저인 Gem 을 통해 설치를 진행하다 다음과 같은 에러가 생겼다.

```
$ gem install bundler
ERROR:  While executing gem ... (Gem::FilePermissionError)
    You don't have write permissions for the /Library/Ruby/Gems/2.3.0 directory.
```

[Mac에서 Gem::FilePermissionError 에러 발생시 해결 방법][ref1] 을 참고하여 해결하면 된다.


[ref1]: https://jojoldu.tistory.com/288
[ref2]: https://jekyllrb-ko.github.io/docs/
# Homepage

## Features

* Contact form
* Pre-built pages
* Pre-styled components
* Blog with pagination
* Post category pages
* Disqus comments for posts
* Staff and author system
* Configurable footer
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* RSS/Atom feed
* SEO tags
* Google Analytics

## 기본 정보 세팅 ⭐️

1. Add your site and author details in [`_config.yml`](https://github.com/dourowinekorea/dourowinekorea.github.io/blob/main/_config.yml).
2. Add your Google Analytics and Disqus keys to [`_config.yml`](https://github.com/dourowinekorea/dourowinekorea.github.io/blob/main/_config.yml).
3. 수정후 빌드 성공 확인 ([actions](https://github.com/dourowinekorea/dourowinekorea.github.io/actions))
4. 화면별 이미지/텍스트 수정:
    - [Home](https://github.com/dourowinekorea/dourowinekorea.github.io/blob/main/index.html)
    - [Blog](https://github.com/dourowinekorea/dourowinekorea.github.io/blob/main/blog/index.html)
    - [About](https://github.com/dourowinekorea/dourowinekorea.github.io/blob/main/about.html)
    - [Contact](https://github.com/dourowinekorea/dourowinekorea.github.io/blob/main/contact.html)

## 로컬 실행 방법

Frisco was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~


### Posts

* Add, update or remove a post in the *Posts* collection.
* The **Staff Author** field links to members in the **Staff Members** collection.
* Documentation pages are organised in the navigation by category, with URLs based on the path inside the `_docs` folder.
* Change the defaults when new posts are created in `_posts/_defaults.md`.

### Contact Form

* Preconfigured to work with CloudCannon, but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).

### Staff

* Reused around the site to save multiple editing locations.

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Navigation* section.

### Footer

* Exposed as a data file to give clients better access.
* Set in the *Data* / *Footer* section.

---

## Git 사용법
로컬 컴퓨터에 git 이 설치되어 있어야 합니다.

~~~sh
git clone (주소)
~~~

(변경사항 바로 올려서 적용한다고 가정하고)
파일 수정한 후에

~~~sh
git add .
git commit -m '(수정한 내용 메세지)'
git push origin main
~~~

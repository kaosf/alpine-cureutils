# cureutils on Docker

It's based on Alpine Linux for lightweight image.

Special thanks to @greymd

[dockerfiles/cureutils/debian at master · greymd/dockerfiles](https://github.com/greymd/dockerfiles/tree/master/cureutils/debian)

## Usage

Completely same to [greymd/cureutils](https://hub.docker.com/r/greymd/cureutils/).

```
# docker run kaosf/alpine-cureutils cure precures
美墨なぎさ
雪城ほのか
九条ひかり
...
```

```
# echo キュア{ハート,ダイヤ,エース,スペード} | xargs -n 1 | docker run -i --rm kaosf/alpine-cureutils cure grep
キュアハート
キュアエース
```

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (C) 2017 ka

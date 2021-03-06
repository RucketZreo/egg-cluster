
1.12.4 / 2017-10-29
==================

**others**
  * [[`b768018`](http://github.com/eggjs/egg-cluster/commit/b768018b77e1c6f80e8cfd9e9c38e63ec44a473d)] - refactor: use utility to read json (#49) (Haoliang Gao <<sakura9515@gmail.com>>)

1.12.3 / 2017-10-12
==================

**fixes**
  * [[`4b80f33`](http://github.com/eggjs/egg-cluster/commit/4b80f33d272b374e005f3dd2f9dc39865f0d3688)] - fix: master should exit when EADDRINUSE error (#48) (Haoliang Gao <<sakura9515@gmail.com>>)

1.12.2 / 2017-09-28
===================

**fixes**
  * [[`0c886a4`](https://github.com/eggjs/egg-cluster/commit/0c886a43ecac25e79de910cb04778efc77aab9a4)] - fix: should disable worker refork (#46) (fengmk2 <<fengmk2@gmail.com>>)

1.12.1 / 2017-09-22
==================

**fixes**
  * [[`30d120d`](http://github.com/eggjs/egg-cluster/commit/30d120dd292d79a25113c951664d18480dde2a00)] - fix: should send egg-ready when app/agent restarted after launched (#45) (Haoliang Gao <<sakura9515@gmail.com>>)

1.12.0 / 2017-09-14
==================

**features**
  * [[`56bff0d`](http://github.com/eggjs/egg-cluster/commit/56bff0dda04074cbd7259b2652954832647a9a61)] - feat: agent debugPort 5856 -> 5800 (TZ <<atian25@qq.com>>)

1.11.2 / 2017-09-13
==================

**features**
  * [[`61b5b66`](http://github.com/eggjs/egg-cluster/commit/61b5b660146b5ef3795f7f2fe4d61195ca6d93c1)] - feat: simplify debug error when kill by vscode (TZ <<atian25@qq.com>>)
  * [[`308d9fd`](http://github.com/eggjs/egg-cluster/commit/308d9fde230122dd1d85d9563dd64c5103f8a7df)] - feat: debug & egg-ready message (TZ <<atian25@qq.com>>)
  * [[`a4fa5f5`](http://github.com/eggjs/egg-cluster/commit/a4fa5f5171226354d02760edbfc20db8eca3f9e1)] - feat: delete default port options that has defined in egg (#40) (Haoliang Gao <<sakura9515@gmail.com>>)
  * [[`09ccc5a`](http://github.com/eggjs/egg-cluster/commit/09ccc5ab62bbac2a214d80589dcc1695adfb6b90)] - feat: revert to 1.9.2 (TZ <<atian25@qq.com>>)

**others**
  * [[`ab76a19`](http://github.com/eggjs/egg-cluster/commit/ab76a19a8275906df757d2a9e585ccd89c62f6a5)] - test: improve cov (TZ <<atian25@qq.com>>)

1.11.1 / 2017-09-11
==================

**fixes**
  * [[`8d46f20`](http://github.com/eggjs/egg-cluster/commit/8d46f20c04967647a1991736d2db2db0202790a2)] - fix: only set options.debugProtocol at debug mode (#42) (TZ | 天猪 <<atian25@qq.com>>)

1.11.0 / 2017-09-08
==================

**features**
  * [[`49bd949`](http://github.com/eggjs/egg-cluster/commit/49bd949a5271f0db86de6c4111fefbd6613017e1)] - feat: delete default port options that has defined in egg (#40) (Haoliang Gao <<sakura9515@gmail.com>>)

**others**
  * [[`0561ce7`](http://github.com/eggjs/egg-cluster/commit/0561ce7bd69151dd66b1e24352f4f0b632591a39)] - refactor: support debug options (#41) (TZ | 天猪 <<atian25@qq.com>>)
 * [new tag]         1.10.0     -> 1.10.0


1.10.0 / 2017-09-07
==================

**others**
  * [[`0561ce7`](http://github.com/eggjs/egg-cluster/commit/0561ce7bd69151dd66b1e24352f4f0b632591a39)] - refactor: support debug options (#41) (TZ | 天猪 <<atian25@qq.com>>)

1.9.2 / 2017-08-30
==================

**fixes**
  * [[`7277b00`](http://github.com/eggjs/egg-cluster/commit/7277b00516905f0e26c78c063b7f84044c069b6d)] - fix: debug status detect should support inspect (#39) (TZ | 天猪 <<atian25@qq.com>>)

1.9.1 / 2017-08-28
==================

  * fix: sleep 100ms to make sure SIGTERM send to the child processes (#37)
  * test: fix test that should mock the default port (#38)

1.9.0 / 2017-07-27
==================

  * feat: add listen config (#34)
  * refactor: disable console (#36)
  * deps: upgrade eslint (#35)
  * refactor: set agent worker and app worker console level (#33)
  * deps: upgrade dependencies (#32)

1.8.0 / 2017-06-12
==================

  * feat: use graceful-process to refactor app and agent worker (#30)
  * test: sleep 20s to wait for agent process start (#29)

1.7.0 / 2017-06-09
==================

  * feat: reduce info logs on local env (#28)

1.6.4 / 2017-05-28
==================

  * fix: agent should exit on disconnect event whatever master kill with SIGKILL (#27)

1.6.3 / 2017-05-22
==================

  * fix: fix typo (#24)
  * fix: start error should log what happend (#26)
  * fix: fix deperated api (#25)
  * deps: upgrade dependencies (#22)

1.6.2 / 2017-03-22
==================

  * fix: should print logger when agent start error (#20)

1.6.1 / 2017-03-03
==================

  * fix: sticky logic error (#19)
  * feat: use egg-utils (#18)

1.6.0 / 2017-03-01
==================

  * feat: add options framework (#17)

1.5.0 / 2017-02-21
==================

  * feat: exit when error emitted during start (#16)

1.4.0 / 2017-02-13
==================

  * feat:add sticky cluster mode (#14)
  * test: add test for agent debug port (#13)

1.3.0 / 2017-01-20
==================

  * feat: get clusterPort (#12)

1.2.0 / 2016-12-26
==================

  * feat: npm publish files limit (#10)

1.1.0 / 2016-12-20
==================

  * deps: upgrade dependencies
  * refactor: options should be passed through
  * feat: print env when start (#8)

1.0.0 / 2016-10-12
==================

  * feat: exit if worker start timeout (#6)

0.2.0 / 2016-10-12
==================

  * feat: when debug mode, master should exit when worker die (#7)
  * test: fix testcase (#5)

0.1.0 / 2016-08-16
==================

  * feat: [BREAKING_CHANGE] master won't load config  (#4)
  * test: add test cases (#3)

0.0.4 / 2016-07-16
==================

  * fix: remove antx loader (#2)

0.0.3 / 2016-07-16
==================

  * fix: loader version (#1)
  * fix: logger

0.0.2 / 2016-07-15
==================

  * init code

---
order: 5
title: Change Log
toc: false
timeline: true
---

`ng-zorro-antd-mobile` strictly follows [Semantic Versioning 2.0.0](http://semver.org/lang/zh-CN/).

#### Release Schedule

- Weekly release: patch version at the end of every week for routine bugfix (anytime for urgent bugfix).
- Monthly release: minor version at the end of every month for new features.
- Major version release is not included in this schedule for breadking change and new features.

---

## 0.9.4 (2018-10-10)


### Bug Fixes

* **button:** fix button with custom icon ([a3c6150](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/a3c6150))
* **ci:** fix ci node version ([312fce6](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/312fce6))
* **components:** change the way to import subject ([88864ab](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/88864ab))
* **date-picker:** fix invaild date ([6620635](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/6620635))
* **demo:** don’t  expand code ([6d65ebb](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/6d65ebb))
* **pulltorefresh:** fix demo pulltorefresh ([8725c4b](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/8725c4b))
* **input-item:** fixed custom-keyboard hide ([#21](https://github.com/fisherspy/ng-zorro-antd-mobile/issues/21)) ([9b8f3da](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/9b8f3da))
* **carousel:** fix last panel bug ([2c5cd92](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/2c5cd92))
* **tabs:** unable get offsetWidth & offsetHeight when setInkBarStatus at first time sometime ([#7](https://github.com/fisherspy/ng-zorro-antd-mobile/issues/7)) ([6502082](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/6502082))
* **steps:** udpate setTimeout time ([6da37ab](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/6da37ab))


### Features

* **ci:** update ci config ([0b178c4](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/0b178c4))
* **list-item:** remove classname ([#20](https://github.com/fisherspy/ng-zorro-antd-mobile/issues/20)) ([e0850f6](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/e0850f6))
* **modal:** add modal test ([#18](https://github.com/fisherspy/ng-zorro-antd-mobile/issues/18)) ([7c59b61](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/7c59b61))
* **template:** support issue and PR template ([bc59939](https://github.com/fisherspy/ng-zorro-antd-mobile/commit/bc59939))

## 0.9.0 (2018-09-29)

**NG-ZORRO** has a blue print for both desktop and mobile at the very beginning of the project.

According to the specification of **Ant Design Mobile**, **Alibaba Data Technology and Product** terminal team started to develop **NG-ZORRO-MOBILE** based on **Angular >=2** in June, 2016. To prove its ability also integrate it into production.

 In the last half year of 2017, **Ant Design Mobile of React** implementation started to redesign and implement with a brand new version **2.x**. To keep in pace with the React edtion, **NG-ZORRO-MOBILE** terminated the onging development and started a tight development of the all new **NG-ZORRO-MOBILE** corresponding to the **Ant Design Mobile of React 2.x**.

For now, based on the latest **Angular ^6.0.0** and **RxJS ^6.0.0** , **NG-ZORRO-MOBILE** have finished all the 45 components which exist in **Ant Design Mobile React 2.x**, and have integrated with **@angular/cli** for ease of use. Meanwhile, we share the same docs&website build system with **NG-ZORRO-DESKTOP** as a uniform style.

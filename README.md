# 伊贼瑞贝卡 (easyRBAC)
我要的很简单，基于RBAC管理权限，有容易上手的UI，最好送给我一个看得过去的SSO就更棒了


你们都不晓得欸，我每次遇到这种需求有多惨！原来在某银行上班的时候，我就是想给我的一组API加权限，他有一套权限管理系统，但是因为和组织架构强绑定，如果我加入应用系统用户就和组织架构冲突了，然后我就被虐啊虐！

还有一些行为很奇葩的权限管理系统，逻辑关系烧脑。我要的不难，就那么一点点功能，如果你要绑定组织架构，请基于此开发上层应用，这东西是个小纯洁，他就管理资源，管理用户，管理资源-用户的绑定关系。我认为是个基础组件。而组织架构是应用系统！应用系统！应用系统！！！

我现在又遇到了很多这样的权限管理的需求，大的小的系统，只要有后台的系统都会要这玩意儿，我真是怕了~那我就做一个，OK？

ps:当年要是有个这种小清新多美好啊~

***
## Road Map

- [x] 用户编辑、增删
- [x] 用户分组
- [x] 用户分组权限
- [x] 用户权限
- [x] 范围管理权限
- [x] SSO
- [x] 用户信息
- [ ] 后台授权、鉴权
- [ ] Swagger支持
- [ ] SSO后系统获取用户ACL

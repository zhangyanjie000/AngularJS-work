# AngularJS-work


# 实现的功能或效果： </br>
1、双向数据功能</br>
如： </br>
1-1：从控制器或服务器读取数据 </br>
1-2：为文本域添加双向数据绑定 </br>
1-3：用户的头像、昵称、发表的文本、粉丝等信息实现双向数据绑定 </br>
</br>
2、导航条效果 </br>
如： </br>
2-1：ng-repeat 实现导航条 </br>
2-2：下拉菜单（可结合 bootstrap 实现） </br>
2-3：手风琴菜单</br>

4、视图和路由 </br>
4-1：首页各模块使用视图和路由实现单页面应用。ng-view 对应的文件存放到 view 文件夹中。 </br>
4-2：创建 “简介”按钮对应用的视图，并使用视图和路由实现单页面应用。ng-view 对应的文件存 放到 view 文件夹中。 </br> 
4-3：创建 “消息”按钮对应用的视图，并使用视图和路由实现单页面应用。ng-view 对应的文件存 放到 view 文件夹中。 </br>
</br>
# 思路</br>
1、从控制器中读取数据；定义控制器，在控制器中声明变量初始值。</br>
2、为文本域添加双向数据绑定；ng-model 创建一个双向数据绑定，绑定html表单元素到$scope变量中去。</br>
3、手风琴菜单，利用ng-show操作，当click“操作”按钮，ng-show=”true”,再次点击时候，ng-click=”false”。实现显示隐藏。</br>
4、粉丝排序显示；利用过滤器，orderBy过滤器对数组中的对象进行排序，默认排序为升序排序。</br>

zk-angular
==========

# A ZK extension for Angular JS

This project aims to provide a convenient way for Java developers to bind the data from server to client and vise versa.
It contains both powers of [AngularJS][angularjs] and [ZK MVVM][mvvm]; __AngularJS__ 
is a structural framework for dynamic web applications and provides a complete client-side solution.
__ZK MVVM__ is a data binder to synchronize data between the View (__ZUL Page__) and ViewModel (__Java Object__),
in this project the View will be the __AngularJS__'s template (HTML & CSS). The following figure illustrates the whole concept of this project.

![ZK Angular Architecture](https://raw.githubusercontent.com/zkoss/zk-angular-demo/master/src/main/webapp/img/zk-ng-architecture.png)

### Version

0.8.0

### Maven Installation
	
	<dependency>
		<groupId>org.zkoss.angular</groupId>
		<artifactId>zk-angular</artifactId>
		<version>0.8.0</version>
	</dependency>

### Demo Project

 *  [ZK Angular Demo](https://github.com/zkoss/zk-angular-demo)
	
### License

 * [GPL v2](http://www.gnu.org/licenses/gpl-2.0.html)

 
[angularjs]: https://angularjs.org/
[zk]: http://www.zkoss.org
[mvvm]: http://books.zkoss.org/wiki/ZK%20Developer's%20Reference/MVVM
[bootstrap]: http://getbootstrap.com/
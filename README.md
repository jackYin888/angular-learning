#### $scope 



 controller 存在独立作用域，子控制器可继承父控制器属性

 var app = angular.module('myApp', []);

   * 代码压缩混淆的时候回调跳过字符串，所以可以通过以下方式来替换$scope

   * $rootScope 属于全局作用域

   
    app.controller('controller_first', ['$scope', function($s) {
            $s.name = 'JackYin'
        }])
        

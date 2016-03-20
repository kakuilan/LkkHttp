LkkHttp class
==========

php的http类，其中的request异步并发请求支持apache和nginx。
  
  使用方法:
  
  $http  = new LkkHttp();
  
  $get     = $http->get('http://www.oschina.net/');
  
  $code    = $http->getHttpStatusCode('http://www.oschina.net/');
  
  $request = $http->request('http://www.oschina.net/');
  
  $file    = $http->save('http://www.oschina.net/', __DIR__);

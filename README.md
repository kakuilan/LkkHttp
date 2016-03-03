myHttp asynHandle
==========

php的http类，其中的request异步并发请求支持apache和nginx。
  使用方法:
  $myHttp  = new myHttp();
  $get     = $myHttp->get('http://www.oschina.net/');
  $code    = $myHttp->getHttpStatusCode('http://www.oschina.net/');
  $request = $myHttp->request('http://www.oschina.net/');
  $file    = $myHttp->save('http://www.oschina.net/', __DIR__);

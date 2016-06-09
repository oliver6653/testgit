1111111111
2222222
3333gggg

 webView.setWebViewClient(new WebViewClient(){     
                public void onReceivedSslError(WebView view, SslErrorHandler handler, SslError error){     
                          //handler.cancel(); 默认的处理方式，WebView变成空白页     
//                        //接受证书     
                    handler.proceed();  
                         //handleMessage(Message msg); 其他处理     
               }  
         });  
		 
		 
		 F:\androidstudio\AndroidStudioProjects\demo\CircleDemo-master\CircleDemo\app\src\main\java\com\yiw\circledemo
		 
		 
		 
		 kkkkkkkkkkkkkkkkk
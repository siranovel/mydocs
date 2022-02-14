libproxyjniの機能仕様書
=======================
1. 目的

   c言語からjavaクラス内のメゾッドを、呼び出すことができる

1. 前提

    サポートOS: linux x86_64  
    サポート動的プログラム: java 11以降  

1. 機能範囲

    ![](images/ucProxyJNI.jpg)  

1. 機能範囲外

1. 制限事項

    同じメゾットが複数ある場合は、先頭のみ呼び出せる

1. 詳細機能

    ![](images/actProxyJNIMethod.jpg)  
    ![](images/actProxyJNIField.jpg)  
    ![](images/actSysProp.jpg)  


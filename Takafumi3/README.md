### コンパイラのバージョン
gcc 9.3.0
### 実行ファイルのサイズ
※program/source/にあるソースの実行ファイルのコードサイズを示したものである。  
  
**SAS-2**  
* 32bit  
  * server:22.3KB  
  * client:21.4KB  
* 64bit  
  * server:26.3KB  
  * client:21.4KB  
* 256bit  
  * server:22.4KB  
  * client:21.5KB  
  
**SAS-L2**  
* 32bit  
  * server:22.4KB  
  * client:17.2KB  
* 64bit  
  * server:26.4KB  
  * client:17.2KB  
* 256bit  
  * server:22.5KB  
  * client:17.2KB  
### ファイル構成
SAS-2-- 32bit(認証情報を32bitとしたSAS-2プログラム)---client_data(被認証側のデータ保存場所)  
     |_ 64bit                                    |_ server_data(認証側のデータ保存場所)  
     |_ 256bit                                   |_ exp(SAS-2の評価実験用ソース)  
                                                 |_ source(SAS-2のソース)  

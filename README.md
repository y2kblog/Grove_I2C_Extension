# Grove用I2C通信距離延長基板（2個セット）

<img src="/images/Product_Photo.jpg" width="300px">  

NXP社の高ドライブ電流型のI2CバスバッファPCA9600Dを用いてI2Cの信号線の許容負荷容量を増加させ、I2C接続のGroveモジュールの通信距離を延長するための基板です。  
基板同士は一般的なストレート結線のLANケーブルで接続します。LANケーブルは入手性が良いため、マイコンとGroveモジュール間の通信距離が数m～数10mのシステムを容易に構築できます。

<img src="/images/connection.jpg" width="600px">  

## 内容物  

<img src="/images/Package_contents.jpg" width="500px">  

## 別途ご用意いただく物  

- <a href="https://www.switch-science.com/catalog/2376/">PCA9600D 高ドライブ電流I2Cバスバッファ基板</a>
- Groveケーブル
- LANケーブル

## 回路図  

<img src="/images/CircuitDiagram.png" width="500px">  


## 基板寸法  

<img src="/images/PCB_size.png" width="200px">  


## 接続例  
<img src="/images/connect_example.jpg" width="350px">  

20mのLANケーブル(エレコム社LD-CTT/BU200)を用いて通信テストを行い、Fast mode(400kbps)で問題なく通信できました。

## 組立方法  
以下の画像に示すように延長基板に部品をはんだ付けします。  

<img src="/images/Assemble1.jpg" width="200px">  

別途ご用意いただいたPCA9600D基板に付属の細ピンヘッダをはんだ付けし、PCA9600D基板上のシルクと延長基板上のシルクが一致する向きにICソケットに挿します。  

<img src="/images/Assemble2.jpg" width="200px">  

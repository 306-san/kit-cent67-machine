# kit-cent67-machine
+ ある大学で授業で使う環境をVagrantで実行できるようにしました。
+ 学校で指定されたisoからbox作成してるので差異が少ないので安心して利用できるかと
+ 使ったisoはCentOS-6.7-x86_64-bin-DVD1.isoになります
+ **最新の環境じゃないと動かないです**

### 使い方

まずは、以下のリンクからboxをDL（1.2GB）  
https://docs.google.com/uc?export=download&confirm=Z52T&id=0B7yIaq7QMg_7LWVmNVN5YmNYY00  
そんでDLしたところで、

```bash
$vagrant box add kit-cent67 kit-cent67.box
```
あとはこれをcloneして
```bash
$vagrant up
```
するだけ

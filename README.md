# gan_torch_mnist
mnistを学習するGAN. pytorchを用いている.  

## usage
### training
1. pythonのinstall  
2. packageのinstall  
```
pip install -r requirements.txt
```
3. training  
```
python train.py
```
4. 結果の確認  
学習終了後, ディレクトリ内にresultフォルダが作成されているため確認

### attention
mnistが存在しない場合, downloadを行うため, ネット環境が必要  

## abstract
GAN(Generative Adversarial network)は生成モデルと識別モデルから成る.  
- Disctiminator(識別モデル)  
入力されるサンプルが生成モデルの分布から来たものか, 実際のデータ分布から来たものかを識別できるように学習する.  
- Generator(生成モデル)  
識別モデルに贋作と見破られないサンプルを生成するように学習を行う. 乱数からサンプルを生成する.  

## training result example
### 学習過程
- 1epoch  
![1](https://user-images.githubusercontent.com/54930418/74580230-12383500-4fe5-11ea-9e18-675ba8f18d94.png)

- 25epoch  
![25](https://user-images.githubusercontent.com/54930418/74580240-43186a00-4fe5-11ea-8968-31e44ee62107.png)

- 200epoch  
![198](https://user-images.githubusercontent.com/54930418/74587796-599ce080-503a-11ea-84bd-109701f13664.png)

- gif  
![index](https://user-images.githubusercontent.com/54930418/74587869-332b7500-503b-11ea-97da-f255aa978968.gif)
<Paste>

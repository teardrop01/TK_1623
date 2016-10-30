# OneNightWerewolf Bot
## 製品概要
### Play Tech

### 背景（製品開発のきっかけ、課題等）
何を創ろうかと話し合ったときに、ChatBotで何かやりたいよねという話になりました。チーム全員ゲームが好きなので、PlayTechで考えた時に、人狼をLINEBOTでやろうよ！という話になりました。
従来の人狼の課題として挙げられるのが、
* 人がある程度集まらないと出来ない
* 対面でやる場合は同じ場所に居なければいけない
* アプリを使う場合でも文字ばかりのチャット形式・掲示板形式で使い勝手が悪い  
です。  

### 製品説明（具体的な製品の説明）   

### 特長  
####1. MessagingAPIを利用した見やすいUI
####2. 離れていても手軽に人狼を楽しめる
####3. ワンナイト人狼なので少人数（３人～）で楽しめる
![Alt text](/images/icon.jpeg)  
ワンナイト人狼のゲームマスター(GM)をやってくれるLINEBOTです。  
  
![Alt text](/images/S__42287136.jpg)  
個人チャットで参加申請を出すことでゲームに参加できます。  
  
![Alt text](/images/S__42287132.png)  
トークルームにBOTを招待してゲーム開始のコマンドを発言するとゲームが開始されます。  
  
![Alt text](/images/S__42287129.png)
![Alt text](/images/S__42287128.png)  
夜時間は役職を配られ、個人チャットで役職の行動をします。  
  
![Alt text](/images/S__42287131.png)  
全員の行動が終わった後に夜時間を終えると議論時間が始まります。議論時間中に投票が可能です。  
  
![Alt text](/images/S__42287130.png)  
投票は個人チャットで行います。  
  
![Alt text](/images/S__42287133.png)  
全員の投票が終わった後にゲームを終わらせると結果が開示されます。  
  

### 解決出来ること
課題点として挙げた３つすべてを解決できます。また、LINE単体で楽しめる要素が一つ増え、他のSNSよりもLINEの利用頻度が高くなると推測できます。具体的に言うとオンライン人狼でメジャーなのはSkypeを利用して人狼をすることなのですが、Skype人狼には他にツールが必要になります。しかし、LINEではツールは不要なので、より手軽にできるというメリットが生まれ、利用頻度が高くなると推測できるというわけです。
### 今後の展望
まだ、完成には至っておらず、完成させたいと考えています。完成したら、配役カスタマイズの実装、タイマーの実装等、機能面の拡張を行っていきたいと思います。また、ワンナイト人狼に限らず、通常の人狼BOTもLINEBOTで開発したいですね。  
### 注力したこと（こだわり等）
* 占い先指定や投票等をButtonsで実装した（UIを凝った）
* 雰囲気のある役職の絵を描いた

## 開発技術
### 活用した外部技術
#### API・データ
* Messaging API

#### フレームワーク・ライブラリ・モジュール
* PHP
* Heroku
* MySQL

#### デバイス
* LINEを利用できるデバイス全般

### 独自技術
#### 期間中に開発した独自機能・技術
* 特に無し

#### 研究内容（任意）
* 特に無し
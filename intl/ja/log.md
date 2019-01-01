# 100 Days Of Code - 学習ログ

## 1日目: 2018/11/23 Fri
### **今日の進捗**
Railsチュートリアル  
１章：ゼロからデプロイまで、２章：Toyアプリケーション

Rails Tutorial  
Chapter1 : Deploy for the first time, Chapter2 : Toy_app

### **思ったこと**
scaffoldを用いた簡易なページ生成が非常に楽だった。  
また、Heroku(本番環境)へのデプロイがただgit pushするだけなのが意外だった。

It's so easy to create pages with MVC architecture using scaffold,  
to deploy source code into production using git push command as well.

### **リンク**
[Chapter1](https://github.com/Natch/railstutorial_hello_app)
[Chapter2](https://github.com/Natch/railstutorial_toy_app)



## 2日目: 2018/11/24 Sat
### **今日の進捗**
Railsチュートリアル  
３章：ほぼ静的なページの作成

Rails Tutorial  
Chapter3 : create static pages

### **思ったこと**
MVC作成流れはcakeと同じ。しかしgenerateコマンドの点で便利。  
テスト駆動開発はだいぶ疎かだったので、学びが大きい。

Create Flow using rails is the same as cakePHP, but more useful in the terms of generate command existing.  
I've learned a lot of TDD since testing is neglect previously.

### **リンク**
[Chapter3](https://github.com/Natch/railstutorial_sample_app)



## 3日目: 2018/11/26 Mon
### **今日の進捗**
Railsチュートリアル  
４章：Rails風味のRuby

Rails Tutorial  
Chapter4 : Rails flavored ruby

### **思ったこと**
自然言語に近い形でコードを表現できて、人間フレンドリーな言語だ。  
今まで経験した言語で、最も好きな設計思想を持った言語

Ruby is constructed as a human-friendly language so that we can express coding like using natural language.  
It has the most favorite design philosophy for me since I`ve experienced so far.

### **リンク**
[Chapter4](https://github.com/Natch/railstutorial_sample_app)



## 4日目: 2018/11/28 Wed
### **今日の進捗**
Railsチュートリアル  
５章：レイアウトを作成する

Rails Tutorial  
Chapter5 : create layouts

### **思ったこと**
Asset Pipeline機構により、SCSSなどをいちいちトランスパイルする手間がなくて便利  

We don't need to transpile each times (e.g. modify SCSS) with the Asset Pipeline mechanism,  
that is, convenient.

### **リンク**
[Chapter5](https://github.com/Natch/railstutorial_sample_app)



## 5日目: 2018/11/29 Thr
### **今日の進捗**
Railsチュートリアル  
６章：ユーザーのモデルを作成する

Rails Tutorial  
Chapter6 : create user's model

### **思ったこと**
railsの規約に則ることで、パスワードのハッシュ化や  
バリデーションを考慮したモデルの構築が簡単にできる。

By following the rules of rails,  
It is easy to construct a model that considered password hashing and validation.

### **リンク**
[Chapter6](https://github.com/Natch/railstutorial_sample_app)



## 6日目: 2018/12/01 Sat
### **今日の進捗**
Railsチュートリアル  
７章：ユーザー登録

Rails Tutorial  
Chapter7 : register users

### **思ったこと**
routes.rbファイルにresourcesを指定することで、RESTfulなルーティングをデフォルトで用意してくれる！

Specifying resources in the routes.rb file can prepare RESTful routing for my app easily.

### **リンク**
[Chapter6](https://github.com/Natch/railstutorial_sample_app)



## 7日目: 2018/12/05 Wed
### **今日の進捗**
Railsチュートリアル  
８章：基本的なログイン機能
９章：発展的なログイン機能

Rails Tutorial  
Chapter8 : basic login function
Chapter9 : advanced login function

### **思ったこと**
テストをどの程度作り込めばいいか判断が難しい

It is difficult to judge how much the test should be built.

### **リンク**
[Chapter7,8](https://github.com/Natch/railstutorial_sample_app)



## 8日目: 2018/12/06 Thr
### **今日の進捗**
Railsチュートリアル  
１０章：ユーザーの更新・表示・削除

Rails Tutorial  
Chapter10 : User update, disp, delete

### **思ったこと**
gem万能。ページネーションやダミーデータなども簡単にできる。

Gem is versatile.  
A function such as pagination and dummy data can be implemented easily using it.

### **リンク**
[Chapter10](https://github.com/Natch/railstutorial_sample_app)



## 9日目: 2018/12/10 Mon
### **今日の進捗**
Railsチュートリアル  
１１章：アカウントの有効化

Rails Tutorial  
Chapter11 : activate accounts

### **思ったこと**
メタプログラミングの一手法である動的ディスパッチによって、動的に呼び出すメソッドを指定できる。

Dynamic dispatching a kind of metaprogramming allows me to specify methods to be called dynamically.

### **リンク**
[Chapter11](https://github.com/Natch/railstutorial_sample_app)



## 10日目: 2018/12/12 Wed
### **今日の進捗**
Railsチュートリアル  
１２章：パスワードの再設定

Rails Tutorial  
Chapter12 : Password reset

### **思ったこと**
ユーザに入力させる必要がないけど、ほしいという情報をビューに埋めるという手段を知った。（メールアドレスなど）

I've learned the means that fill the view with the information we need but let a user enter it.

### **リンク**
[Chapter12](https://github.com/Natch/railstutorial_sample_app)



## 11日目: 2018/12/14 Fri
### **今日の進捗**
Railsチュートリアル  
１３章：ユーザーのマイクロポスト

Rails Tutorial  
Chapter13 : user's microposts

### **思ったこと**
メソッドチェーンを駆使して、関連付けられたモデル群を取り出すことができる。

Using the method chain allow us to retrieve the associated model group.

### **リンク**
[Chapter13](https://github.com/Natch/railstutorial_sample_app)



## 12日目: 2018/12/18 Tue
### **今日の進捗**
Railsチュートリアル  
１４章：ユーザーをフォローする

Rails Tutorial  
Chapter14 : follow a user

### **思ったこと**
チュートリアル完走！  
レールから外れた柔軟な実装手法も学ぶことができた。

I've finally completed rails tutorial!  
I also learned flexible methodology without predetermined rail.

### **リンク**
[Chapter14](https://github.com/Natch/railstutorial_sample_app)



## 13日目: 2019/01/01 Tue
### **今日の進捗**
Ruby on Rails 5 アプリケーションプログラミング
５章：モデル開発

Ruby on Rails 5 Application Programming
Chapter05 : Model development

### **思ったこと**
想定するモデルが実際にありそうであったのと、  
丁寧な図示によってアソシエーションの理解が深まった。

The understanding of the model association deepened  
thanks to the polite illustration and used model for learning was actually likely.

### **リンク**
[railbook](https://github.com/Natch/railbook)
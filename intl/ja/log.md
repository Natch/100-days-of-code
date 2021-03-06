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



## 14日目: 2019/01/04 Fri
### **今日の進捗**
Ruby on Rails 5 アプリケーションプログラミング  
６章：コントローラ開発

Ruby on Rails 5 Application Programming  
Chapter06 : Controller development

### **思ったこと**
ログインや例外などの共通処理のテクニックがためになった。

Techniques for common processing  
such as login and exception was informative for me.

### **リンク**
[railbook](https://github.com/Natch/railbook)



## 15日目: 2019/01/06 Sun
### **今日の進捗**
Ruby on Rails 5 アプリケーションプログラミング  
７、８章：ルーティング、テスト

Ruby on Rails 5 Application Programming  
Chapter07,08 : Routing, test

### **思ったこと**
resourcesメソッドのネストにより生成されるルートが理解できた。

I understand the route rule generated by nesting the resources method.

### **リンク**
[railbook](https://github.com/Natch/railbook)



## 16日目: 2019/01/07 Mon
### **今日の進捗**
Ruby on Rails 5 アプリケーションプログラミング  
９章：クライアントサイド開発

Ruby on Rails 5 Application Programming  
Chapter09 : Client side development

### **思ったこと**
Turbolinksの仕組みを学んだ。  
クライアントとサーバを切り分けて開発するときは、停止して開発することになりそう。

I learned the mechanism of Turbolinks.  
When separating client and server and developing,  
it seems that I need to stop it.

### **リンク**
[railbook](https://github.com/Natch/railbook)



## 17日目: 2019/01/10 Thr
### **今日の進捗**
Ruby on Rails 5 アプリケーションプログラミング  
１０章：Railsの高度な機能

Ruby on Rails 5 Application Programming  
Chapter10 : Rails advanced function

### **思ったこと**
約７００ページのrails基礎本を読了🙌  
非同期処理のモジュール(active_job)やキャッシュは、  
やはり実際に運用しないと効果が実感できない。

I Read about 700 pages of rails basic book.  
Asynchronous processing module (active_job) and cache function  
are not operated production environment, so I could not see the effect of it.

### **リンク**
[railbook](https://github.com/Natch/railbook)



## 18日目: 2019/02/12 Tue
### **今日の進捗**
記録再開✍️  
この１ヶ月間で学んだこと  
・CodingTest (e.g. live-coding, codility) の対策に注力した。  
・チェリー本:「プロを目指す人のためのRuby入門」を読了。  

また、タスク管理アプリの作成を通して、現場で使える知識を学び中  
「現場で使えるRuby on Rails5 速習実践ガイド」  

Resume recording ✍️  
What I've learned in the past month  
· I focused on taking measures for CodingTest. (e.g. live-coding, codility)  
· "Introduction to Ruby for those who aim at professional" I read this book.  

In addition, through the creation of the task management application,  
learning knowledge can be used on job scene.  

### **思ったこと**
次回から記録  

### **リンク**
[プロを目指す人のためのRuby入門](https://github.com/Natch/rubybook)  
[現場で使えるRuby on Rails5 速習実践ガイド](https://github.com/Natch/taskleaf)



## 19日目: 2019/02/14 Thr
### **今日の進捗**
「現場で使えるRuby on Rails5 速習実践ガイド」
Chapter5  
Rspec, Capybara, FactoryBotを用いたTask管理アプリケーションのシステムテスト  

System test of Task management application using Rspec, Capybara, FactoryBot  

### **思ったこと**
まだ基礎レベルだが、RspecはMinitestよりも実装の仕方に柔軟性があり、より自然言語に近い記述ができて好きだ。  
Capybaraと組み合わせたブラウザシミュレーションやDBのロールバックをテスト終了後にしてくれるのがよきかな。

Although my skill level is basic, Rspec is more flexible than Minitest,  
and it makes us possible to write description close to natural language like English.  

It is good to do browser simulation combined with Capybara and rollback of DB after the test.  

### **リンク**
[現場で使えるRuby on Rails5 速習実践ガイド](https://github.com/Natch/taskleaf)



## 20日目: 2019/02/17 Sun
### **今日の進捗**
「現場で使えるRuby on Rails5 速習実践ガイド」
Chapter7  
機能拡張：確認画面、検索機能、ソート機能、メール送信、ファイルアップロード、CSVインポート/エクスポート、ページネーション  

Enhancements : Confirmation screen, search function, sort function, mail transmission, file upload, CSV import/export, pagination  

### **思ったこと**
ransack, csv, kaminariは有用なgemなので、覚えておく。

'ransack', 'csv', and 'kaminari' are useful gems.  
so I need to remember them.  

### **リンク**
[現場で使えるRuby on Rails5 速習実践ガイド](https://github.com/Natch/taskleaf)



## 21日目: 2019/02/20 Wed
### **今日の進捗**
「現場で使えるRuby on Rails5 速習実践ガイド」
Chapter8  
Ajaxによるサーバ通信  

Server communication by Ajax  

### **思ったこと**
クライアントのイベント実行の方法として、  
Server-generated JavaScript Responses (SJR)によるAjax実装がある。  

SJRはHTTPレスポンスボディにJSを渡すことで実現できてrubyコードをembedできるメリットがある一方で、共通管理がしづらい。  

As a method of client event execution,  
There is Ajax implementation method by Server - generated JavaScript Responses (SJR).  

While SJR can be realized by passing JS to HTTP response body  
and has merit that it can embed ruby code,  
but it is hard to manage Javascript codes.  

### **リンク**
[現場で使えるRuby on Rails5 速習実践ガイド](https://github.com/Natch/taskleaf)



## 22日目: 2019/03/17 Sun
### **今日の進捗**
Everyday Rails - RSpecによるRailsテスト入門
Chapter01-03 : モデルスペック

Everyday Rails - Introduction of Rails Testing with RSpec
Chapter01-03: Model Specifications

### **思ったこと**
describeとcontextはアウトライン化して文脈を解釈しやすくなるため、しっかり分けて記述したい。  
itから始まるexampleの記述は英語のほうがコードの上では解釈がしやすい。  

I'd like to separate out describe and context  
that enables us to interprete codes easily by outlined.  



## 23日目: 2019/04/30 Tue
### **今日の進捗**
Everyday Rails - RSpecによるRailsテスト入門
Chapter04-05 : 意味のあるテストデータの作成、コントローラスペック

Everyday Rails - Introduction of Rails Testing with RSpec
Chapter04-05: Create meaningful test data, Controller Spec

### **思ったこと**
FactoryBotによるテストデータの作成においてDRYを保つためには、traitが有用だった。  

The trait was useful for keeping DRY in creating test data with FactoryBot.  



## 24日目: 2019/05/02 Wed
### **今日の進捗**
Everyday Rails - RSpecによるRailsテスト入門
Chapter06-07 : フィーチャスペック、リクエストスペック

Everyday Rails - Introduction of Rails Testing with RSpec
Chapter06-07: Feature Spec, Request Spec

### **思ったこと**
今後、APIの設計が重要課題となりそうなので、リクエストスペックは覚えておきたい。

In the future, API design is going to be an important issue,  
so I would like to remember the Request Spec.  



## 25日目: 2019/05/12 Sun
### **今日の進捗**
Everyday Rails - RSpecによるRailsテスト入門
Chapter08-09 : スペックをDRYに保つ、早くテストを書き、早いテストを書く

Everyday Rails - Introduction of Rails Testing with RSpec
Chapter06-07: Keep Specs on DRY, Write a test fast, write a fast test

### **思ったこと**
DBの読み書きが多い場合や、メソッドの返却値が決まっている場合は、  
テスト実行時間を早めるために、積極的にモックやスタブを使っていきたい。  

In case that reading and writing to DB occured many times, or return values of any methods are already determined,  
I'd like to use mocks and stubs positively to speed up the test for execution time.  

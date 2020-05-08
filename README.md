# django_tutorial

以下サイトをもとにチュートリアルをまとめる。

https://tutorial.djangogirls.org/ja/


## 仮想環境のセットアップとDjangoのインストール

仮想環境(myvenv)の作成  
python3 -m venv myvenv

仮想環境(myvenv)の実行  
source myvenv/bin/activate

## プロジェクト(mysite)を作成  
django-admin startproject mysite .

## ウェブサーバを起動する  
python manage.py runserver

## 新しいアプリケーションの作成
python manage.py startapp blog

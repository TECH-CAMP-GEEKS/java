# java

## javaの開発方法（eclipse使用しない）

1. JDKをインストールする

  以下のコマンドを実行してjavaがインストールされているか確認する

  ```
  $ javac --version
  ```

  入っていなければ、以下の[サイト](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)からJDKをインストールする
  
  ![https://i.gyazo.com/28e95529f4f9e664840ae8a72cd0e02b.png](https://i.gyazo.com/28e95529f4f9e664840ae8a72cd0e02b.png)
  
2. Hello.javaというファイルを作成する
  ```
  $ vim Hello.java
  ```
3. 以下のような記述をする
  ```
  public class Hello {
    public static void main(String[] args) {
      System.out.println("Hello World!");
    }
  }
  ```
4. コンパイルする
  ```
  $ javac Hello.java
  // Hello.class というファイルが生成される
  ```
5. クラスを実行する
  ```
  $ java Hello
  ```

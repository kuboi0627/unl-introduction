**ユースケース図：ATMで「お金を引き出す」**  
概略：銀行のATMを利用して、自分の口座からキャッシュカードで必要なお金を引き出します。  
アクター：利用者  
事前条件：アクターが口座とキャッシュカードを持っていること。  
事後条件：アクターの口座から指定された金額が引き出されること。  
イベントフロー  
**【基本フロー】**  
1.ATMの画面にある「引き出し」を選択すると、ユースケースが開始する。  
2.ATMへキャッシュカードを入れる。
3.暗証番号を入力する。(E-1)  
4.引き出したい金額を入力する。　　
5.引き出した金額を確認する。  
6.ご利用控の「要/不要」を選びます。  
7.カード、ご利用控、現金を受け取ると、ユースケースが終了する。  

**【代替フロー】**  
E-1.暗証番号を間違える。  
  1.暗証番号を入力する画面に戻る。  
 
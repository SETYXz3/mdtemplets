**markdownファイル作成チートシート：**

### 見出し

```
# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
```



### カスタムフォント

<span style="background-color:hotpink; border-radius:5px">　角丸背景文字　</span>

````html
<span style="background-color:hotpink; border-radius:5px">　角丸背景文字　</span>
````

<span style="background-color:springgreen">　背景文字　</span>

<span style="color:red"> 文字色  </span>

<span style="font-size:15px;font-style:italic">  文字斜め </span>

X<sub>2</sub>　　`X<sub>2</sub>`

X<sup>2</sup>　　`X<sup>2</sup>`

<s>打ち消し</s>　　`<s>打ち消し</s>`

<u>下付き線</u>　　`<u>下付き線</u>`

<span style="border: 1px red solid; padding: 1px;">赤い枠</span>　　`<span style="border: 1px red solid; padding: 1px;">赤い枠</span>`



### チェックリスト

- [ ] <span style="background-color:hotpink; border-radius:5px">　Flutter　</span> タスクflutter <span style="background-color:coral; border-radius:6px">　優先　</span>
- [ ] <span style="background-color:springgreen; border-radius:5px">　blackchain　</span> dev環境inhouseの配布  <span style="background-color:springgreen; border-radius:6px">　Due: 01/20　</span>
- [ ] <span style="background-color:salmon; border-radius:30px">　blackchain　</span> icon案の修正  <span style='background-color:bisque;border-radius:6px'>　Due: 01/20　</span>
- [ ] <span style='background-color:blueviolet;color:white;border-radius:5px'>　FIDO2　</span> keycloak serverの構築  <span style='background-color:aqua;border-radius:5px 0px 5px 0px'>　Due: 01/20　</span>
- [ ] <span style='background-color:grey;color:white;border-radius:50%'>１</span> 丸いリスト番号



### コメント

> **コメント**
>
> サンプルコメントです。
>
> サブコメント
>
> >サブサンプルコメントです。



### ソースコード

```java
class hello {
  public static void main(args[] arg){
    println("Hello world!!!");
  }
}
```



### code diff

```diff
diff sample:
- aaaa
+ bbbb
```



### 色付き文言

<p style="background-color:mistyrose; border-radius:5px">　注意：<br>　注意の文言</p>

<p style="background-color:lightsalmon; border-radius:5px">　警告：<br>　警告の文言</p>

<p style="background-color:deepskyblue; color: black; border-radius:10px 0px 10px 0px">　Tip：<br>　Tipの文言、角丸カスタマイズできる。</p>

<p style="background-color:lemonchiffon; color: red; border-radius:0px 10px 0px 10px">　Tip：<br>　重要の文言、角丸カスタマイズできる。</p>


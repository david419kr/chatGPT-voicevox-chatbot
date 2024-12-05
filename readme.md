# update 241205

*ChatGPT以外に、Grok APIとOllamaに対応しました。  
*モデルの会話温度を設定できるようになりました。   


# overview

ChatGPTやGrok、Ollamaにvoicevoxキャラのプロフィールを入れ、Voivevoxを通じて彼女たちの声でおしゃべりしてくれます。  
ボイボたちと会話を楽しめる（風の）声付きチャットボットです。今んとこ女子のみです。  
Pythonは初めてで、自分用でかなりいい加減な作りです。一応、動きます。  
プロンプトに改善の余地ありです。デフォルトのキャラプロンプトはsqliteでtumugi.dbに格納されていますが、好きなように修正してお使いください。


# how to use
1. Pythonをインストールします。（3.10で動作確認しました）
2. このレポジトリーをgit cloneするか、[Download ZIP](https://github.com/david419kr/GPT-voicevox-chatbot/archive/refs/heads/main.zip)します。
3. [Voicevox Engine](https://github.com/VOICEVOX/voicevox_engine/releases/latest)をインストールします。
4. "SET_YOUR_API_KEY_HERE.txt"に、OpenAI APIキーとGrok APIキーを入れます。Ollamaのみ使う場合はスルーで。
![image](https://github.com/user-attachments/assets/bfa9d079-bd0d-419f-b45b-bef233ef9ca6)

5. "start.bat"で起動します。初起動の場合、自動でvenvが生成されインストールされます。

# known issue
会話履歴やオプションの選択時に、２回クリックしないと反映されたりされなかったりするバグがありますが、解決法が分かりません。

# screenshots  

１．メイン画面  
![image](https://github.com/user-attachments/assets/66d735f3-4021-4cab-b98f-5ac3e4f27423)

  
２．音声選択  
![image](https://github.com/user-attachments/assets/f2bb5bc5-8a1f-4fd4-b540-381869fa973f)

  
３．キャラカスタマイズ  
![image](https://github.com/user-attachments/assets/45d5b394-576e-456d-bee5-c7a58712b350)

  
４．API、モデル選び  
![image](https://github.com/user-attachments/assets/8c46284c-56c2-4f3b-8e6e-932fda106314)

5. 会話（音声リプレイ付き）  
![image](https://github.com/user-attachments/assets/7f24f5a2-0579-4851-8d53-a5d5a15a23be)


# jenkinsfileからジョブを作成しGitHubを操作する方法
前提：jenkins version 2.289.3

### jenkinsfileを作成
- agent
- enviroment
- stages
 - stage
  - steps
   - step
   - sh
   - dir


### 関数化について
- node
- groovy

### pluginについて
- withCredentials
    - passwordでメタ文字を使用するとエスケープされずにエラーとなる
- Slack Notification Plugin

### ジョブの作成方法
- コンソール上の操作
    pipelineから作成
- cron設定について

### ユースケースごとの記載方法
- 繰り返し処理（ダイナミックなstageの記載方法）
- エラーハンドリングstage、groovy関数、shコマンドのそれぞれのエラーハンドリングについて


# Privacy Policy — KenjaDeck

**Effective date: November 1, 2026**

**The short version: KenjaDeck collects nothing.** There are no accounts, no analytics, no ads, and no tracking. Your presentations never leave your device — the only network traffic the app ever makes is when **you** use the built-in AI assistant, and those requests go directly to the AI provider **you** configured. We run no AI service and see none of that traffic.

KenjaDeck is a presentation app for macOS, developed by KenjaHub ("we", "us"). This policy explains what happens to your data when you use the app.

## 1. Data we collect

None. KenjaDeck does not transmit any personal data to us, and does not share data with any third party on our behalf.

In particular, KenjaDeck does **not** include:

- user accounts or sign-in
- analytics, telemetry, or crash-reporting SDKs
- advertising or ad tracking of any kind
- third-party trackers

This matches our App Store privacy declaration: *Data Not Collected*.

## 2. Your presentations stay on your device

Everything KenjaDeck does with your decks happens locally on your device:

- **Creating, editing, layout, rendering, printing and presenting all run on your Mac.**
- **Decks are never uploaded.** There is no server, no sync, no cloud — decks and exports are written wherever you choose on your disk.

## 3. The AI assistant — the only network traffic

KenjaDeck includes a built-in AI assistant that can answer questions about the open deck. It uses **your** model, not ours (bring your own key):

- **You configure the endpoint.** The assistant speaks to any OpenAI-compatible endpoint you set up in the app — OpenAI, DeepSeek, Qwen, or a local server such as Ollama or LM Studio.
- **Requests go directly from your Mac to that endpoint.** We run no AI service and no proxy: your questions, your deck content and your key never pass through us, and we could not see them if we wanted to.
- **What a request contains:** your message, the recent conversation, and the deck content the assistant reads through read-only inspection tools — a deck summary, slide text, or a rendered image of one slide. The assistant can only look; it cannot edit, create or save anything.
- **Your API key** is stored only in the app's settings file on your Mac, and is sent only to the base URL you configured, as an authorization header. For a local server you can leave it empty, and then nothing is sent.
- **The conversation lives in memory only.** Closing the app or starting a new session clears it; nothing is ever written to disk.
- **Once your data reaches the provider you chose, their privacy policy governs it.** We do not choose, vet or endorse providers — pick one you trust.

## 4. Data stored on your device

The following data is stored only on your device, under your full control:

- **Decks and exports** — the presentations you create or open and the files you export stay wherever you saved them; KenjaDeck keeps no copy
- **App settings** — including your AI model profiles: base URL, model id and API key, kept in the app's settings file on your Mac

Uninstalling the app removes the app and its local settings. Your decks are yours and remain untouched.

## 5. Network access

KenjaDeck itself initiates no network traffic — there is no account check, no update ping, no telemetry. The only traffic the app ever sends is an AI-assistant request that **you** triggered, delivered to the endpoint **you** configured. App updates are delivered by the App Store, not by us.

## 6. Children

KenjaDeck is rated 4+ and is not directed at children. Since the app collects no data at all, no data of children is collected either.

## 7. Your control

Because everything lives on your device, you are in full control at any time: open, copy, export or delete your decks like any other file, remove your saved models and keys in the AI Models settings, or uninstall the app to erase its settings.

## 8. Changes to this policy

If we change this policy, we will post the updated version on this page with a new effective date.

## 9. Contact

- Email: [kenjasoft@kofukuai.com](mailto:kenjasoft@kofukuai.com)
- GitHub: <https://github.com/KenjaHub>

---

# 隐私政策 — KenjaDeck（简体中文）

**生效日期：2026 年 11 月 1 日**

**简而言之：KenjaDeck 不收集任何数据。**没有账号、没有统计、没有广告，也没有追踪。你的演示文稿从不出你的设备——应用唯一会产生的网络流量，是**你**使用内置 AI 助手的时候，而那些请求直接发往**你自己配置**的 AI 服务商。我们不运营任何 AI 服务，也看不到那些流量。

KenjaDeck 是一款 macOS 演示文稿应用，由 KenjaHub（下称「我们」）开发。本政策说明你使用本应用时，你的数据会发生什么。

## 1. 我们收集的数据

无。KenjaDeck 不会向我们传输任何个人数据，也不会代表我们与任何第三方共享数据。

具体而言，KenjaDeck **不包含**：

- 用户账号或登录
- 统计分析、遥测或崩溃报告 SDK
- 任何形式的广告与广告追踪
- 第三方追踪器

这与我们在 App Store 的隐私申报一致：*不收集数据（Data Not Collected）*。

## 2. 演示文稿留在你的设备上

KenjaDeck 对你的演示文稿所做的一切，都在你的设备本地完成：

- **创建、编辑、排版、渲染、打印与放映，全部在你的 Mac 上运行。**
- **演示文稿从不上传。**没有服务器、没有同步、没有云端——文稿与导出文件只写入你在磁盘上选择的位置。

## 3. AI 助手——唯一的网络流量

KenjaDeck 内置一个 AI 助手，可以就当前打开的文稿回答问题。它用的是**你自己的**模型，而不是我们的（自带密钥，BYOK）：

- **端点由你配置。**助手通过 OpenAI 兼容接口与你设置的任意端点通信——OpenAI、DeepSeek、Qwen，或 Ollama、LM Studio 等本地服务。
- **请求从你的 Mac 直接发往该端点。**我们不运营任何 AI 服务、也没有任何代理：你的问题、文稿内容与密钥都不经过我们，我们想看也看不到。
- **请求包含的内容：**你的消息、最近的对话，以及助手通过只读检查工具读取的文稿内容——文稿概要、幻灯片文字，或某一张幻灯片的渲染图。助手只能查看，不能编辑、创建或保存任何内容。
- **你的 API 密钥**只保存在你 Mac 上的应用设置文件里，且只以授权头的形式发往你配置的基础 URL。使用本地服务时可以留空，此时什么都不会发送。
- **对话仅存于内存。**关闭应用或开启新会话即被清除，任何内容都不会写入磁盘。
- **数据到达你选择的服务商之后，适用他们的隐私政策。**我们不推荐、不审查、也不背书任何服务商——请选择你信任的服务商。

## 4. 存储在你设备上的数据

以下数据仅存储在你的设备上，完全由你掌控：

- **文稿与导出文件**——你创建或打开的演示文稿与导出的文件留在你保存它们的位置；KenjaDeck 不保留任何副本
- **应用设置**——包括你的 AI 模型配置：基础 URL、模型 ID 与 API 密钥，保存在你 Mac 上的应用设置文件中

卸载应用会移除应用及其本地设置。你的文稿属于你，不会被触碰。

## 5. 网络访问

KenjaDeck 自身不发起任何网络流量——没有账号验证、没有更新探测、没有遥测。应用唯一发出的流量，是**你**触发的一次 AI 助手请求，发往**你**配置的端点。应用更新由 App Store 提供，而非我们。

## 6. 儿童

KenjaDeck 分级为 4+，不面向儿童。由于应用完全不收集数据，自然也不会收集任何儿童数据。

## 7. 你的掌控

因为一切都保存在你的设备上，你始终拥有完全的掌控：像操作任何普通文件一样打开、复制、导出或删除你的文稿；在「AI 模型」设置中删除已保存的模型与密钥；或卸载应用以清除其设置。

## 8. 政策变更

如果我们修改本政策，会在本页发布更新版本，并注明新的生效日期。

## 9. 联系方式

- 邮箱：[kenjasoft@kofukuai.com](mailto:kenjasoft@kofukuai.com)
- GitHub：<https://github.com/KenjaHub>

---

# プライバシーポリシー — KenjaDeck（日本語）

**発効日：2026 年 11 月 1 日**

**要点：KenjaDeck は何も収集しません。**アカウントも、分析も、広告も、トラッキングもありません。お客様のプレゼンテーションが端末の外へ出ることはありません。アプリが通信を行うのは、内蔵 AI アシスタントを**お客様ご自身が**使ったときだけで、そのリクエストは**お客様が設定した** AI プロバイダーへ直接送られます。当社は AI サービスを運営しておらず、その通信を見ることもできません。

KenjaDeck は macOS 用プレゼンテーションアプリで、KenjaHub（以下「当社」）が開発しました。本ポリシーは、アプリご利用の際にお客様のデータがどう扱われるかを説明するものです。

## 1. 収集するデータ

なし。KenjaDeck は当社へいかなる個人データも送信せず、当社のために第三者へデータを共有することもありません。

とくに、KenjaDeck には以下のものは**含まれません**：

- ユーザーアカウントやサインイン
- アナリティクス、テレメトリー、クラッシュレポート SDK
- いかなる形態の広告および広告トラッキング
- サードパーティのトラッカー

これは App Store のプライバシー申告「*Data Not Collected（データ収集なし）*」と一致します。

## 2. プレゼンテーションはお客様の端末に残ります

KenjaDeck がプレゼンテーションに対して行うすべての処理は、お客様の端末上でローカルに実行されます：

- **作成・編集・レイアウト・レンダリング・印刷・スライドショーは、すべてお客様の Mac 上で動作します。**
- **プレゼンテーションがアップロードされることは一切ありません。**サーバーも、同期も、クラウドもなく、スライドや書き出しファイルはお客様が選んだ場所に保存されます。

## 3. AI アシスタント——唯一のネットワーク通信

KenjaDeck には、開いているスライドについて質問に答える内蔵 AI アシスタントがあります。使うのは**お客様の**モデルであり、当社のものではありません（BYOK——自分のキーを持参する方式）：

- **エンドポイントはお客様が設定します。**アシスタントは、アプリ内で設定した OpenAI 互換エンドポイントと通信します。OpenAI、DeepSeek、Qwen、あるいは Ollama・LM Studio などのローカルサーバーでもかまいません。
- **リクエストはお客様の Mac からそのエンドポイントへ直接送られます。**当社は AI サービスもプロキシも運営していません。お客様の質問・スライドの内容・キーが当社を経由することはなく、当社が見ることもできません。
- **リクエストに含まれるもの：**お客様のメッセージ、最近の会話履歴、そしてアシスタントが読み取り専用の検査ツールで読んだスライドの内容——スライド全体の概要、スライドのテキスト、または 1 枚のスライドのレンダリング画像です。アシスタントは閲覧のみ可能で、編集・作成・保存は一切できません。
- **API キー**はお客様の Mac 内のアプリ設定ファイルにのみ保存され、設定されたベース URL に認証ヘッダーとして送信されるだけです。ローカルサーバーでは空にでき、その場合は何も送信されません。
- **会話はメモリ上にのみ存在します。**アプリを閉じるか新しいセッションを始めると消去され、ディスクに書き込まれることは一切ありません。
- **データがお客様の選んだプロバイダーに到達した後は、そのプロバイダーのプライバシーポリシーが適用されます。**当社はプロバイダーの選定・審査・推薦を行いません。信頼できるプロバイダーをお選びください。

## 4. 端末に保存されるデータ

以下のデータはお客様の端末にのみ保存され、完全にお客様の管理下にあります：

- **スライドと書き出しファイル**——作成または開いたプレゼンテーションと書き出したファイルは保存した場所にそのまま残り、KenjaDeck はコピーを保持しません
- **アプリ設定**——AI モデルプロファイル（ベース URL、モデル ID、API キー）を含む設定は、お客様の Mac 内のアプリ設定ファイルに保存されます

アプリをアンインストールすると、アプリとそのローカル設定は削除されます。スライドはお客様のものであり、手つかずのまま残ります。

## 5. ネットワークアクセス

KenjaDeck 自身は、ネットワーク通信を一切開始しません。アカウント確認も、更新確認も、テレメトリーもありません。アプリが送信する唯一の通信は、**お客様が**実行した AI アシスタントのリクエストで、**お客様が**設定したエンドポイントへ送られます。アプリの更新は当社ではなく App Store から配信されます。

## 6. 児童

KenjaDeck のレーティングは 4+ で、児童向けに作られたアプリではありません。アプリはまったくデータを収集しないため、児童のデータも収集されません。

## 7. お客様の管理

すべてが端末内に存在するため、データの管理権限は常に完全にお客様側にあります。スライドはほかのファイルと同じように開く・コピー・書き出し・削除ができ、「AI モデル」設定から保存済みのモデルとキーを削除したり、アプリをアンインストールして設定を消去したりできます。

## 8. 本ポリシーの変更

本ポリシーを変更する場合は、このページに新しい発効日付きの更新版を掲載します。

## 9. お問い合わせ

- メール：[kenjasoft@kofukuai.com](mailto:kenjasoft@kofukuai.com)
- GitHub：<https://github.com/KenjaHub>

---

© 2026 KenjaHub

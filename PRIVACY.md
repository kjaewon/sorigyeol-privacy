# 목소리친구 개인정보처리방침 (Privacy Policy)

*최종 수정일: 2026년 11월 11일*

[English](#en) · [日本語](#ja)

**목소리친구** (패키지명: `com.next2great.sorigyeol`, 이하 "앱")은 짧게 읽은 목소리의 높낮이·밝기 같은 특징을 기기에서 분석해 색과 작은 캐릭터로 표현하는 앱입니다. 앱이 어떤 정보를 어떻게 다루는지 아래와 같이 안내합니다.

## 1. 기본 원칙

- 회원 가입이나 로그인 없이 사용합니다. 생년월일·성별 같은 정보를 묻지 않습니다.
- 목소리는 기기 안에서만 분석합니다. 개발자는 별도의 서버를 운영하지 않으며, 목소리나 분석 결과를 수집하지 않습니다.
- 녹음 원본은 분석에만 쓰고 저장하지 않습니다. 분석이 끝나거나 다시 녹음하면 기기 메모리에서 사라집니다.
- 결과는 창작 표현이며 성격·건강·감정을 판단하지 않습니다. 화자를 식별하거나 목소리로 사람을 구별하지 않습니다.

## 2. 기기에 저장하는 정보

앱이 기기에 저장하는 음성 결과와 설정 정보는 다음과 같습니다. 이전 버전에서 만든 함께 만들기 결과에는 14세 미만 표시가 남아 있을 수 있습니다.

- 보관함 결과: 캐릭터와 색, 사용자가 붙인 이름, 설명 문장, 요약 측정값(음높이 중앙값·변화 폭, 소리 밝기 지표, 말한 시간 등), 결과 화면에 그리는 축소한 음높이 곡선
- 함께 만들기 결과: 참여자가 입력한 이름이나 별명, 관계(가족·친구 등), 각 참여자의 결과
- 앱 설정: 테마, 움직임 줄이기, 대표 캐릭터, 첫 안내를 본 여부

이 정보는 개발자에게 전송되지 않으며, Android 클라우드 백업과 기기 간 이전에서도 제외합니다.

## 3. 권한과 파일

- **마이크 (RECORD_AUDIO)**: 사용자가 녹음 버튼을 누를 때만 최대 15초 동안 사용합니다. 녹음은 파일로 남기지 않습니다.
- **오디오 파일 가져오기**: 사용자가 고른 파일 하나를 시스템 파일 선택기로 열어 앞부분 15초만 분석합니다. 파일을 앱에 복사해 두지 않습니다.
- **사진 저장 (Android 9 이하만 저장소 쓰기 권한)**: 사용자가 "갤러리에 저장"을 누를 때 공유 이미지를 사진 폴더에 저장합니다. 갤러리에 저장한 사진은 앱을 지워도 남습니다.
- **공유**: 사용자가 공유를 누르면 만든 이미지를 Android 공유 창으로 사용자가 고른 앱에 넘깁니다. 이후 처리는 그 앱의 정책을 따릅니다.

그 밖의 위치, 연락처, 계정 정보 등은 요청하지 않습니다.

## 4. 함께 만들기

여러 사람이 한 기기로 차례로 녹음해 결과를 나란히 봅니다. 녹음 전에 모두에게 기기에서 분석하고 녹음 원본은 저장하지 않는다는 점을 알리고 동의를 받도록 안내합니다. 비교는 측정값의 차이만 보여 주며 궁합 점수를 만들거나 관계·성격을 추정하지 않습니다.

## 5. Google Play 기능

앱은 새 버전 확인과 리뷰 남기기(Google Play 인앱 리뷰)를 위해 Google Play와 통신합니다. 이 과정은 Google의 개인정보처리방침에 따라 처리됩니다.

- Google 개인정보처리방침: https://policies.google.com/privacy

## 6. 분석·광고

앱에는 광고가 없습니다. 오류 보고와 선택적 이용 통계를 위해 Google Firebase를 사용합니다.

목소리친구는 앱의 오류를 찾아 고치기 위해 Google의 **Firebase Crashlytics**를 사용합니다. 앱이 비정상 종료되거나
처리하지 못한 오류가 생기면 다음 정보가 Google 서버로 전송됩니다.

- 오류가 난 위치와 직전의 실행 흐름(스택 트레이스), 오류 발생 시각
- 앱 버전, 기기 모델, 운영체제 버전, 화면 방향, 남은 메모리·저장공간 같은 기기 상태
- 앱 설치마다 무작위로 만들어지는 Crashlytics 설치 식별자

이 정보에는 이름, 연락처, 계정, 사용자가 앱에 입력한 내용이 포함되지 않으며, 오류 분석과 앱 품질 개선에만 사용합니다.
전송된 정보는 Google이 [Firebase 개인정보 보호 안내](https://firebase.google.com/support/privacy)에 따라 처리하며,
Crashlytics 오류 기록은 약 90일 동안 보관된 뒤 삭제됩니다.

목소리친구는 앱 개선을 위해 Google의 **Firebase 애널리틱스(Google Analytics for Firebase)**를 사용합니다.
사용자가 설정에서 사용 통계 전송을 켰을 때에만 화면 조회, 기능 사용, 앱 사용 시간, 앱 버전, 기기·운영체제 정보,
앱 설치별 식별자와 대략적인 국가·도시 정보가 Google에 전송됩니다. 설정에서 언제든지 끌 수 있습니다.
광고 식별자는 수집하지 않도록 설정했습니다. 음성 녹음, 분석 결과, 참여자의 이름을 분석 이벤트에 넣지 않습니다.
정보는 [Firebase 개인정보 보호 안내](https://firebase.google.com/support/privacy)와
[Google 개인정보처리방침](https://policies.google.com/privacy)에 따라 처리됩니다.

## 7. 정보 삭제

- 결과 화면의 "이 결과 지우기", 함께 만든 결과의 "이 그룹 지우기"로 하나씩 지울 수 있습니다.
- 설정의 "보관함 모두 지우기"로 결과와 함께 만든 결과를 한 번에 지울 수 있습니다.
- 기기 설정에서 앱 데이터를 지우거나 앱을 삭제하면 기기에 저장된 모든 정보가 삭제됩니다. 갤러리에 저장한 사진은 사진 앱에서 지웁니다.

## 8. 아동

앱은 만 14세 미만 아동을 대상으로 하지 않습니다. 함께 만들기의 이름과 결과는 기기에만 저장됩니다.

## 9. 방침 변경

이 방침이 바뀌면 이 페이지에 게시하고 최종 수정일을 고칩니다.

## 10. 문의

- 개발자: next2great
- 이메일: next2great.dev@gmail.com

---

# Voice Critters Privacy Policy (English) {#en}

**Voice Critters** (package `com.next2great.sorigyeol`, "the app") analyzes features of a short voice sample, such as pitch and brightness, on your device and expresses them as colors and a small character.

*Last updated: November 11, 2026*

## 1. Principles

- No sign-up or login. The app does not ask for your birth date or gender.
- Your voice is analyzed only on your device. The developer runs no server and does not collect your voice or results.
- The original recording is used only for analysis and is not saved. It is cleared from memory when analysis finishes or you record again.
- Results are creative expressions and do not judge personality, health or emotions. The app does not identify speakers or tell people apart by voice.

## 2. Data stored on your device

- Collection results: character and colors, the name you give it, explanation text, summary measurements (median pitch and range, a brightness index, speaking time, etc.) and a reduced pitch curve drawn on the result screen
- "Make together" results: names or nicknames entered for participants, the relationship (family, friends, etc.), and each participant's result
- App settings: theme, reduce motion, main character, and whether you've seen the first-run guide

This data is not sent to the developer and is excluded from Android cloud backup and device-to-device transfer.

## 3. Permissions and files

- **Microphone (RECORD_AUDIO)**: used only when you tap record, for up to 15 seconds. Recordings are not saved as files.
- **Importing an audio file**: the file you pick in the system file picker is opened and only its first 15 seconds are analyzed. The file is not copied into the app.
- **Saving photos (storage write permission on Android 9 and earlier only)**: when you tap "Save to gallery", the image is saved to your Pictures folder. Saved photos stay even if you uninstall the app.
- **Sharing**: when you tap share, the image is passed to the app you choose in the Android share sheet, under that app's policy.

The app does not request location, contacts or account information.

## 4. Make together

Several people take turns recording on one device and see their results side by side. Before recording, the app asks you to tell everyone that analysis happens on the device and recordings aren't saved, and to get their agreement. Comparisons only show differences in measured values; there is no compatibility score and no guess about relationships or personality.

## 5. Google Play features

The app communicates with Google Play to check for new versions and to leave a review (Play in-app review), under Google's privacy policy: https://policies.google.com/privacy

## 6. Analytics and ads

The app has no ads. Firebase Crashlytics sends crash reports, such as stack traces, app and device information, and installation identifiers, to Google to help fix errors. Crash reports are retained by Firebase for approximately 90 days.

Firebase Analytics is off by default. If you enable usage analytics in Settings, Google receives app interaction and usage information, device and app details, an installation identifier, and approximate region. You can turn it off at any time. Advertising ID collection is disabled. We do not add recordings, voice analysis results, or participant names to analytics events. Google processes this information under its [Firebase privacy information](https://firebase.google.com/support/privacy) and [privacy policy](https://policies.google.com/privacy).

## 7. Deleting data

Delete a single result with "Delete this result", a group with "Delete this group", or everything with "Delete entire collection" in Settings. Clearing the app's data or uninstalling it removes everything stored on the device. Delete photos saved to the gallery in your photos app.

## 8. Children

The app is not directed at children under 14. Names and results for participants are stored only on the device.

## 9. Changes

Changes are posted on this page with a new "last updated" date.

## 10. Contact

next2great — next2great.dev@gmail.com

---

# こえのともだち プライバシーポリシー（日本語） {#ja}

**こえのともだち（Voice Critters）**（パッケージ名 `com.next2great.sorigyeol`、以下「本アプリ」）は、短く読み上げた声の高さや明るさなどの特徴を端末内で分析し、色と小さなキャラクターで表現するアプリです。

*最終更新日：2026年11月11日*

## 1. 基本方針

- 会員登録やログインは不要です。生年月日や性別は尋ねません。
- 声は端末内でのみ分析します。開発者はサーバーを運営しておらず、声や分析結果を収集しません。
- 録音そのものは分析にのみ使い、保存しません。分析が終わるか録音し直すと、端末のメモリから消えます。
- 結果は創作的な表現であり、性格・健康・感情を判断するものではありません。話者を識別したり、声で人を区別したりしません。

## 2. 端末に保存する情報

- コレクションの結果：キャラクターと色、ユーザーが付けた名前、説明文、要約した測定値（声の高さの中央値と変化の幅、明るさの指標、話した時間など）、結果画面に描く縮小した声の高さの曲線
- 「みんなで作る」の結果：参加者が入力した名前やニックネーム、関係（家族・友だちなど）、各参加者の結果
- アプリの設定：テーマ、動きを減らす、代表キャラクター、最初の案内を見たかどうか

これらの情報は開発者に送信されず、Android のクラウドバックアップと端末間の移行からも除外します。

## 3. 権限とファイル

- **マイク（RECORD_AUDIO）**：録音ボタンを押したときだけ、最大15秒間使います。録音はファイルとして残しません。
- **音声ファイルの読み込み**：システムのファイル選択画面で選んだファイルを開き、先頭の15秒だけを分析します。ファイルをアプリにコピーしません。
- **写真の保存（Android 9 以前のみストレージ書き込み権限）**：「ギャラリーに保存」を押すと、画像を写真フォルダに保存します。保存した写真はアプリを削除しても残ります。
- **共有**：共有を押すと、作った画像を Android の共有画面で選んだアプリに渡します。その後の取り扱いはそのアプリのポリシーに従います。

位置情報、連絡先、アカウント情報などは要求しません。

## 4. みんなで作る

複数の人が1台の端末で順番に録音し、結果を並べて見ます。録音の前に、端末内で分析し録音は保存しないことを全員に伝えて同意を得るよう案内します。比較は測定値の違いだけを示し、相性のスコアを作ったり関係や性格を推測したりしません。

## 5. Google Play の機能

本アプリは、新しいバージョンの確認とレビュー（Google Play アプリ内レビュー）のために Google Play と通信します。この処理には Google のプライバシーポリシーが適用されます：https://policies.google.com/privacy

## 6. 分析・広告

本アプリには広告はありません。Firebase Crashlyticsは、不具合の修正のため、スタックトレース、アプリと端末の情報、インストール識別子などのクラッシュレポートをGoogleに送信します。レポートはFirebaseに約90日間保存されます。

Firebase Analyticsは初期設定ではオフです。設定で利用状況の送信をオンにした場合、アプリの操作・利用状況、アプリと端末の情報、インストール識別子、おおよその地域がGoogleに送信されます。いつでもオフにできます。広告IDの収集は無効にしています。録音、声の分析結果、参加者の名前を分析イベントに含めません。情報は[Firebaseのプライバシーに関する説明](https://firebase.google.com/support/privacy)と[Googleのプライバシーポリシー](https://policies.google.com/privacy)に従って処理されます。

## 7. 情報の削除

結果画面の「この結果を削除」、グループの「このグループを削除」、設定の「コレクションをすべて削除」で削除できます。端末の設定でアプリのデータを消去するかアプリを削除すると、端末に保存されたすべての情報が削除されます。ギャラリーに保存した写真は写真アプリで削除してください。

## 8. 子ども

本アプリは14歳未満の子どもを対象としていません。参加者の名前と結果は端末にのみ保存されます。

## 9. ポリシーの変更

このポリシーを変更した場合は、このページに掲載し最終更新日を改めます。

## 10. お問い合わせ

next2great — next2great.dev@gmail.com

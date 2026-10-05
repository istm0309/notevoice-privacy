# 한국어

**NoteVoice 개인정보 처리방침**
시행일: 2026년 10월 5일

init(이하 "운영자")는 NoteVoice 앱(이하 "앱")을 제공하며, 이용자의 개인정보를 소중히 다룹니다.
이 방침은 앱이 어떤 정보를 어떻게 다루는지 설명합니다.

## 1. 요약

- 녹음한 소리는 **기기 안에서만 분석**하며 운영자 서버로 보내지 않습니다.
- 만든 악보는 **기기에만 저장**됩니다.
- 하루 무료 내보내기 횟수를 지키기 위해 **Google 로그인**을 쓰고, 계정 식별자와 사용 횟수가 서버에 저장됩니다.
- 광고(Google AdMob)를 위해 **광고 ID** 등이 사용될 수 있습니다.

## 2. 수집하고 이용하는 정보

| 정보 | 사용 목적 | 어디에 저장되는가 |
|---|---|---|
| 마이크 음성 (녹음) | 음높이를 분석해 악보를 만들기 위함 | 기기 안에서만 처리합니다. 서버로 전송하지 않습니다. |
| 악보 데이터(음표, 제목, 템포 등), 앱 설정 | 악보 보관, 편집, 내보내기, 화면 설정 유지 | 기기 안 앱 전용 저장 공간 |
| 가져온 파일(WAV, 이미지, PDF) | 사용자가 직접 선택한 파일로 악보를 만들기 위함 | 기기 안에서만 처리합니다. 서버로 전송하지 않습니다. |
| Google 계정 정보(계정 고유 식별자, 이메일 주소) | 로그인, 하루 무료 내보내기 횟수를 계정에 연결하기 위함 | Google Firebase Authentication |
| 날짜별 무료 내보내기 사용 횟수 | 하루 무료 횟수 제한 | Google Firebase (Cloud Firestore, 서울 리전) |
| 기기 및 앱 무결성 신호 | 변조된 앱이나 자동화된 요청을 걸러내기 위함 (Firebase App Check, Google Play Integrity) | Google이 처리합니다. 운영자는 이 신호를 별도로 저장하지 않습니다. |
| 광고 ID, 기기 및 광고 상호작용 정보 | 광고 표시, 광고 효과 측정, 부정 클릭 방지 | Google AdMob이 처리합니다. |
| 구독 구매 정보 | 프리미엄 구독 확인 | Google Play 결제 서비스. 운영자는 카드 정보를 받지 않습니다. |

앱은 이름, 전화번호, 주소, 위치 정보, 연락처, 사진첩, 통화 기록을 수집하지 않습니다.
이용자가 내보내기 한 파일을 공유할 때 선택한 다른 앱으로 전달되는 정보는 해당 앱의 방침을 따릅니다.

## 3. 광고와 동의

- 앱은 Google AdMob의 보상형 광고(광고를 보면 내보내기)를 사용합니다. AdMob은 광고 ID 등을 이용해 광고를 보여 주고
  측정할 수 있습니다. 자세한 내용은 Google 정책을 확인하세요. https://policies.google.com/technologies/ads
- 유럽경제지역, 영국 등 동의가 필요한 지역에서는 처음 실행할 때 동의 창이 나타나며, 앱의 설정 카드에서 선택을 바꿀 수 있습니다.
- 기기 설정(설정 → 개인정보 보호 → 광고)에서 광고 ID를 재설정하거나 맞춤 광고를 끌 수 있습니다.

## 4. 개인정보의 보유와 이용 기간

- 마이크 음성과 악보: 앱 안에서 이용자가 삭제하거나 앱을 삭제할 때까지 기기에만 있습니다.
- Google 계정 식별자와 사용 횟수: 로그인 계정을 유지하는 동안 보관합니다. 사용 횟수는 날짜별로 기록되며 하루 단위 제한 외의
  용도로 쓰지 않습니다. 이용자가 계정을 삭제하면 계정과 지난 사용 기록은 즉시 삭제됩니다. 다만 삭제 후 다시 가입해 그날의 무료
  횟수를 되돌리는 것을 막기 위해, **당일의 사용 기록 1건은 최대 3일 뒤 자동으로 삭제**됩니다.
- 법령에서 따로 보관을 정한 경우에는 그 기간 동안 보관합니다.

## 5. 제3자 제공과 처리 위탁

운영자는 개인정보를 판매하지 않습니다. 서비스 제공을 위해 아래 사업자의 서비스를 이용하며, 이들은 각자의 방침에 따라
정보를 처리합니다.

| 사업자 | 목적 |
|---|---|
| Google LLC (Firebase Authentication, Cloud Functions, Cloud Firestore, App Check, Play Integrity) | 로그인, 무료 횟수 저장과 확인, 앱 무결성 확인 |
| Google LLC (AdMob) | 광고 표시 |
| Google LLC (Google Play 결제) | 구독 결제 |

이용자의 정보는 Google의 서버에서 처리되므로 대한민국 밖에서 처리되거나 보관될 수 있습니다. 횟수 정보를 담는 데이터베이스는 서울 리전에
있으나, 로그인과 광고 처리는 Google의 다른 지역에서 이루어질 수 있습니다.

## 6. 이용자의 권리

이용자는 언제든지 다음을 할 수 있습니다.
- 앱 설정에서 **로그아웃**하기
- 기기의 앱 설정에서 **마이크 권한 해제**하기
- 앱 데이터 삭제 또는 앱 삭제로 기기 안의 악보와 설정 지우기
- 앱 설정의 **계정 삭제** 버튼으로 계정과 서버에 저장된 사용 기록을 직접 삭제하기 (앱을 지우거나 이메일로 요청하지 않아도 됩니다)
- 서버에 저장된 정보의 **열람 요청** (아래 연락처)

## 7. 만 14세 미만 아동

앱은 만 14세 미만 아동을 대상으로 하지 않으며, 아동의 개인정보를 알면서 수집하지 않습니다. 아동의 정보가 수집되었다고 판단되면
아래 연락처로 알려 주세요. 지체 없이 삭제하겠습니다.

## 8. 안전성 확보 조치

- 서버 데이터베이스는 앱에서 직접 읽거나 쓸 수 없고, 인증된 서버 함수를 통해서만 접근합니다.
- 서버 호출은 Firebase App Check로 정식 앱에서 온 요청만 받도록 합니다.
- 전송 구간은 암호화(HTTPS)됩니다.
- 앱 화면은 다른 앱의 화면 캡처와 녹화에서 보호됩니다.

## 9. 방침의 변경

내용이 바뀌면 이 페이지에 변경 사항과 시행일을 알립니다. 중요한 변경은 앱 안에서도 안내합니다.

## 10. 문의

개인정보 관련 문의, 열람과 삭제 요청: istm0309@gmail.com
개인정보 보호책임자: init

---

# English

**NoteVoice Privacy Policy**
Effective date: October 5, 2026

init ("we") provides the NoteVoice app (the "App"). This policy explains what the App does with your information.

## 1. Summary

- Audio you record is analyzed **on your device only**. It is not sent to our servers.
- The scores you make are stored **only on your device**.
- To enforce the daily free-export limit, the App uses **Google sign-in**. Your account identifier and a daily usage count are stored on a server.
- **Google AdMob** may use your advertising ID to show ads.

## 2. Information we handle

| Information | Purpose | Where it is handled |
|---|---|---|
| Microphone audio | To detect pitches and create sheet music | On your device only. Not uploaded. |
| Score data (notes, title, tempo) and app settings | To save, edit and export scores and remember your settings | App-private storage on your device |
| Files you import (WAV, images, PDF) | To create a score from a file you choose | On your device only. Not uploaded. |
| Google account information (unique account ID, email address) | Sign-in, and tying the daily free export to your account | Google Firebase Authentication |
| Number of free exports used per day | To enforce the daily free limit | Google Firebase (Cloud Firestore, Seoul region) |
| Device and app integrity signals | To reject modified apps and automated requests (Firebase App Check, Google Play Integrity) | Processed by Google. We do not store these signals separately. |
| Advertising ID, device and ad interaction data | To show and measure ads and prevent invalid traffic | Processed by Google AdMob |
| Subscription purchase status | To confirm Premium | Google Play Billing. We never receive your card details. |

The App does not collect your name, phone number, address, location, contacts, photo library or call history.
When you share an exported file, what the receiving app does with it is governed by that app's policy.

## 3. Advertising and consent

- The App uses Google AdMob rewarded ads (watch an ad to export). AdMob may use your advertising ID to show and measure ads.
  See https://policies.google.com/technologies/ads
- Where consent is required (for example the EEA and the UK), a consent form appears at first launch. You can change your choice from the
  settings card in the App.
- You can reset your advertising ID or turn off ad personalization in your device settings (Settings → Privacy → Ads).

## 4. Retention

- Audio and scores stay on your device until you delete them or uninstall the App.
- Your Google account identifier and usage counts are kept while your account is in use. Usage counts are recorded per day and used
  only for the daily limit. When you delete your account, the account and past usage records are deleted immediately. To stop someone
  from deleting and re-registering to get back the day's free export, **today's single usage record is deleted automatically within 3 days**.
- We keep data longer only where the law requires it.

## 5. Sharing and service providers

We do not sell personal information. We use the following providers, who process data under their own policies:

| Provider | Purpose |
|---|---|
| Google LLC (Firebase Authentication, Cloud Functions, Cloud Firestore, App Check, Play Integrity) | Sign-in, storing and checking the free-export count, app integrity |
| Google LLC (AdMob) | Showing ads |
| Google LLC (Google Play Billing) | Subscription payments |

Your information is processed on Google's servers and may be processed or stored outside your country. The database that holds the count is in the
Seoul region, but sign-in and ad processing may happen in other Google regions.

## 6. Your rights

You can at any time:
- **Sign out** in the App settings
- **Revoke the microphone permission** in your device's app settings
- Delete scores and settings on the device by clearing app data or uninstalling the App
- Use **Delete account** in the App settings to delete your account and the usage records stored on our server yourself (no need to uninstall or email us)
- **Request access to** the information stored on our server (contact below)

## 7. Children

The App is not directed to children under 14 (or the minimum age in your country), and we do not knowingly collect children's data. If you
believe a child's data was collected, contact us and we will delete it promptly.

## 8. Security

- The server database cannot be read or written directly by the App. It is reached only through authenticated server functions.
- Server calls use Firebase App Check so only requests from the genuine App are accepted.
- Data in transit is encrypted (HTTPS).
- The App's screens are protected from screenshots and screen recording by other apps.

## 9. Changes

If this policy changes, we will post the changes and the effective date on this page, and tell you in the App for important changes.

## 10. Contact

Questions, access and deletion requests: istm0309@gmail.com
Privacy officer: init

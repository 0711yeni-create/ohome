# O.HOME APK 빌드

이 저장소의 GitHub Actions는 O.HOME 웹사이트를 Android APK로 감싸서 빌드합니다.

## 처음 한 번만

1. GitHub에서 이 폴더를 새 저장소로 업로드합니다.
2. 저장소의 **Settings → Secrets and variables → Actions → Variables → New repository variable**로 갑니다.
3. 이름을 `OHOME_URL`로 입력합니다.
4. 값에 실제 O.HOME 주소를 입력합니다. 예: `https://ohome-example.vercel.app`
5. 저장합니다.

## APK 만들기

1. 저장소에서 **Actions** 탭을 누릅니다.
2. 왼쪽에서 **Build O.HOME APK**를 누릅니다.
3. **Run workflow** → **Run workflow**를 누릅니다.
4. 완료되면 아래쪽의 **Artifacts → OHOME-debug-apk**를 눌러 APK를 받습니다.

이 APK는 인터넷으로 지정한 O.HOME 주소를 열기 때문에 O.HOME의 기존 Firebase/Supabase 기능을 그대로 사용할 수 있습니다.

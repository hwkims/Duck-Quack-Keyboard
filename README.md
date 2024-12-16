![image](https://github.com/user-attachments/assets/767afd9f-d1c9-4f8e-89df-ae5871d3b003)

20만원아끼기
---

## 🦆 Duck Quack Keyboard

This project provides a fun and quirky keyboard experience where every key press triggers the sound of a duck quacking. Simply extract the provided files, run the `.exe` file, and enjoy the amusing quack sounds as you type!

### 🎧 Features
- Each key press triggers a unique duck quack sound.
- Customize sounds for different keys using the `config.ini` file.
- Easily configurable with no additional setup needed beyond extracting the files.

### 📦 Installation
1. Download and extract the `.zip` file.
2. After extracting, open the folder and double-click the `.exe` file to run the application.
3. The application will run, and each time you press a key, you'll hear a duck quack!

### 🎨 Customization
- **Sound Files**: All key sounds are stored in the `assets/` folder. You can replace the sound files (e.g., `duck.wav`) with your own quack sounds.
- **Settings**: The `config.ini` file allows you to adjust settings like volume, sound channels, and which sound to play for each key.

### 📝 Example `config.ini`
```ini
[Config]
volume=3
maxSoundChannel=3
noSoundOnBattery=0

[Sound]
key=duck.wav
ctrl=duck.wav
alt=duck.wav
shift=duck.wav
space=duck.wav
tab=duck.wav
del=duck.wav
backSpace=duck.wav
enter=duck.wav
```

- **[Config]** section:
  - `volume`: Controls the sound volume (1-10).
  - `maxSoundChannel`: Sets the maximum number of sound channels (adjust if you want to play multiple sounds at once).
  - `noSoundOnBattery`: Set to `1` to disable sound when running on battery.

- **[Sound]** section:
  - You can specify different `.wav` sound files for each key action, like `key`, `ctrl`, `alt`, `shift`, `space`, `tab`, `del`, `backSpace`, and `enter`.

---

## 🦆 오리 꽥 소리 나는 키보드

이 프로젝트는 키를 누를 때마다 오리의 꽥 소리가 나는 재미있는 키보드 경험을 제공합니다. 제공된 파일을 압축 해제하고 `.exe` 파일을 실행하면 타이핑할 때마다 오리 꽥 소리가 납니다!

### 🎧 특징
- 각 키를 누를 때마다 고유한 오리 꽥 소리가 재생됩니다.
- `config.ini` 파일을 통해 각 키에 해당하는 소리를 자유롭게 설정할 수 있습니다.
- 압축을 풀고 바로 실행하면 되므로 별도의 복잡한 설정이 필요 없습니다.

### 📦 설치 방법
1. `.zip` 파일을 다운로드하고 압축을 풀어주세요.
2. 압축을 푼 폴더 안에서 `.exe` 파일을 더블 클릭하여 실행합니다.
3. 프로그램이 실행되면, 키를 누를 때마다 오리 꽥 소리가 납니다!

### 🎨 커스터마이징
- **소리 파일**: `assets/` 폴더에 있는 `duck.wav` 파일을 원하는 오리 꽥 소리 파일로 교체할 수 있습니다.
- **설정**: `config.ini` 파일에서 볼륨, 소리 채널 수, 각 키에 대한 소리 파일을 설정할 수 있습니다.

### 📝 예시 `config.ini`
```ini
[Config]
volume=3
maxSoundChannel=3
noSoundOnBattery=0

[Sound]
key=duck.wav
ctrl=duck.wav
alt=duck.wav
shift=duck.wav
space=duck.wav
tab=duck.wav
del=duck.wav
backSpace=duck.wav
enter=duck.wav
```

- **[Config]** 섹션:
  - `volume`: 소리의 볼륨을 설정합니다 (1-10).
  - `maxSoundChannel`: 동시에 재생할 수 있는 최대 소리 채널 수를 설정합니다.
  - `noSoundOnBattery`: 배터리 모드에서 소리를 끄려면 `1`로 설정합니다.

- **[Sound]** 섹션:
  - 각 키에 대해 사용할 `.wav` 소리 파일을 지정할 수 있습니다. 예: `key`, `ctrl`, `alt`, `shift`, `space`, `tab`, `del`, `backSpace`, `enter`.

---

이 README 파일은 사용자가 압축을 풀고 바로 실행할 수 있도록 안내하며, `config.ini` 파일로 소리와 설정을 쉽게 수정할 수 있다는 점을 강조하고 있습니다.

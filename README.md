
# 🎮 HeatPump Master

**HeatPump Master** is an Android game developed with Java in Android Studio.

In this game, you control the heating actions of a heat pump with the goal of using only green electricity from wind and solar to reduce CO₂ emissions and avoid electricity from fossil fuels like coal and gas.

At the same time, you must maintain a high level of comfort by keeping the room temperature within a specified comfort range and ensuring that the hot water tank has enough—but not too much—hot water.

Additionally, the app includes interesting facts about heat pumps, showing why they are crucial for decarbonizing the heating sector and achieving independence from fossil fuels—making them a key technology for the energy transition.



## 📸 Screenshots
![Screenshot_Game_1](https://github.com/user-attachments/assets/cd60795c-b0a6-4b95-b12e-f70512177c19)
*Gameplay screen*

![Screenshot_Game_2](https://github.com/user-attachments/assets/5e0ea008-3377-4f9d-816c-a7cef18fde3b)  
*Another Gameplay screen*

![Screenshot_LevelEnd](https://github.com/user-attachments/assets/9fe47a89-1835-4e09-8711-708ce9101f7a)
*Level completed screen*

![Screenshot_HeatPumpMaster_InterestingFacts](https://github.com/user-attachments/assets/cfa81c00-5475-40e5-bbf4-95f459def184) 
*Interesting facts about heat pumps* 

![Screenshot_HeatPumpMaster_Menu_rounded](https://github.com/user-attachments/assets/34db8206-95b1-40e8-b1c3-75912aa18503)  
*Main menu*





## 🔧 Technologies Used

- **Java** (Android SDK)
- **SQLite** – for defining level design data
- **Firebase Realtime Database** – for online high score leaderboard




## 🚀 Getting Started

1. **Clone the repository**

    ```bash
    git clone https://github.com/thomasdengiz/HeatPump_Master.git
    ```

2. **Open in Android Studio**

    ```bash
    - Launch Android Studio
    - Select "Open an Existing Project"
    - Choose the cloned folder
    - Wait for Gradle sync to complete
    ```

3. **Run the app**

    ```bash
    - Connect an emulator or physical device
    - Press the green "Run ▶️" button or use Shift+F10
    ```

> **Note:** To enable Firebase features, place your `google-services.json` file in the `/app/` folder. Firebase Realtime Database is not needed for the game. It is only used for the highscore list.

<!--
## 📦 Building the APK

```bash
1. In Android Studio, go to:
   Build > Build Bundle(s) / APK(s) > Build APK(s)

2. After the build completes, find the APK at:
   app/build/outputs/apk/debug/app-debug.apk

3. Install the APK on your Android device or emulator.


## 📱 Get It on Google Play
<p align="center">
  <img src="https://github.com/user-attachments/assets/f14433c9-1a6f-4428-ba4c-a41654b30094" alt="ic_launcher_foreground" width="150"/>
</p>
-->


## 🛡️ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


## 📚 External Libraries

This project uses the following external libraries. Please review their licenses and repositories for details:

- **Firebase Android SDK**  
  License: [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0)  
  Used for: Realtime database and Firebase services.  
  Repo: [https://github.com/firebase/firebase-android-sdk](https://github.com/firebase/firebase-android-sdk)

- **Glide**  
  License: [BSD, part MIT and Apache 2.0](https://github.com/bumptech/glide/blob/master/LICENSE)  
  Used for: Image loading and caching.  
  Repo: [https://github.com/bumptech/glide](https://github.com/bumptech/glide)

- **SQLiteAssetHelper**  
  License: [Apache License 2.0](https://github.com/jgilfelt/android-sqlite-asset-helper/blob/master/LICENSE.txt)  
  Used for: Managing SQLite databases shipped with the app.  
  Repo: [https://github.com/jgilfelt/android-sqlite-asset-helper](https://github.com/jgilfelt/android-sqlite-asset-helper)


All included libraries are permissively licensed and compatible with this project’s [MIT License](LICENSE).

If you use or distribute this project, please respect the licenses of these third-party components.


## 🎵 Music Credits

This game features royalty-free background music from [FreePD.com](https://freepd.com/) by Kevin MacLeod for the levels as MP3 files under the [**Creative Commons CC0 1.0 Universal (Public Domain)**](https://creativecommons.org/publicdomain/zero/1.0/legalcode) license :

- 🎧 *Fresh Focus*  
- 🎧 *Modern Island Jam*  
- 🎧 *Natural Vibes*

You are free to use, modify, and distribute these tracks without attribution. I gratefully acknowledge and appreciate the creator’s work.




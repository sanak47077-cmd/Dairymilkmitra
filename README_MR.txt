डेअरी मित्र Android प्रोजेक्ट

हा Android Studio मध्ये APK बनवण्यासाठीचा प्रोजेक्ट आहे. या वातावरणात Android SDK/Gradle उपलब्ध नसल्यामुळे तयार APK थेट compile करता आलेला नाही.

APK बनवण्याची पद्धत:
1. संगणकावर Android Studio स्थापित करा.
2. हा ZIP extract करा.
3. Android Studio > Open > DairyMitra फोल्डर निवडा.
4. Gradle sync पूर्ण होऊ द्या आणि SDK Platform 35 स्थापित करा.
5. Build > Build Bundle(s) / APK(s) > Build APK(s) निवडा.
6. APK साधारण app/build/outputs/apk/debug/app-debug.apk येथे मिळेल.

टीप: हे सध्याच्या HTML डेमोचे WebView wrapper आहे. माहिती स्थानिक ब्राउझर/WebView storage मध्ये राहते; फोन बदलल्यास किंवा app data clear केल्यास डेटा जाऊ शकतो. हे cloud/database app नाही.

# মোবাইল থেকে APK বানানোর সহজ নিয়ম

১. GitHub-এ নতুন Repository খুলুন।
২. এই ZIP-এর সব ফাইল/folder upload করুন।
৩. Upload করার পর Repository → Actions এ যান।
৪. `Build Student Somiti APK` workflow দেখা যাবে।
৫. `Run workflow` চাপুন (যদি push-এ নিজে শুরু না হয়)।
৬. Build শেষ হলে workflow-এর নিচে `Artifacts` থেকে `student-somiti-apk` download করুন।
৭. ZIP খুললে `app-debug.apk` পাবেন।

নোট: GitHub Actions নিজেই Android SDK/Java সেটআপ করবে।

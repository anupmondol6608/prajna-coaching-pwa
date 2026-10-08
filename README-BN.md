# প্রজ্ঞা কোচিং সেন্টার — PWA v1

এই package-টি আপনার existing Google Apps Script Web App-কে installable PWA shell হিসেবে চালায়।

## গুরুত্বপূর্ণ
- Google Sheets / Apps Script backend পরিবর্তন করা হয়নি।
- PWA shell-এ আপনার নতুন “প্রজ্ঞা Coaching Center — শিক্ষা, শৃঙ্খলা, সাফল্য” logo ব্যবহার করা হয়েছে।
- Service worker শুধু PWA shell/assets cache করে। Google Apps Script-এর live data offline করা হয়নি।
- `index.html`-এর `APP_URL`-এ আপনার বর্তমান deployment URL দেওয়া আছে।

## Publish
GitHub Pages / Firebase Hosting / নিজের HTTPS hosting-এ পুরো folder upload করুন।

তারপর Chrome-এ প্রকাশিত URL খুলে Install App নির্বাচন করুন।

## Source project
Existing Apps Script project আলাদা থাকবে:
Google Apps Script -> Google Sheets -> current Web App

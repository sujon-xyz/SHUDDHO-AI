# SHUDDHO ΑΙ

**SHUDDHO ΑΙ** হল একটি এআই-চালিত ওয়েবসাইট যা মানুষের বাংলা এবং ইংরেজি লেখার গ্রামার ঠিক করে দেয়। আমাদের লক্ষ্য হল ভাষার সঠিক ব্যবহারের মাধ্যমে যোগাযোগ আরও সহজ ও সঠিক করা। 🌟

## অফিসিয়াল ওয়েবসাইট

আমাদের অফিসিয়াল ওয়েবসাইটে দেখুন: [SHUDDHO ΑΙ](https://shuddho-ai.vercel.app/) 🌐

## এপিআই ডকুমেন্টেশন

আমরা দুটি প্রধান এপিআই অফার করি যা বাংলা এবং ইংরেজি লেখার গ্রামার ঠিক করতে সাহায্য করে। 📜

### ইংরেজি গ্রামার ঠিক করার এপিআই

এন্ডপয়েন্ট: `https://api.shothik.ai/api/fix-english-grammer` ✍️

`data Json {"data":"Give me pain I will give you money someone said this word one of the legends"}`

`response {
  "content": "\"Someone, one of the legends, said, \u0027Give me pain, and I will give you money.\u0027\"\n"
}`

### বাংলা গ্রামার ঠিক করার এপিআই

এন্ডপয়েন্ট: `https://api.shothik.ai/api2/fix-bangla-grammer` ✍️

`data Json {"data":"ভাবছি আপনাদের জন্য মোবাইল ব্যাংকিং এর কোন ফিশিং পেজ বানালে ভালো হয় বিকাশ তো বানালাম এখন কোনটা বানালে ভালো হয়? \n\nনিচে কমেন্ট করে বলতে পারেন আপনার মতামত।","mode":"standerd","synonym":"Basic","conversationId":1718380142405}`

`response {
  "success": true,
  "message": "Event triggered successfully!",
  "content": "ভাবছি আপনাদের জন্য মোবাইল ব্যাংকিং এর কোন ফিশিং পেজ বানালে ভালো হয়। বিকাশ তো বানালাম, এখন কোনটা বানালে ভালো হয়? \n\nনিচে কমেন্ট করে বলতে পারেন আপনার মতামত। \n"
}`

## এপিআই ব্যবহারের বিস্তারিত

1. **ইনপুট ডাটা তৈরি করুন:** ইনপুট ডাটা JSON ফরম্যাটে প্রেরণ করতে হবে। 📝
2. **এন্ডপয়েন্ট এ অনুরোধ পাঠান:** সংশ্লিষ্ট এপিআই এন্ডপয়েন্ট এ HTTP POST অনুরোধ পাঠাতে হবে। 📬
3. **আউটপুট গ্রহন করুন:** এপিআই থেকে প্রাপ্ত JSON আউটপুট ব্যবহার করে সঠিক গ্রামার সহ টেক্সটটি প্রদর্শন করুন। 📥

## উদাহরণ

**গ্রামার ছাড়া বাক্য:**  
সব ছেড়ে চলে যাচ্ছে মার হৃদয়ে এই মন তো চাচ্ছেনা আর এই পৃথিবীতে তবে কি থাকবো এই পৃথিবীতে আমি কে ধরে রাখবে আমায় ❌

**SHUDDHO ΑΙ আউটপুট:**  
সব ছেড়ে চলে যাচ্ছে মার হৃদয়ে। এই মন তো চাচ্ছেনা আর এই পৃথিবীতে। তবে কি থাকবো এই পৃথিবীতে? আমি কে ধরে রাখবে আমায়? ✔️

**গ্রামার ছাড়া বাক্য:**  
Once upon A Time legend said feel pain except pain and no pain those who don't know pain ❌

**SHUDDHO ΑΙ আউটপুট:**  
Once upon a time, legend said that those who have never felt pain cannot feel any pain except for pain itself. ✔️

### 🎁 Happy Coding! 🎁

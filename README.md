# 5 Problem Solution

## Problem 1: Reverse a String (String উল্টানো)

- এই সমস্যায় একটি string কে উল্টো করে দেখাতে বলা হয়েছে।
- আমি শুরুতে result নামে একটি খালি string নিয়েছি।
- এরপর for loop দিয়ে string-এর শেষ দিক থেকে শুরু করে প্রথম দিক পর্যন্ত এক এক করে character নিয়েছি।
- প্রতিবার character টা result এর সাথে যোগ করেছি।
- এইভাবে loop শেষ হওয়ার আগেই পুরো string উল্টো হয়ে যায়।
- শেষে সেই উল্টো string টা return করেছি।

## Problem 2: Count Vowels (Vowel সংখ্যা বের করা)

- এখানে একটি string-এর ভেতরে মোট কয়টি vowel আছে সেটা বের করতে হবে।
- প্রথমে "aeiou" এই vowel গুলো একটি string-এর মধ্যে রেখেছি।
- এরপর count নামে একটি variable নিয়েছি vowel গোনার জন্য।
- for loop দিয়ে string-এর প্রতিটা letter check করেছি।
- যদি কোনো letter vowel হয়, তাহলে count এক বাড়িয়েছি।
- সব letter check শেষ হলে count return করেছি।

## Problem 6: Sum of All Numbers (Array-এর সব সংখ্যার যোগফল)

- এখানে array-এর সব সংখ্যাকে যোগ করতে হবে।
- আমি শুরুতে sum এর মান ০ ধরেছি।
- তারপর loop চালিয়ে array-এর প্রতিটা সংখ্যা এক এক করে sum এর সাথে যোগ করেছি।
- সব সংখ্যা যোগ হয়ে গেলে sum return করেছি।
- এইভাবেই total যোগফল পাওয়া যায়।

## Problem 7: Find Even Numbers in an Array (Even সংখ্যা বের করা)

- এই problem-এ একটি array থেকে শুধু even সংখ্যা আলাদা করে বের করতে হবে।
- আমি প্রথমে evens নামে একটি empty array নিয়েছি।
- এরপর loop চালিয়ে array-এর প্রতিটা সংখ্যা check করেছি।
- যদি কোনো সংখ্যা ২ দিয়ে ভাগ করলে ভাগশেষ ০ হয়, তাহলে সেটাকে even ধরে evens array-তে যোগ করেছি।
- loop শেষ হলে evens array-টাই return করেছি।

## Problem 10: PingPong Challenge

- এই সমস্যায় ১ থেকে ২০ পর্যন্ত সংখ্যা console করতে হবে নির্দিষ্ট কিছু নিয়ম অনুযায়ী।
- আমি for loop ব্যবহার করে ১ থেকে ২০ পর্যন্ত loop চালিয়েছি।
- যদি কোনো সংখ্যা ৩ এবং ৫ দুটো দিয়েই divisible হয়, তাহলে "PingPong" console করেছি।
- শুধু ৩ দিয়ে divisible হলে "Ping" console করেছি।
- শুধু ৫ দিয়ে divisible হলে "Pong" console করেছি।
- আর কোনো condition না মিললে সংখ্যাটাই console করেছি।
- এখানে condition লেখার order ঠিক রাখা খুব জরুরি।
